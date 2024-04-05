[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [your name]
### Student number: [your student number] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?
The levels are split into 3 each section having a split path to a key, each section teaches a set amount of game components and also rewards exploration such as the hidden healthpack. The game is designed to be in a mountain to disrupt the mindset of a horizontal progression in favor of a mix of both horizontal and linear. This is done when the player is encouraged to discover and play with the newly presented mechanics by giving unclear directions and splitting the path to allow the player to either directly approach the key or if it proves too difficult returning later after climbing the mountain and gaining more skill.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
The higher the player goes, there is a chance that the player may encounter a danger such as game over, however there is the addition of falling back to lower floors as you scale the mountain. It creates two senses of danger of both dying and losing temporary progress, encouraging the player to keep going. By having different ways of causing drama, it keeps the player active and more attentive as they learn from these mistakes.

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?
The first two sections display both the enemies and platforms, each being reasonably challenging teaching about combat as well as jumping traversal. The final level combines both of these designs, creating a chaotic scene. The player must plan and have a quick reaction as they ride the moving platforms. The players can also try multiple different routes each having their own challenge such as taking the left rising platform or the right rising platform with an enemy guarding but is much easier and more viable to access.

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?
The first two keys are hidden, requiring the player to search and explore for them. However the level is designed so you can move forward even without the keys. If the keys are missed it encourages the player to go back and look for said keys. There are also health packs hidden in the same manner in rooms filled with enemies or obstacle courses. Some of the hidden rooms introduce preestablished obstacles which challenge the player’s learnt skills throughout the game.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid
The Acid is introduce as the first obstacle it is used to encourage players to use the jump feature, however I decided to only use the acid on the lower floors. 

### 2.2. Checkpoints
Checkpoints are also used throughout the level, there is a new checkpoint at each new section. I purposely put the checkpoints at the start of each checkpoint in order to allow the players to learn from obstacles they may encounter.


### 2.3. Chompers
Chomper are introduce on the lower mountain as to show one of the easier types of enemies.

### 2.4. Health Pickups
Health pickups start to appear midway of the game as low damage obstacles start to appear. They can be found both before and after obstacles sometimes even hidden.

### 2.5. Keys 
Keys are the main focus of the game as they are scattered around the mountain. Some of the keys are hidden down a split path. This is done to allow the player to explore and practise either opting to go for it straight away or returning after they have practise.

### 2.6. Moving Platforms
Moving platforms are introduced right before the final level, they act as an advance obstacle of pakouring and reaction timing. They are also introduced with enemies riding them.

### 2.7. Passthrough Platforms
Passing platforms acts as a way to hide hidden items such as one of the keys, They encourage exploration and testing of the player.

### 2.8. Spikes
Spikes act very similar to acid but less dangerous as they are smaller and are not instant kill obstacles. They also encourage the use of health packs.

### 2.9. Spitters
Spitters is the ranged enemy type which is used in a variety of ways. They can be placed down normally as enemies or as obstacles on top of high platforms that snipe the player.

### 2.10. Weapon Pickup (Gun)
The gun is introduced after the staff as it has the advantage of being a ranged weapon. 

### 2.11. Weapon Pickup (Staff)
The staff is the first weapon introduced

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


