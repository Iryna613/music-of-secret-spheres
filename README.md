# Music of Secret Spheres

This is a physics-based simulation task inspired by a fictional teleportation scenario featuring Rick and Morty.  
The program explores the dynamics of ping-pong balls interacting with a polished steel hemisphere in a sealed stone chamber.

## 📖 Scenario

During a routine visit to Dr. Biodolsky, Rick and Morty accidentally teleported into a mysterious chamber with no exits.  
In the center of the room stood a stone cube with a mirror-polished steel hemisphere of radius 150.0 mm embedded on top.  
Plastic ping-pong balls, branded with a Chinese marketplace logo, were falling from a pipe above and striking the hemisphere, producing melodic impacts. After hitting the hemisphere, the balls bounced off and vanished.

Ancient inscriptions revealed that a teleportation window could be activated by the correct melody—one that can be generated if a ping-pong ball bounces exactly **three times** on the hemisphere.

Morty noticed that:
- The pipe is initially vertical, centered above the hemisphere.
- Balls fall from the pipe with **zero initial velocity**.
- The pipe outlet can be adjusted vertically between **300.0–1000.0 mm** above the stone surface.
- The horizontal position of the pipe outlet can be moved within a circle of **182.0 mm radius** centered on the hemisphere.

## 🧪 Goals

1. **Ideal Case**:  
   Determine possible pipe positions and corresponding regions of the hemisphere where a ball (as a point mass) can bounce **exactly three times**, assuming **perfectly elastic collisions**.

2. **Realistic Case**:  
   Use standard tournament ping-pong ball properties:  
   - Diameter: 40.3 mm  
   - Mass: specified above  
   - Bounce height: 250 mm when dropped from 305 mm onto a steel block

3. **Tilted Pipe** (optional):  
   Consider the pipe tilted up to horizontal, introducing a horizontal component of initial velocity increasing linearly with angle (up to 5.0 mm/s).  
   Does this increase the number of teleport destinations?

4. **Ball Deformation** (optional):  
   Account for **maximum deformation of 0.7 mm** during impact.

5. **Ball Variability** (advanced):  
   Real ping-pong balls vary slightly:  
   - Diameter: 40.3 ± 0.06 mm  
   - Mass: 2.70 ± 0.03 g  
   - Bounce height: 240–260 mm

   A teleport will work if **at least one out of 24 balls** in a sequence produces the correct melody.  
   Given uniformly distributed parameters, determine how the target region on the hemisphere must change to achieve **50% success probability**.

> Only one ping-pong ball is present in the room at any given time.
