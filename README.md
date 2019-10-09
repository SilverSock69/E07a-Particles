# E07a-Particles

In this repository we will be playing and configuring particles. In this python file, when the mouse is clicked then particles/effects should be the outcomes effect. 
Editing line 113 allows the particle that is shown when the mouse is clicked to be a specific one. In my repository, I made it a fire particle
I also edited the python file in lines 43-53 to show the colors yellow and green
I made the actual fire yellow, while the bits flinging out the flame are green


Playing with particles and emitters

This is an opportunity for you to play with some particles. As you hold down the mouse button, particles are generated and appended to self.particle_list. You will have the opportunity to play with the parameters for generating the particles to explore different effects.

The sprites that may be used for this project are in the assets table (there are a lot of them!). I have removed the black backgrounds, but they were downloaded from [https://kenney.nl/assets/particle-pack](https://kenney.nl/assets/particle-pack). If you want to change the image, you can do so on line 113.

The sprites are being colorized with the colors on lines 43–54. If you need a reference for the open color set, it is available at [https://yeun.github.io/open-color/](https://yeun.github.io/open-color/). The color names are lower-case and an underscore separates the name and the number. If you wanted Pink 9 (#a61e4d), for example, you could reference it as 
```open_color.pink_9```

The second value in the tuple on lines 43–54 are the number of frames for that color. The particle will count down through each step in that list before self-destructing.

The particles can be initialized (on line 113) with a position (x, y), an initial velocity (dx, dy), an acceleration (ax, ay). They should be given an initial scale, but they can also decay in size.

To select a random float in a range, you can use random.uniform(a,b). This will select a random decimal value between a and b.

Some constants have been defined on lines 17–28. Feel free to adjust those, too.

Your assignment is to choose one of the following: fire, smoke, rain, explosion

Adjust the parameters to generate particles that resemble what you have chosen when the user pushes the mouse button.

As always, edit the LICENSE and README.md.