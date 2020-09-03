# p5.play-boilerplate

Boiler plate for p5.play

1. Physics Engine :
   We need physics engine so that in our game world, we can make the objects look like actual physical bodies.

2. We use an online available physics engine - matter.js

3. In matter.js, we have three very important things
   i) Engine - power source to light up the world to be created
   ii) World - the World that we design to add the objects
   iii) Bodies - The bodies that are present in our game world.

4. We can make use of the inbuilt Engine, world and Bodies from matter.js

5. Whenver we create a object in our world, to add it to the world,
   type World.add(world,<body name>);

6. To make the body static, we need to make use of the algorithm, 
     isStatic: true

7. To give bounciness to the body, make use of the algorithm
    restitution: 1.0

    (restitution varies from 0 to 1 generally);

8. Never forget to update the engine inside the draw function.
