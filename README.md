# Wordle-filter


A web application which helps the user play the game Wordle [https://www.powerlanguage.co.uk/wordle/].


Here is a screen shot of my application. 

![Screen Shot 2022-01-17 at 09 58 05](https://user-images.githubusercontent.com/85199675/149748343-79687218-7892-47be-9557-0a9abcd256bf.png)










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
