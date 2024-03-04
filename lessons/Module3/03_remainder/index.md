---
assignment: 03_remainder_1_intro_to_remainder
dir: levels/Level0/Module3/src/_03_remainder/_1_intro_to_remainder
lesson: 03_remainder
level: Level0
module: Module3
oassignment: 1_intro_to_remainder
opath: levels/Level0/Module3/src/_03_remainder/_1_intro_to_remainder
title: 03 Remainder 1 Intro To Remainder
---
# 03 Remainder

{{ forkrepo(fm_level, fm_module) }}

{{ reporef(fm_level, fm_module) }}






## Introduction to Remainder

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


The remainder operator is represented as the percent sign %. This just means the remainder after division. You may also hear this be called modulo.
A common use for remainder is to test if a number is odd or even.
To do this test, you divide the number by 2.
If the remainder is zero, the number is even, but if the remainder is one, the number is odd. In code this would look like this:
```
int number = new Random().nextInt(100);
 if (number % 2 == 0) {
     System.out.println("number is even");
 }
 else {
     System.out.println("number is odd");
 }
```
Another use for remainder could be to track every 20 times a loop is executed, as follows:
```
for (int i=1; i<=1000; i++) {
    // do some code
    if (i % 20 == 0){
        System.out.println("20 more repeats completed");
    }
}
```

### Eclipse Recipes

FizzBuzz

### Processing Recipes

Bullseye
Bumble Bee



## Bullseye

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img alt="Bullseye image" src="http://level0.jointheleague.org/modules/Mod3Recipes/images/bullseye.png"/>

### Goal:

Use remainder to make a bullseye like the image above.

### Steps:

1. This recipe practices using remainder to detect odd and even numbers.
2. Find the Bullseye recipe program ( bullseye.pde ) and open it using Processing.
3. Follow the instructions in the code to make a striped bullseye like the one in the picture.
4. Make sure you SAVE YOUR CODE when you are done.




## Bumblebee

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img alt="Bumblebee image" src="./bumbleBee.png"/>

### Goal:

Draw the bumblebee using a for loop and remainder

### Steps:

1. This recipe practices using remainder and calling methods that use parameters.
2. Find the Bumble Bee recipe program ( bumble_bee.pde ) and open it using Processing.
3. Follow the instructions in the code to make a long stripy bumble bee like the one in the picture.
4. Make sure you SAVE YOUR CODE when you are done.




## Fizz Buzz

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
1, 2, fizz, 4, buzz, ...

### Goal:

Use a for loop and remainder (%) to build FizzBuzz - a children's counting game.

### Steps:

1. Write a loop to print all the numbers between 1 and 20.
2. Now modify the  program so that any time a number is divisible by 3, print "fizz" in place of the number. And instead of printing numbers that are divisible by 5, print "buzz". For numbers that are divisible by both 3 and 5, print "fizzbuzz".
3. If your code is correct, the program will now print:

1, 2, fizz, 4, buzz, fizz, 7, 8, fizz, buzz, 11, fizz, 13, 14, fizzbuzz, 16, 17, fizz, 19, buzz


