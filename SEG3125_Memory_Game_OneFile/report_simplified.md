# SEG3125 Assignment 3 Report: Memory Match

## 1. Designer

**Name:** Arjun Hande  
**Student Number:** [add student number]

## 2. Game

The game I made is called **Memory Match**. It is a matching-card memory game. The user flips two cards at a time and tries to remember where each symbol is placed. If the two cards match, they stay open. If not, they turn back over.

I chose this type of game because it is simple to understand, but still tests short-term memory. The user has to remember the position of hidden cards after seeing them once.

The game has three levels:

- Easy: 4 pairs
- Normal: 6 pairs
- Hard: 8 pairs

It also has three card themes:

- Animals
- Nature
- Food

### Inspiration sites

**Helpful Games memory game**  
https://www.helpfulgames.com/subjects/brain-training/memory.html

I used this for the basic idea of matching hidden cards. My version has a simpler setup area, clearer feedback, and a score.

**Math Is Fun Simon Says**  
https://www.mathsisfun.com/games/simon-says.html

This helped me think about fast feedback. In my game, the message area changes after each move so the user knows what happened.

**Memory Health Check**  
https://www.memorylosstest.com/free-short-term-memory-tests-online/

This reminded me that a memory game should not be too complicated. I tried to keep the task clear and easy to start.

## 3. Personas and Storyboards

### Persona 1: Maya Chen

**Intrinsic characteristics:** patient, organized, easily distracted by clutter.

**Relation to technology:** Maya uses websites and apps often, but she prefers simple interfaces where the next step is obvious.

**Relation to the domain:** Maya likes short focus games during study breaks. She understands matching games already.

**Goal:** Maya wants a calm memory game she can play quickly without needing a lot of instructions.

### Storyboard 1: Maya

1. Maya opens the game and sees a simple setup area on the left. She selects Easy and Animals.
2. She starts the game and flips two cards. A message tells her if she found a match or not.
3. At the end, she sees her score, time, and number of moves. She can replay if she wants.

This storyboard uses a calm blue and white style. The setup controls are separated from the game area so the screen does not feel crowded.

### Persona 2: Leo Martin

**Intrinsic characteristics:** competitive, curious, likes quick feedback.

**Relation to technology:** Leo plays browser games and is comfortable trying different settings.

**Relation to the domain:** Leo enjoys quick games where he can improve his score.

**Goal:** Leo wants a memory game that gives him a score and lets him replay on a harder level.

### Storyboard 2: Leo

1. Leo opens the game and chooses Hard with a different card theme.
2. He watches the stats at the top while playing, especially time and moves.
3. When he finishes, he checks his score and tries again to beat it.

This storyboard focuses more on challenge and replay. The score and stats are always visible.

## 4. High-Fidelity Prototype

The final prototype combines both storyboard ideas. I kept Maya's simple layout, but also added Leo's score, timer, moves, and best score.

The prototype is built as one `index.html` file using React from a CDN. This makes it easier to host on GitHub Pages because there is no build step.

### Visual design choices

**Colour theme:** I used blue, white, and light grey. Blue is used for buttons and hidden cards because those are the main interactive parts. White panels make the game easier to read.

**Typography:** I used a basic Arial font to keep the design simple. The title is bigger than the rest of the text so the user can quickly understand the page.

**Layout:** The setup section is on the left and the game is on the right. This separates choosing options from playing the game.

**Negative space:** I left space around the panels and the board so the game does not feel too crowded.

**Contrast:** Hidden cards are blue, while open cards are white. This makes the card state easy to notice.

**Visual hierarchy:** The title, controls, stats, and board are arranged so the user sees the most important information first.

### Gestalt principles

**Similarity:** All cards have the same size, shape, and colour when hidden, so they look like part of one group.

**Proximity:** The level and theme controls are grouped together. The stats are also grouped together at the top of the game panel.

**Figure-ground:** The blue cards stand out from the white game area. This helps the user focus on the main activity.

**Continuity:** The card grid is organized in rows and columns, which helps the user remember card positions.

### Organization, input, and navigation patterns

The interface uses a simple dashboard layout. The user chooses settings, starts the game, plays, and then can replay. The inputs are dropdown menus and card buttons.

### Accessibility choices

The cards are real buttons, so they can be focused with the keyboard. The game also uses labels for the setup controls and aria-labels for the cards.

### Prototype link

**Portfolio link:** [add portfolio link]

## 5. Code

**GitHub repository:** [add GitHub repository link]

The website is mainly one file:

- `index.html`

The file contains the HTML, CSS, and React/JavaScript code in one place.

## 6. Generative AI Acknowledgement

I used generative AI to help organize the assignment and create a first version of the code and report. I then simplified the design and changed the structure so it was easier for me to understand and explain.

For the mockups/storyboards, AI helped me think of two different user flows, but I adjusted the final design to match a simpler layout.

For the prototype, AI helped with the React card matching logic, but I reviewed the code and changed it into a one-file GitHub Pages version.

For the report, AI helped with wording and organization. I edited the wording so it better matched how I would explain the project.
