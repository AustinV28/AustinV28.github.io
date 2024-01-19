---
title: Projects
layout: project
type: project
image: https://sklc-tinymce-2021.s3.amazonaws.com/comp/2023/02/233_1677505293.png
title: "Character Count Program"
date: 2023
published: true
labels:
  - C
  - SSH
summary: "A C program I created for my ICS 212 class that reads characters until EOF, counts uppercase and lowercase letters, and displays the character counts."
---

<img class="img-fluid" src="https://sklc-tinymce-2021.s3.amazonaws.com/comp/2023/02/233_1677505293.png" alt="Description" width="50%">

This was an assignment I had for my ICS 212.

The program reads one character at a time until reaching EOF, using the `getchar()` function to obtain characters from the user. It counts the uppercase and lowercase letters of the alphabet, storing the counts in an array of 26 elements. The code ensures the character range is from 'a' to 'z' and from 'A' to 'Z' without using 26 if-statements or a 26-case switch-statement. The array is a local variable in the `main()` function and is passed to other functions as required. The program concludes by printing out the letters and their counts.

In this assignment, I learned how to:
- Use SSH for character input.
- Efficiently count and store occurrences of letters in an array.
- Design functions to modularize code.

Here is the code:

{% gist AustinV28/9702054d371b92d40a4385427ff6e4e7 %}
