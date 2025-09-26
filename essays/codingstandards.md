---
layout: essay
type: essay
title: "The Importance of Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-09-25
published: true
labels:
  - Code Maintainability
  - Software Engineering
---

<img width="400px" class="rounded float-start pe-4" src="../img/codingstandards/cantread.avif">

## Coding Standards In a Collaborative Setting

Imagine this, you're working at a new company and you are code reviewing 5 files each written by different people. Each of these files uses a different naming style, indentation style, and overall structure. One person uses tabs while another uses spaces, one file uses camel case while the other uses snake case or even both. Functions are declared inconsistently across files and comments are everywhere. You finally finished reviewing and it feels like it took you twice as long as it should have and you're grabbing medication for the headache you just contracted. 

This scenario shows why coding standards matter. When working with other people, it is beneficial to have a shared approach to writing code. Without a shared approach, small projects can become messy and hard to maintain. Teams will slow down and bugs will find their way in. Coding standards have a purpose to prevent this by ensuring that code is functional, readable, and consistent.

Coding standards greatly help readability. When code has a consistent format, it becomes easier to read, understand, and debug. The person reading your code doesn't have to waste their energy guessing what your function does or finding where your nested for loop ends. Instead, the person reading your code can use that energy to find the real problems within your code. This is important in large and long term projects because multiple people will view what you wrote over time. 

## How ESLint Helped Me

When I started using ESLint, I found it quite annoying. I didn't like seeing all of the warnings while I was writing code and it felt like ESLint was constantly bothering me with things like missing spaces and unused variables. It bothered me less the more I used it but I also started to find it more valuable as time went on. I enjoyed seeing my code organized and consistent. I also found it very practical when reading code that my classmates were showing me. Since they were using ESLint too, their code formatting was obviously similar to mine and it made it a lot easier to understand because I didn't have to deal with unfamiliar formatting. There was also a specific instance where I was trying to use a variable from a seperate file in a function and ESLint gave me an "unused variable" warning despite that variable being used in the function. But that warning actually ended up helping me to realize that there was something wrong with the way that I was importing it, and this happened all before running the code. ESLint went from being a nuisance to being a tool that helped speed up my debugging and collaboration.

