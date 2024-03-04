---
assignment: 03_char_2_string_methods
dir: levels/Level0/Module4/src/_03_char/_2_string_methods
lesson: 03_char
level: Level0
module: Module4
oassignment: 2_string_methods
opath: levels/Level0/Module4/src/_03_char/_2_string_methods
title: 03 Char 2 String Methods
---
# 03 Char

{{ forkrepo(fm_level, fm_module) }}

{{ reporef(fm_level, fm_module) }}






## String Methods

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
charAt()length()

### Goal:

Use charAt and length methods to access information in a String variable.

### Steps:

1. Create a String variable and initialize it with some characters (at least 3).
2. Use the charAt method to print the 3rd character in the String (remember, computers start counting at zero).
3. Use the length method to print how many characters are in the String.
4. Use a for loop to examine each character in the String, and when you find one that matches the character you are looking for, print its index.




## Pi Aloud

{{ javaref(fm_level, fm_module,fm_lesson,fm_assignment, fm_dir) }}


<hr/>
<img src="./piAloud.png"/>

### Goal:

Use charAt and length methods to access the digits of pi in a String variable.

### Steps:

1. Place the first 20 digits of pi into a String variable.
2. Print out the first 3 digits of pi. Remember the first digit will be pi.charAt(0).
3. Use a for loop to print each digit of pi on a new line.
4. If your computer can play sounds, use the speak method to say each digit of pi using a loop.
5. [CHALLENGE]

After printing the first 3 digits of pi, ask the user for the next digit using the getInputFromUser() method

Compare the users' char to the next digit of pi

If they are correct, print out "correct". If they are not, print "incorrect"


