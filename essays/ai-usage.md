---
layout: essay
type: essay
title: "Putting the AI in PAIN"
date: 2023-11-21
published: false
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

I'd like to take a step back from the STEM field for a moment and focus on the impacts of AI in the arts. I am a digital artist, and AI has been a nightmare for the art community. AI art generators have been able to create nothing short of masterpieces in a matter of minutes or even seconds. There are some dead giveaways for AI images, such as hands with too many fingers, lack of logic, strange background, etc.

The frustrating thing is that AI _can_ be used to help artists, but that isn't the main focus of development. For example, Clip Studio Paint by Celsys recently launched a 2.0 version of their drawing software that includes a feature called "Shading Assist" which looks over a drawing with flat colors and intelligently applies shading. This feature was well received by digital artists because it's not generating art, but helping artists to enhance their art and study shading. Additionally, many artists who use Clip Studio Paint are comic artists who have deadlines to meet. This tool helps speed up the process and aids them in completing their chapters in time.

However, tools like these don't seem to be the focus of many developers. Many seem to only be focused on creating more and more sophisticated generators that become more and more believable. I can only hope that artists don't lose anymore jobs or opportunities to AI.

## Challenges and Opportunities

Like I mentioned earlier, AI is smart, but not the smartest. It doesn't solve every problem, and many of the solutions that it provides are not the best solution and sometimes, not even a solution at all. My main reason for not using AI besides wanting to actually learn the material is that I don't trust it. Maybe I'm not good at generating prompts, but it's too much of a mixed bag for me.

Also, permitting use of AI in an educational setting is a bit iffy to me. Some students might use it responsibly, using AI as a Q&A resource, but others might use it as an answer sheet. For now, AI might be acceptable because there's a lot of knowledge that you need to have to actually understand the code that is generated, but as AI becomes more sophisticated, this could pose an issue. 

## Comparative Analysis

Using AI and Software Engineering are two completely different skills. That's not to say that they're mutually exclusive, but they are separate, distinct things. I can't and won't speak to how AI impacts learning this course since I didn't use it for the learning portion of this class. However, I do believe that trying to learn both how to use AI and Software Engineering simultaneously likely detracts from both learning experiences.

## Future Considerations

I don't want to sound like a broken record, but I think to integrate AI into Software Engineering education, a) it should be taught as a different skill, and b) it should be used as a resource---not a replacement for coding. I don't know if it helps or hinders learning from personal experience as I did not use it for WODs.

## Conclusions

AI is not yet sophisticated enough to be useful to beginner Software Engineers nor advanced Software Engineers. Whether or not it is a good thing in education is questionable, and its long term effects on our workforce are yet to be seen, whether that be helping people get accreditation without actually gaining skills or outright replacing workers. As a society, I think we need to start reevaluating our development of AI, and we need to seriously start asking, "Should this be made?" rather than, "Can this be made?"

AI is already wrecking the art community, simulating human faces and voices, and though people try to limit its influence, it seems like it just keeps going. I'm all for freedom from government regulation, but once this technology begins to threaten peoples' livelihoods, we need to start limiting development before we end up in _The Matrix_ or _Terminator_ or some dystopian society where humans are almost totally obsolete. Hopefully, that stays in sci-fi.