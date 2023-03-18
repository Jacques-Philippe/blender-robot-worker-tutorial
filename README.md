# Overview

We're following [this tutorial](https://www.youtube.com/watch?v=9LMEUXPxl8g&list=PLsGl9GczcgBvuBDsj9dA1Aa_arhcJib-s&ab_channel=RyanKingArt)

# Steps

1. Create robot's head
   1. Cube
   1. Mirror about Y
   1. Create robot face front
   1. Create robot face rear
   1. Add details
      1. vent
      1. visor
   1. Add eyes
   1. Add lights next to eye
1. Create robot's neck
   1. Neck base
   1. Neck details
   1. Shoulder turning components
1. Create robot body

   1. Body shape
   1. Bottom details
   1. Body details
      1. front Pipe
      1. left plaque
      1. rear panel
   1. Create tanks, add straps and wires
   1. Create legs
      1. leg bottom and side details
      1. Wheels
   1. Add lights to front
   1. make face longer

1. Creater robot arms
   1. Shoulder
   1. Arm
   1. Clamp
1. Set render properties
   - Eevee
   - Ambient Occlusion
   - Screen Space Reflections
   - Motion blur
   - autoshop hdr
1. Set light
   - Rectangular Area light orange, blue
1. Set camera
   1. Change resolution to 1440px square
   1. Change focal length
1. Get ready for shading
   - Enable Node Wrangler add-on
1. Create metal material and apply
   1. Create metal material
   1. Apply metal material to all objects
   1. Apply Scale and Rotation to all objects
1. Set up rigging
   1. Set neck as head parent for rotation
   1. Lock head
   1. lock neck bolt
   1. Parent lower neck to neck platform
   1. lock neck platform
   1. Lock and parent arms
   1. Lock and parent all torso parts
   1. Lock and parent legs
   1. Create cube to contain model
   1. Parent body to cube
   1. Parent legs to cube
1. Rename robot hierarchy parts
1. Set up scene
   1. Create hierarchy collections for lights/cam, environment, and robot
   1. Create floor, wall
   1. Create floor and wall textures
   1. Update camera field of view
   1. Pose robot
   1. Add new area light
   1. Add irradiance volume, bake indirect lighting (note: Eevee only)
1. Compositing
   1. Render image
   1. Add color filtering
   1. Add vignette
1. Animation
   1. Adjust camera resolution to 1920x1080
   1. Place robot at animation start
   1. On start robot is
      - leaning forward
      - arms down
      - head down
   1. On arrive robot is
      - leaning back and coming to rest
      - arms are pulled back and down a bit and back to normal
      - head is leaning back with body
   1. Robot looks around
      - looks left a bit, looks down and right, and finally up
      - body follows rightward, turning clockwise
      - arms are pulled by turning movement and come back to rest
   1. Robot speeds off again

# Resources

- [HDR](https://polyhaven.com/a/autoshop_01)
- [metal plate 018](https://3dtextures.me/2019/05/28/metal-plate-018/)
- [metal plate 015](https://3dtextures.me/2019/05/08/metal-plate-015/)
- [voltage sign](https://pixabay.com/vectors/high-voltage-sign-symbol-24145/)
- [radioactive sign](https://pixabay.com/vectors/nuclear-radioactivity-toxic-hazard-34997/)
