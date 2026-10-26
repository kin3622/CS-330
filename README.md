How do I approach designing software?

I started from the reference photo and broke it down. I went through what objects are in it, and which basic shapes could stand in for each one. The desk became a plane, the monitor became two boxes (bezel and screen), the stand a cylinder with two box legs, and each speaker a box, two cylinders, and two torus rings. I then placed objects one at a time and checked the result after each one, instead of building everything at once. The skill I picked up is turning something complicated into a few simple parts, and I can use that for any project where the whole thing feels too big to start. Choosing small, reusable pieces also carried into my code, where a single helper function now draws every part of the scene.

How do I approach developing programs?

My main strategy was changing one thing at a time and testing it. That mattered most with lighting. My lights did nothing at first, so I tested with extreme values and then found out I was only using two lights from the four available. The material’s ambient setting was also washing out the scene, and that it ignored a light’s diffuse color, so I tinted one light through its ambient color instead. I added objects, textures, lights, and camera controls (WASD and QE movement, mouse look, scroll to change speed, and a key to switch between perspective and orthographic views). My approach also changed over time. Early on I copied the same block of code for every shape. By the end I had a MeshHelper function and an enum, so each part of the scene is one call instead of about 25 lines.

How can computer science help me in reaching my goals?

Computational graphics gave me practical skills in 3D math, lighting, cameras, and organizing code.
