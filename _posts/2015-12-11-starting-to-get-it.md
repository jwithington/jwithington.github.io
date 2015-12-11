---
layout: post
title: Starting to *get* it
---
I'm working over on [freecodecamp][fcc] now, learning JavaScript with a few goals:

- finish their program in Front End, Full Stack, and soon, [Data Visualization and Backend][fccmed] work
- work on their non-profit projects (for a better world!) so that 
- I can build projects that help me get work in the field (for a better me!)

Today, I was working on one of their algorithm challenges ([Bonfires][bon], in [FCC][fcc]-speak). It's [an exercise in truncating strings][trunc] that I'd started last night and had some success with, but I'd set it down to work on it today.

I was able to figure it out in a way that made me really feel like I'm starting to *get* this. Not just parroting what others show me; really building my skills. It's a rush, and it's really exciting.

Here's the code. It's yet another start in my world of starts. 

<script src="https://gist.github.com/anonymous/25516460412e7af66feb.js"></script>

[fcc]: http://www.freecodecamp.com/
[fccmed]: https://medium.freecodecamp.com/learn-to-code-by-coding-d1e241de81c0#.3kahg68km
[bon]: http://www.freecodecamp.com/map#basic-algorithm-scripting
[trunc]: http://www.freecodecamp.com/challenges/bonfire-truncate-a-string#?solution=function%20truncate(str%2C%20num)%20%7B%0A%20%20%2F%2F%20Clear%20out%20that%20junk%20in%20your%20trunk%0A%20%20if%20(num%20%3C%3D%203)%20%7B%0A%20%20%20%20str%20%3D%20str.slice(0%2C%20num)%20%2B%20'...'%3B%0A%20%20%7D%20else%20if%20(num%20%3E%3D%20str.length)%20%7B%0A%20%20%20%20return%20str%3B%0A%20%20%7D%20else%20%7B%0A%20%20%20%20str%20%3D%20str.slice(0%2C%20num%20-3)%20%2B%20'...'%3B%0A%20%20%7Dreturn%20str%3B%0A%7D%0Atruncate(%22A-%22%2C%201)