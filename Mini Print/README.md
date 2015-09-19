Mini Print
========

Project files specific to the Mini Print project

About
-----
The annual mini print exhibition by MA Print students and staff.

**Format:** 20 x 25 cm paper, and a maximum image size 10 x 8cm 
**Edition:** 60 

Arnolini Bookshop, Bristol
**Preview:** Thursday 3 December, 2015 (5.00 - 7.30pm)

In return for participation, each artist recieves a full set of 30 prints. 5 of the remaining prints from each edition are archived in the CFPR and UWE collections, and the rest are available to buy. 

For more information see:
[Website](http://uwe.ac.uk/sca/research/cfpr/MINI%20PRINT/index.html)

Concept
-------
The subject and medium for each print is dictated by the individual artist

For my print I plan to produce something which relates to the theme of my final project, but also acts as a testing gound for the direction of my work, particularly in terms of execution and style.

Conceptually I am exploring the relationship between digital and physical objects using the theme of games and play - specifically pinball. 

This project will be a chance to execute ideas of skecthing digitally in 3D software and how that object translates to print (or physically in some way)

Progress
-------

#### Proof of concept
I've expored this idea of drawing 3D and translating to print. 
**Examples:**
[Visual Thought](http://jonosandilands.blogspot.co.uk/2015/03/visual-thought.html)
[Particle Memory](http://jonosandilands.blogspot.co.uk/2015/04/particle-thought.html)

I want to expand and refine this. Part of that is to become better at using 3D software. I've decided to focus on using Blender as it is open source and I am finding it easier to work with than Rhino.

#### Experimentation (17 September 2015)
I'm going to start producing a series of test pieces to explore using 3D software as a sketchbook and outputting up to the stage of ready to print files.

I will list these below, and save all seperate experimentation's working files into sub directories

## **001** - 17/9/15
- [Mockup](Experiments/001/MP_experiment_001.png)
- [Blender File](Experiments/001/001.blend)

Notes: Practice creating basic 3D geometry in Blender, testing workflow for exporting the image and processing with diffusion dither for screenprint. 

Trying out a layer of colour but not happy with the murkiness - need to retain (or try to recreate) the vivid RGB colours - few ideas to try (change key colour, and export the colour layers flat). 

Techincal note: because I am creating these for the intention of screenprinting I want to find a workflow I can generate the seperate layers of colour *almost* directly from Blender.

Workflow: 
- **Key Layer** Material white / **Blender** render image / **Photoshop** Diffusion Dither
- **Colour Layer** Material coloured default / **Blender** render image / **Photoshop** Diffusion Dither


## **002** - 18/9/15

- [Mockup - Black key colour](Experiments/002/MP_experiment_002.jpg)
- [Mockup - Purple key colour](Experiments/002/MP_experiment_002-variation.jpg)
- [Blender File](Experiments/002/002.blend)

Imporving the vividness of the representation of colour. 2 versions trying out the two ideas I had from 001 - to export the colour layers flat (with no shading) and change the key colour from black to (in this case) purple. Much happier with these results.

Workflow: 

- **Key Layer** Material white + increased intensity / **Blender** render image / **Photoshop** Diffusion Dither
- **Colour Layer** Material coloured shadeless / **Blender** render image / **Photoshop** Flat artwork as exported

## **003** - 18/9/15

- [Mockup](Experiments/003/MP_experiment_003.jpg)
- [Blender File](Experiments/003/003.blend)

Ok I need to work with more complex shapes, not just the out of the box ones in Blender. Start by drawing a pinball flipper using similar methods to my previous examples. 

Importing Illustrator files as .svg. I'm comfortable drawing in Illustrator so think this could be the best way for me. I had some problems with the export settings from Illustrator to get .svg files into blender [this forum post solved it](http://blenderartists.org/forum/showthread.php?326843-MAJOR-problem-Illustrator-CC-SVG-and-Blender-2-69&s=a68145dbf7fa608fea797b03b7e23c6e&p=2576229&viewfull=1#post2576229). 

[This tutorial](https://youtu.be/VZDR8nCYdvU?t=8m40s) was helpful for working out some more things to know in Blender when importing .svg from Illustrator. (Convert to mesh from curve)

Workflow: 

- **Shape** drawn in **Illustrator** saved as svg / **Blender** import + scale + convert to mesh + extrude etc

## **004** - 18/9/15

- [Mockup - background](Experiments/004/MP_experiment_004.jpg)
- [Mockup - no background](Experiments/004/MP_experiment_004_no_bg.jpg)
- [Mockup - no background - grain mix](Experiments/004/MP_experiment_004_grain_mix.jpg)
- [Blender File](Experiments/004/004.blend)

Curbing my curiosity a bit with this experiment. Basically wondering about going totally flat with the style instead of the grain, which is making things a bit murky looking. There's options to explore here. It may well be about finding a balance.

One with background could be a digital print - I don't have to constrain myself to screenprinting. 
Second just by removing the background maybe helps. Third is a mix with no background and grain (with key colour grey). Liking where it's going.

The concept and qualities I originally wanted to achieve was to create this grainy vision (in a way reacreating a thought from a visual/dreamy memory). The diffusion dither lends itself well to screenprinting too.

Getting more familiar with Blender already, so far this has been a good excercise. I often find myself guided by software, so this was a good test of having an idea and trying to execute is as I envisioned.

## **005** - 19/9/15

- [Mockup](Experiments/005/MP_experiment_005.jpg)
- [Blender File](Experiments/005/005.blend)

Attempting to execute an idea of using a pinball cabinet to the size of the mini print, rotated at an orthographic angle instead of being straight. After playing around a bit I decide that wasn't working, as it looked like it was floating, hence why adding the legs.

This is really an excercide in mapping images onto the 3D object - UV mapping.

The designs are based on an old pinball machine that I am currently restoring. I'm going to need to recreate some of the graphics on it so I figure it would be good practice to recreate it in 3D too. If I go forward with this I'll add the playfield and maybe the backbox too.

It'll be even better screenprinted, but will need more work to seperate and retain a flat shadowed look.

[This tutorial](https://www.youtube.com/watch?v=f2-FfB9kRmE) and [This one](https://www.youtube.com/watch?v=zh280Id_eXg) were helpful.

Workflow: 

- **Blender** UV mapping  - export UV Map and place graphics in **Photoshop** Import mapped art into place

