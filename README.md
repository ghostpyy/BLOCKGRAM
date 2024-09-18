![logo](https://github.com/qilin2/BLOCKGRAM/blob/main/visuals/Screen%20Shot%202022-10-16%20at%2012.50.09%20PM.png)

## Team
- Brandon Hung [@qilin2](https://www.github.com/qilin2): Team Lead, Team Manager, Frontend, UI/UX Design
- Sunho Kim [@sunho](https://github.com/sunho) : Co-Lead, Frontend, Backend, UI/UX Design, Database
- Wei Quan Lai [@LaiWeiQuan](https://github.com/LaiWeiQuan) & Eren Saglam [@ghostpyy](https://github.com/ghostpyy): CockroachDB Database.
- Merlin Ho [@clairvoyage](https://github.com/clairvoyage) : UI/UX Design

## About
An interactive and dynamic educational programming interface that simplifies complex structures into simple sentences for better interpretability & understanding. This app is entirely built from scratch.

[CalHacks 9.0 Submission]([https://devpost.com/submit-to/16501-cal-hacks-9-0/manage/submissions])

![gif](https://github.com/qilin2/BLOCKGRAM/blob/main/visuals/blockgram.gif)

## Inspiration
Inspired by [Scratch Programming](https://scratch.mit.edu/developers) and tutoring young kids coding, words and letters are too dull and boring for them. Having a tool to let them visualize makes coding interesting and easily understandable.
![ui](https://github.com/qilin2/BLOCKGRAM/blob/main/visuals/interface.png)


## Functionality
C and C++ programming language is especially challenging language to learn as a beginner. Compared to higher languages like python and javascript, they have more tricky concepts such as pointers that makes the language not really approachable. What we built is a real time bi-translator between scratch-like block language and c/c++ which allows students to toy around with text and block code simultaneously. This enables students to learn complicated programming languages like c/c++ more hands-on, intuitive way.

![workspace](https://github.com/qilin2/BLOCKGRAM/blob/main/visuals/workspace.png)


## How It's Built
CParser written in javascript to get C AST and implemented a DFS style conversion from C AST to our own blocking language tree representation. We implemented reverse conversion from blocking language tree to C code so that bi-translation works perfectly. We got a virtual machine for our own block coding language which makes the simulation of variables and expression interpretation more low-level. It allows to implement visualization of control structure and variables changes more easily. We also used cockroachdb to implement code sharing function. CockroachDB fitted into this purpose since it could be used to visualize the traffic of share real time using CockraochLabs.

![compile](https://github.com/qilin2/BLOCKGRAM/blob/main/visuals/compile.png)


## How to Run
1. Download the .zip file or use git clone.
2. run npm install
3. run npm start


## Built with
- ReactJS
- Database

THANK YOU ! :)

