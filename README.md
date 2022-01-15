# Wordle-filter


This is a script which helps a user play the game Wordle [https://www.powerlanguage.co.uk/wordle/]





![Screen Shot 2022-01-15 at 15 46 11](https://user-images.githubusercontent.com/85199675/149628004-af584938-ac2c-490c-9344-d057a9841413.png)










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

Enter prompts given by Wordle.com into a script which returns the possible solutions. 


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

This is my first project using a large data set. I

### Continued development

- Add user interface which takes users letters and gives them the possible words.
- Add 'cheat' function which reveals the answer for the day. 
