# Defined #

This document outlines the principles behind For The Web (FTW.) FTW is an experiment in web architecture that embraces core web technologies and hopes to be boring.

## Web-Centric ##
I like the core web technologies. They got us here. FTW strives to hew as close to the underlying technologies as possible. While APIs may offer a prettier face to existing W3C or ECMA APIs they shouldn't, under most circumstances, reject the basic pattern. The framework should be familiar to anyone who knows the basics of web development. 

## JavaScript Runs in the Browser ##
While there will be a build system for production, development must be possible without a compilation step. JavaScript just runs in the browser.

## Minimize Dependencies ## 
The main output of the project should be able to be run as a standalone folder. The build system, development server and project plumbing will require `node` and `npm` but you should be able to download FTW, unzip it and run it with no other steps. 

## Does Just Enough to Solve Most Problems ##
This isn't designed to solve the biggest, most complicated problems. Most people don't actually need to solve the world's biggest problems. 