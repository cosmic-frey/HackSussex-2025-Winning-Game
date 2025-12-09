# I'm A HackSussex Three Category Winner??!!??
Soooo we won three categories?? Mental! This our first in person hackathon, and really we were just aiming to win something (even if it was Hackiest Hack). Over the month of November I began familiarising myself with Javascript, as I felt this familiarity could be helpful in the long run. I did not however, predict that this decision would result in winning my fist Hackathon - especially as a two-person team (we'll get onto that later). 

**As a WARNING: This is a very informal blog-style README. I will be adding a more proffessional one later, but I thought it would be best to document the process of making Password Quest whilst it was still fresh in my mind. I also want this as something to look back on, because I was in shock for two days after winning and the weekend went by in a blur.**   
  
## The Other Entries:
Before I get started, I want to highlight the other amazing entries (as well as the one that got banned as I thought that one was actually one of the best). Check out all the other amazing entries in the Devpost link below:


## The Game:

We created a Multi-level 2D game using Javascript (phaser.js) in vscode, which followed our magical protagonist on a quest to defeat the dragon who stole his personal data. Our end product was a working game we named Password Quest, which included a narrated intro-video and narrated outro-page (we used ElevenLabs for all audio, including narration).
   
Password Quest investigated themes of personal privacy, shadow threats and the importance of altruism in internet safety, winning three prize categories in total from two awarding bodies.   


### Game structure:  
(This is a written breakdown of our game structure however, if you are a more visual learner, there are stills at the end of the README for each section noted in this list.)
**1) Intro-Video:**  
The intro video sets the scene for the plot. To make this we used AI generated art that we pixelised for the opening scene, Canva, Piskel (for the dragon and crying scene) and ElevenLabs for the narration and background music.  
**2) Level 1:**   
Level 1 was set up as a moving platformer, and the aim of this level was to


## The Winning Categories:
These winning categories were:
- The BCS Chartered Institute for IT Prize for best game investigating themes of internet safety
- The Major League Hacking Prize for best use of Auth0
- The Major League Hacking Prize for best use of Vultr

### Judging Criteria for the Categories we won:
- **BCS Chartered Institute for IT:**

- **MLH Best Use of Auth0:**

- **MLH Best Use of Vultr:**

## How Tasks were split-up:
Initially we were supposed to be part of a larger team. However, pessimistically I dreamt that this all went wrong the night before (I hate having prophetic dreams the night before a big deadline), so I readied myself for this eventuality. Our other two teammates had uni deadlines (which is so valid, I feel for anyone who has January exams), and my teammate (Jabez, one of my closest friends from Sixth Form) had committments in the evening which were to watch his flatmate in a performace and sleep 6-9 hours (both valid and I would have done the same in his position, I did regret onl sleeping 4-5 hours the following Monday).   
This did complicate the division of tasks, as many of these timings were unknown, so - we decided to do something **bold** and somewhat rash:
- I (The **Biologist**) would work on the logic
- He (The **Theoretical Physicist**) would work on the graphics and anything else he had time for.
This put both of us majorly out of our comfort zones, and also forced us to engage in "valuable learning opportunities" (helpful as this was one of the judging criteria).

I have a tendency to over-reach in projects and not get them finished (never take me to pottery painting it will be the most stressful experience of your life), so I made sure we entered this competition with a simplicity-focussed mindset (which went out of the window a little bit when things started going a bit too well - I'm too much of an over-achiever). This simplicity was helpful as it focussed the initial stages of work so that we had something playable by the first evening (Level 1).
   

## The Decision-making Process:
So, why Phaser and why Javascript?   
This was actually a whole crisis I had when researching ways to make video games. I knew what scratch was and I know how to make noughts and crosses with C++ (kinda) and... well that was about it to be honest.   

### Why not Python?
Initially I wanted to make a game using Pygame. I downloaded the Al Sweigart book "Making games with Python & Pygame", watched youtube videos, read through demos, worked through mini-projects in codex.io - then I actually looked at previous winning submissions from 2024 and 2023. None of them used Python. This set off some warning bells and I started watching videos of people talking about making winning games for hackathons and why Pygame did not work. Turns out it's slow, prone to crashing, the errors and hard to work through, and there's a limit to the technical effects you can add. Additionally, one of the previous winners for The HackSussex GameJam literally wrote about how bad python had been and how they had to learn to use unity and make a new game in three hours. This did not sound ideal, and I fear I may have cried if that happened to me.  

### Why not Godot?   
This was the crisis I had the evening before the competition. I have some friends who are starting their own video game business- what are they using? Godot. Everyone seems to be using it, so it must be good....right? That's what I presumed initially too. It looked like an amazing way to make a game where you got visual output immediately, PLUS godscript is similar to Python so this seemed like a huge win (maybe my teammate could help with the code afterall!). However, I have trust issues (at a healthy level I promise), so I initiated a deep dive into why Godot may be a bad idea. Initially, I couldnt find anything obvious, so I started watching tutorial videos and worked demos of how a game can be made. Through watching these videos, something stuck out for me immediately - all the processes involved seemed so interconnected and dependent on one another. This scared me a bit as, although obviously I'm awesome at coding, I'm also very new and I knew that I would be making a lot of mistakes throughout this competition - the last thing I wanted was for one little syntax error to ruin everything. 

### Why Phaser:
Whilst using my partner as a rubber duck to talk this through (thanks Steve), I realised that what I really wanted was a language where everything is spaced out seperately in a clear and organised way - just like my Tamaghosty project!. But - Javascript is just visual, you can't make games with it... right???   
Yeah so turns out (through asking GitHub copilot if you can make a game with Javascript) that Phaser very much exists (my newbie-ness shining through, I promise I'm learning).

## Planning process:
After installing all our packages, implementing the basic backbone of our code (with the help of resources supplied by Phaser for windows), and making initial loading screens, we got to work brainstorming on paper. 

## Challenges we ran into:
### We forgot to reload Powershell for two hours, so we thought packages hadn't installed properly:

### I still don't quite understand why I kept getting a node.js audit error, but ignoring it worked fine:

### I kept breaking the intro-video:

### The physics kept going wrong in Level 1:  


### Coin-counting kept multiplying instead of adding and it made me cry:

### I kept breaking level 2:

### I managed to fix the flames in Level 3 by accident?

### Jumping mechanics are actually a nightmare that I still need to fix:

### Backend is actually really hard:



## Why Phaser Worked:
Obviously I used a lot of resources, and could not have completed this project without access to the internet and GitHub copilot (AI) to streamline our process. Phaser (as I already may have mentioned) has so many open-source resources, and so many examples of how to implement code for different features. For someone who needs to work visually and see how code is implemented, these examples were a godsend. I have linked below every webpage I used to find resources and worked examples of code, however I also used the examples within the windows launcher for Phaser (files for these examples and labelled trial in my repo).
  

## Use of AI:   
AI is a great tool for learning, and helps to streamline a project under time pressure. I am very open about my use of AI as a learning tool, and AI helped me a lot over the past month in familiarising myself with Javascript.   
### What AI was helpful for:
- Adding comments (as my team-mate does not know javascript and there would not have been enough time for me to add comments for every block of code I wrote)
- Summarising the work I had done so far in an .md for me to refer back to after taking breaks (toilet break, lunch break, chat break, walk break, sleep, etc)
- Writing up instructions of ways I could implement changes in .md files
- Explaining why my code was not running (it's hard to get into the flow of Javascript syntax, and as I'm new to it I still regularly make mistakes - which is how you learn!)
- Explaining code errors (what they mean and how they could be fixed)
- Suggesting fixes/ debugging ideas (I'm very new to debugging and this was the first time I learnt to debug in console, which was very exciting!)
- Rearranging my code blocks if I had put them in the wrong sequence (turns out AI can often be just as bad as me at this, but it can be helpful sometimes)
- Writing up instructions of how to use Auth0, Cloudflare, Vultr and ElevenLabs (so I didn't have to waste time googling in the last 30 mins)



