---
layout: essay
type: essay
title: ""
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: true
labels:
  - Smart Questions
  - Stack Overflow
---

## "The only stupid question is the one you didn't ask"

This is a phrase I have heard many professors say to make students feel less embarrassed to ask questions in class, espcially in front of their peers. And yes, it's better to ask a question than not to, and in my college experience so far, I have had the fortune of hearing almost exclusively "smart" questions---in Computer Science, those are generally questions that provide relevant context of the problem, symptoms of the problem, and why that problem is stopping the asker from getting to their goal, among other things. That being said, I'd like to petition that the above phrase be changed to "the only stupid question is the one you should feel ashamed to have asked." However, I admit it's not nearly as inviting to people who are genuinely apprehensive to ask for help (like myself), and it's not exactly appropriate for a professor or even other students to publicly shame someone for asking a not-so-smart question.

Fortunately, we have the Internet to do that!

## Downvote, downvote, downvote

Approximately 9 hours ago as of writing, [Karim Gaber proposed that we have a candy store, and a box of 2*n candies.](https://stackoverflow.com/questions/77061160/candy-store-problem-solving-coding-challenge) Flavors are represented by a numeric value and, given an array of different flavors, we must arrange the flavors into matching pairs, e.g. [5, 8, 5, 8, 8, 8] should be divided into three pairs, (5, 5), (8, 8), and (8, 8). Then, the program returns how many pairs there are. **How should this program be written?**

Sorry, Karim. Nobody's gonna do your homework for you. That has been well-illustrated by the barren reply section.

### How could the question have been improved

To be frank, Karim's original post is a mess that looks like it was copy-pasted off of his course's webpage, with no attempt to fix the messed up formatting at all. There was no effort put into readability. Honestly, I had to guess as to what the problem was asking because of how illegible it was. So, that would be thing #1 to improve.

Assuming he has already attempted the homework, Karim should have mentioned what specific problem he is having with his code. He should include the relevant problem code (not his whole program) and explained the specific issues he was having with it so that other Stack Overflow users can more easily diagnose his problem. Additionally, he should have clearly stated what he has already searched online/tried. This is the bare minimum to establish that he's not one of the "lazy sponges" mentioned in Eric Raymond's [_How to ask questions the smart way_](http://www.catb.org/esr/faqs/smart-questions.html). 

It might also help to clarify _why_ Karim included all of the tags that he did, since it seems to me that the program could be accomplished with only arrays---we could iterate through the initial array, run some sort of comparison that keeps track of matching numbers, and then return a counter which kept track of the amount of pairs that were created. It makes tags like "hashmaps" and "turing-machine" seem like they're supposed to be used in the answer, but we can't know for sure, because Karim copy-pasted his question without any further instructions or attempts at the question for people to _try_ to correct.

Unfortunately, this question has pretty much no redeeming qualities, and it'll be unlikely that Karim will get whatever answer he needed.

## Upvote, upvote, upvote!

On a post from 4 years ago, [Mernt presented with an object with five key-value pairs, in which the values were integers of varying value.](https://stackoverflow.com/questions/55332453/get-key-with-minimum-value) He wanted to be able to return the key-value pair with the smallest numerical value. He included code for his personal attempt 
```javascript
alert(Math.min.apply(Math, arr));
```
which returned ```Infinity```, and a Googled solution,
```javascript
var keys = Object.keys(arr).map(Number).filter(function(a){
    return arr[a];
}); alert(Math.min.apply(Math, keys));
```
which also returned ```Infinity```. The goal was to print to the console something along the lines of, "The lowest value is _x value_ from _y key_." **What can be done to fix the "Infinity" issue?**

It's no surpise that this post recieved 10 answers with a variety of potential solutions.

### What made this question successful



## Success begins with asking smart questions

For Software Engineers, asking smart questions is extremely critical to having the code actually work. It may prove to be the difference between actually diagnosing your problem or being stuck with buggy code that you don't have solutions for. It's impossible to solve a problem without a good understanding of context surrounding it, and difficult/tedious without knowing the previous attempts at solving it (including previous web searches). For the sake of both yourself and those who are trying to help you, it is in your best to include as much _relevant_ detail as possible.

Although, questions don't just require a large amount of details to be considered "smart." In fact, including excess information (e.g. including your whole program when there's a bug in one method) may be detrimental because not all kind Internet strangers want to read _all that_. Precision matters, not only to attract helpful answers, but so that you yourself has an understanding of what the problem is in the first place.

### My outlook

Personally, I have always tried to write "smart" questions, especially on the Internet in order to avoid the downvotes, though I'd mostly be asking questions on Reddit's r/calculus. Luckily, asking smart questions about math translates pretty well to code. This experience has exposed me to smart questions for programming which allowed me to reflect on my old questions on r/javahelp and determine what areas I need to work on. Since I am a lot less "literate" in code, I think my biggest struggle is cutting down my code to the most relevant portions since I have trouble deciding which code is pertinent to my issue. Another area I think I could work on is describing the symptoms of the issue rather than proposing the "educated guesses" I came up with and cluttering the post with solutions I've tried (not steps to diagnose---_full solutions that did not work_). 

In the future, I will definitely be asking myself if that extra detail is important to finding a solution or just clutter. I hope to continue improving my questions to make them smarter, but I hope that I will be met with mercy on the inevitable, odd stupid ones, too.
