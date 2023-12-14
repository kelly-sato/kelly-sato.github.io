---
layout: essay
type: essay
title: "Reduce Reuse Recycle Solutions"
date: 2023-11-30
published: false
labels:
  - Design Patterns
  - Personal Projects
  - Final Project
---

If I've learned anything this semester in ICS 314, it's that if there's an easy way to do something, just do that. I don't know if that was the intention, but it's what I took away. Perhaps design patterns are just an extension of the philosophy of taking the easy route---if there's an existing solution, just use it. After all, progressing the human race = making life easier!

## Just like IBP

Design patterns in software engineering are general reusable solutions to common problems that arise during software development. They aren't templates or finished designs, but instead, they provide general guidelines for solving specific design problems. Essentially, they are repeatable solution. 

A simple analogy might be to calculus in which a "design pattern" might be Integration By Parts: it's a repeatable, structured way to solve an integral with the product of two functions.

Overall, design patterns are especially useful to speed up coding and also save you a headache. Leveraging existing, _functioning_ solutions will always be better and less stressful than going through the logic each time to solve problems you've already solved. If there's already a solution, why not use it?

## Design patterns in the final project

Mine and my group's final project, [manoaexchange.com](https://manoaexchange.com), is essentially a social networking site for past, present, and prospective study abroad students. The site currently supports creating and saving posts with an image and caption. 

With that in mind, we use the **Observer** design pattern in which we _create_ data that is stored in our MongoDB and _publish_ it to the home page which contains posts. The post creation triggers a state change and the home page is the observer which updates with that trigger.

Additionally, we might also be using the **Factory Method** for uploading images to the [Cloudinary](https://cloudinary.com) image upload service. We use this design pattern for image uploads, including both for posts and for avatars. 

## Design patterns in... my own code...?

 I haven't ever _purposefully_ implemented design patterns into my own code. I'm actually quite prone to doing the opposite: as they say, if it ain't broke, don't fix it, so if my code works, even if it looks really wonky, I just leave it. Yes... it seems my favorite "design pattern" is actually the **Anti Pattern**.
 
Besides that, throughout my whole (short) coding career, I think I have unintentionally used design patterns. For example, the **Command** pattern. When I "made" (copied off the Internet and modified) my first C++ code for an Arduino, that sent some simple commands from a joystick to a motor:
- push joystick right: turn clockwise at _x_ revs/s
- push joystick left: turn counter clockwise at _x_ revs/s
- press joystick down: turn 90 degrees clockwise at _x_ revs/s

There were different classes for each function and the Joystick Controller was a class on its own. This design pattern would have allowed me to go back and add more functions without messing with the Joystick function.

## Conclusion

Design patterns emphasize the value of simplicity. Whether it be a math function or a method or a pattern for creating a component in software, reusability solidifies itself as king.