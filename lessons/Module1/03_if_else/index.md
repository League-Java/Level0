---
assignment: 03_if_else_1_unbirthday
dir: levels/Level0/Module1/src/_03_if_else/_1_unbirthday
lesson: 03_if_else
level: Level0
module: Module1
oassignment: 1_unbirthday
opath: levels/Level0/Module1/src/_03_if_else/_1_unbirthday
title: 03 If Else 1 Unbirthday
---
# 03 If Else

{{ forkrepo(fm_level, fm_module) }}

{{ reporef(fm_level, fm_module) }}






## Unbirthday

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img src="./unbirthday.jpg"/>

### Goal:

Find out if today is the user's birthday!

### Steps:

1. Ask the user for their birthday (mm/dd), e.g. 06/09
2. If it matches today's date, wish them a happy birthday
3. otherwise, wish them a very merry UNbirthday


Optional: Watch [this video](https://www.youtube.com/watch?v=iL2Wm-PcfPo).




## Remarkable

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img src="./wow.jpg"/>

### Goal:

Find out something remarkable about the people in your class. When the user enters a name into your program, they will learn something remarkable about that person.

### Steps:

1. Write the names of all the students on the white board
2. Depending on which user types their name, tell them something remarkable about themselves
3. Have students walk round and try each other's programs




## Secret Message Box

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img src="./messageBox.jpg"/>

### Goal:

Share a secret message!

### Steps:

1. Create a password and store it in a String variable.
2. Using a pop-up, ask the first person for a secret message and store it in a variable.
3. Now use a pop-up to tell the NEXT user that they can only see the secret message if they can guess the passcode.
4. If their guess matches the password, show them the secret message.
5. If the password does not match, pop-up "INTRUDER!!"




## Tasty Tomato

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img alt="Tasty Tomato image.." src="http://level0.jointheleague.org/modules/Mod1Recipes/images/tomato.png"/>

### Goal:

Draw a tomato and take a bite out of it!

### Steps:

1. Find the Tasty Tomato recipe program ( tasty_tomato.pde ) and open it using Processing.
2. Make the tomato red.
3. Make the stem green.
4. Take a bite out of the tomato (see the picture).
5. Only bite the tomato when the mouse is pressed.
6. Make sure you SAVE YOUR CODE when you are done.




## Pizza

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img src="./pizza.jpeg"/>

### Goal:

Make a pizza with whatever toppings you can imagine!

### Steps:

1. Find the Pizza recipe program ( pizza.pde ) and open it using Processing.
2. Set your canvas size in the setup method.
```

size(width, height);
```
3. Draw a biscuit colored ellipse for the pizza base, a red ellipse for sauce and a yellow ellipse inside (for the cheese).
Do this in the setup method. You can use R,G,B values or the Processing Color Selector Tool to help you find the right colors.
```

fill(color);
ellipse(x, y, width, height);
```
4. Get some topping images for your pizza. Some examples are provided for you, but if you want to choose your own toppings you can.


Make a PImage variable for each type of topping at the top of the sketch:
```
PImage pepperoni;
```
Drag and drop the topping image file onto your sketch.
Load the topping image (in the setup method):```
pepperoni = loadImage("pepperoni.png");
```
In the draw method, use the image command to draw the topping somewhere on your pizza:
```
image(pepperoni,200,200);
```
If your topping is too big for the pizza, resize the topping image. Do this in the setup method.
```
pepperoni.resize(30, 30);
```

Repeat the above steps for more toppings.

Add more code so that the toppings are only drawn when the user clicks the mouse (in draw method).
Make sure you SAVE YOUR CODE when you are done. 
                                
OPTIONAL Add a different topping with the right mouse click.
```

if (mousePressed && (mouseButton == RIGHT)) {}
```

OPTIONAL Use a background image to put the pizza in a box.
```

PImage pizzaBox = loadImage("box.jpg");     //in setup method
pizzaBox.resize(width, height);      //to match your canvas size
background(pizzaBox);       //in setup method
```

OPTIONAL: To play a sound when you add a topping....
                                    First download a sound from freesound.org and drop it onto your sketch

                                    Import the minim library Pocessing > tools > add tools > libraries (search minim)
```

import ddf.minim.*;     //at the top of the sketch
Minim minim;     //at the top of the sketch
AudioPlayer sound;    //at the top of the sketch

minim = new Minim(this);      //in the setup method
sound = minim.loadFile("ding.wav");      //in the setup method

// Put next 2 lines where you want the sound to play
sound.play();
sound.rewind();
```
5. Make a PImage variable for each type of topping at the top of the sketch:
```
PImage pepperoni;
```
6. Drag and drop the topping image file onto your sketch.
7. Load the topping image (in the setup method):```
pepperoni = loadImage("pepperoni.png");
```
8. In the draw method, use the image command to draw the topping somewhere on your pizza:
```
image(pepperoni,200,200);
```
9. If your topping is too big for the pizza, resize the topping image. Do this in the setup method.
```
pepperoni.resize(30, 30);
```
10. Repeat the above steps for more toppings.
11. Add more code so that the toppings are only drawn when the user clicks the mouse (in draw method).
12. Make sure you SAVE YOUR CODE when you are done.
13. OPTIONAL Add a different topping with the right mouse click.
```

if (mousePressed && (mouseButton == RIGHT)) {}
```
14. OPTIONAL Use a background image to put the pizza in a box.
```

PImage pizzaBox = loadImage("box.jpg");     //in setup method
pizzaBox.resize(width, height);      //to match your canvas size
background(pizzaBox);       //in setup method
```
15. OPTIONAL: To play a sound when you add a topping....
First download a sound from freesound.org and drop it onto your sketch

Import the minim library Pocessing > tools > add tools > libraries (search minim)
```

import ddf.minim.*;     //at the top of the sketch
Minim minim;     //at the top of the sketch
AudioPlayer sound;    //at the top of the sketch

minim = new Minim(this);      //in the setup method
sound = minim.loadFile("ding.wav");      //in the setup method

// Put next 2 lines where you want the sound to play
sound.play();
sound.rewind();
```


