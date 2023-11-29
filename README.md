# The Minnow Project
*What if we took the "Build Your Own X" idea a little too far?*

## Overview
Minnow is an ambitious project to build an entire tech stack from scratch[^1], including programming languages, operating system and applications, for the sole purpose of playing Pong on the internet. That's the target objective: two people playing Pong on different Raspberry Pi devices, with the Pong application served by a third Raspberry Pi device. Everything from the OS to the web browser implemented from scratch.

## Warning!
I don't know what I'm doing yet! I have a cursory understanding of compilers and operating systems, and a fair amount of experience building web-based applications. I certainly do not have the expertise to be doing _any_ of this. And that's kind of the point. I'll learn along the way! But, I may do things wrong. Feel free to tell me how wrong I am!

## Target Milestones
These is a set of intermediate goals for the project. They are subject to change.

| Milestone | Description | Status |
| -- | -- | -- |
| MinLang Compiler | Before we can do anything, we must have a programming language with which to do it. The first version of the compiler will be developed in Rust. | Not Started |
| Self Host MinLang | Once MinLang is sufficiently developed, we will throw off the harness of Rust and self host MinLang. Once this milestone is achieved, _all_ further development will be done in MinLang | Not Started |
| MinOS Kernel | Our operating system! MinOS will run on Raspberry Pi 4B and will serve as the anchor for all of our applications. | Not Started |
| MinTools | Before moving all development over to MinOS (!!) we'll want to have a small set of applications that will support that effort. Specifics TBD. | Not Started |
| Move to MinOS | With this milestone, all bootstraps are off. No more internet, no more standard tools, we only get to use what's available _in_ MinOS. Terrifying. | Not Started |
| MinNet | Networking for MinOS | Not Started |
| MinServe | MinOS Server | Not Started |
| MinWeb, MinML, MinScript | Our own little web browser with document markup and scripting language | Not Started |
| Local MinPong | Pong in MinWeb for one or two players | Not Started |
| Multiplayer MinPong | The final stage, or finish line, or whatever you want to call it. This is the big one.|

# FAQ
> How long will this take?

I don't know. Probably at least a decade. Maybe two. There will probably be humans living on Mars by the time it's done. Strap in, I guess. 

> But... why?

Because it's hard enough to be just a little unreasonable. And because it will require learning a _ton_ about computer systems. It will be a fun thing to people about at parties, maybe, and when it's finished it might look impressive. Maybe people don't always need a reason to do things.

[^1]: Ish. The project will bootstrap its first programming language, MinLang, using Rust. 
