---
layout: essay
type: essay
title: "Putting the AI in PAIN"
date: 2023-11-21
labels:
  - AI
  - ChatGPT
---

## Table of Contents

- [Introduction](#introduction)

- [Personal Experiences with AI](#personal-experience-with-ai)

  - [Experience WODs](#experience-wods)

  - [In-class Practice WODs](#in-class-practice-wods)

  - [In-class WODs](#in-class-wods)

  - [Essays](#essays)

  - [Final Project](#final-project)

  - [Answering a question in class or in Discord](#answering-a-question-in-class-or-in-discord)

  - [Answering a smart-question](#asking-or-answering-a-smart-question)

  - [Coding example](#coding-example)

  - [Explaining code](#explaining-code)

  - [Writing code](#writing-code)

  - [Documenting code](#documenting-code)

  - [Quality assurance](#quality-assurance)

  - [Other uses](#other-uses)

  - [Experience WODs](#experience-wods)

- [Impact on Learning and Understanding](#impact-on-learning-and-understanding)

- [Practical Applications](#practical-applications)

- [Challenges and Opportunities](#challenges-and-opportunities)

- [Comparative Analysis](#comparative-analysis)

- [Future Considerations](#future-considerations)

- [Conclusions](#conclusions)

## Introduction

As AI evolves, it becomes more intertwined in our world. Whether or not this is a good thing is yet to be decided, but many people, including myself, are leaning towards this being a potentially dangerous tool. In Software Engineering, it might even prove to be a good enough replacement for Software Engineers with how well it can produce code... Or can it?

AI might be incredibly advanced, but in my experience, it's not good enough to replace people (yet). In education, it's still a toss up if what you're gonna get is accurate information or a total fabrication. Just as AI is not completely harmful, but not completely harmless. It is not completely helpful, but not completely useless.

It is what it is, though I try to avoid using it.

## Personal Experience with AI

My personal experience with AI for ICS 314 is limited. I avoided using ChatGPT all semester until the final project, and I haven't used GitHub CoPilot at all. However, I have used it for other classes to help me come up with topic ideas for presentations or check the flow of my essays. I also use it to practice my Japanese, asking ChatGPT, "I'd like to practice having a simple conversation in Japanese, could you help me and correct my mistakes?" For those applications, it has genuinely been helpful.

But when it comes to coding... I'll expand on that below.

### Experience WODs
I did not use AI for experience WODS because I thought it might hinder my understanding of the content.

### In-class Practice WODs

I did not use AI for the in-class practice WODs because I did not plan to use it for the actual in-class WODs. 

### In-class WODs

I did not use AI for the in-class WODs because I thought using it would give a dishonest reflection of my actual understanding of the material. I passed all but one WOD, so I think it's a fair conclusion that not using AI for the experiences and in-class practice WODs made me understand the content better.

### Essays

I have not used AI for writing essays. I've played around with ChatGPT's writing skills in the past, and it comes out sounding very unnatural. At most, I copy-paste what I've already written in to ChatGPT and ask for feedback so _I_ can make those changes, but I don't trust ChatGPT to produce a quality, natural-sounding essay. It'll turn a sentence like, "ChatGPT 's writing is not great, and everything they write sounds like it was passed through a thesaurus" to "ChatGPT's writing lacks finesse, and every piece they compose gives the impression of having been overly reliant on a thesaurus." 

And, yes, I put that sentence through ChatGPT with the prompt, "Can you improve my sentence?" and got that "overly thesaurus-reliant piece".

### Final Project

I have begun using ChatGPT for the final project because there's a lot to do, and we aren't given the answer on how to do all of the things we need like we were with the experiences and WODs. I can't afford to spend a ton of time researching with my course load, so asking ChatGPT for help was the most efficient way. However, I feel like I've wasted more time arguing with ChatGPT than actually getting my code to work. 

For the final project, my group and I are essentially creating a social networking site targeted towards prospective, current, and former study abroad students. I wanted to create animated text on the landing page that advertised some of the places you could study abroad with UH Manoa. I had an array of Strings of all of the places:

`['Japan', 'Korea', ... , 'Australia']`

and I had some code (that's long gone at this point) to animate the text fading in from above and then fading out down. However, I was having an issue with my animations in which it didn't totally look right.

I provided ChatGPT my code and wrote a prompt something along the lines of, "Adjust my code so that the text appears in order and so that the next animation starts instantly." It gave me so many bad "fixes." One fix made the word fade in from above, change to the next word, and then fade out. Another fix somehow broke my entire animation... After about 30 minutes of struggling, and tens of questions thrown at it, ChatGPT finally gave me a good suggestion... Use an animation library. 

To be fair, it fixed my animation issues, but at that point I was done asking ChatGPT questions about anything else. I find myself only using it when I need a starting point for _actual_ research.

### Answering a question in class or in Discord

I never answered a question in class or on Discord, so this doesn't apply to me.

### Asking or answering a smart-question

I never asked or answered a smart-question so this doesn't apply to me either.

### Coding example

I never explicitly asked ChatGPT for example code, but the examples that it gives are sometimes complicated and use JavaScript I'm not familiar with. Other times, it's just pseudocode, or in a different language which isn't super helpful either.

### Explaining code

This is actually something ChatGPT is great at in my opinion. Whenever I don't quite understand some code from an external resource, I can ask ChatGPT what a certain function does or something of the like. It breaks down each component in an easy to understand way.

### Writing code

ChatGPT is not great at writing code, even if you give it directions. While working on this final project, I wanted to create a circle with an icon inside. I asked ChatGPT to write some CSS for that thinking it would just be a quick thing. The circle it coded _was_ a circle, but a _dynamic_ circle whose height and width corresponded to the size of the container it was in... Not exactly what I was hoping when I wrote, "Can you code CSS for a green circle that's 75 px wide?"

But to give credit where credit's due, it was just some small fixes to make it what I wanted it to be.

### Documenting code

Although I did just say that ChatGPT is good at breaking down code justa bit earlier, that still doesn't change the fact that it's a horrible writer. I wouldn't ever use ChatGPT to write documentation for my code, especially when I already know what the code does.

### Quality assurance

The furthest I've gotten with this is asking ChatGPT was a certain error means, especially in the browser console. It explains what the error means and gives a list of solutions (which I don't use because they don't usually work). I don't tend to run into many ESLint issues, so I never had the need to ask ChatGPT for a solution.

### Other uses

At the beginning of the semester, my table mates and I used ChatGPT to come up with team names and we ended up with "BitMaster" as the best pick. Take that as you will.

## Impact on Learning and Understanding

I don't know if there would be an impact on learning, but I believe that I was benefited by not using it. However, in order to use AI to write/fix code, at the stage it's currently at, you would still need to understand a good amount of code for AI use to be meaningful (and effective). It also depends on _how_ a person uses it. If someone just copy-pasted whatever ChatGPT spat at them, then there would be no comprehension or understanding (or working code). If someone actually read ChatGPT's explanations, and it does give a lot, then I can see it being used as a learning tool.

## Practical Applications



## Challenges and Opportunities

## Comparative Analysis

## Future Considerations

## Conclusions
