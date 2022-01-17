# Wordle-filter


A web application which helps the user play the game Wordle [https://www.powerlanguage.co.uk/wordle/].

Here's a screen shot of the web application which I intent to solve. 

![Screen Shot 2022-01-17 at 10 02 07](https://user-images.githubusercontent.com/85199675/149749037-fa16b912-fb05-4dd3-a50d-3406e3205eb0.png)


And this is a screen shot of my application. 


![Screen Shot 2022-01-17 at 10 07 37](https://user-images.githubusercontent.com/85199675/149749812-ed639868-1a00-4c4f-85cc-3552d86999d0.png)








## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)



## Overview

### The challenge

User should be able to:

Enter prompts given by Wordle.com into a website which returns the possible solutions. 


## My process

Firstly I needed a database. I Googled "5 letter word database" to no avail before finally downloading the database from Wordle.[https://www.powerlanguage.co.uk/wordle/]

I then used a simple process to remove any words which do not fit. Here is the process. 
 - filter out any word from teh data base which contains a 'grey' letter. 
 - filter out any word from the database which does not contain a ' yellow letter'
 - filter our any word from the database which does not have a specific letter at a specific integer (green letter)
 - print remaining words 
 - 
### Built with

- Javascript

### What I learned

This is my first 'ground-up' project using Javascript, HTML and CSS.


### Continued development

- Add user interface which takes users letters and gives them the possible words.
- Add 'cheat' function which reveals the answer for the day. 
