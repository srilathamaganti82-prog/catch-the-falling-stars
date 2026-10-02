# Game Design Document — Catch the Falling Stars

## 1. Game Overview
**Game Name:** Catch the Falling Stars  
**Genre:** Casual arcade  
**Target Audience:** Students and casual players  
**Core Mechanic:** Move the player left and right to catch falling stars.

## 2. Goal
Catch as many falling stars as possible. Each caught star increases the score by 1.

## 3. Rules
- The player can move left and right.
- Stars fall from the top of the screen.
- Catching a star gives 1 point.
- Missing a star increases the miss count.
- The game ends after 3 missed stars.
- Press Enter to restart after game over.

## 4. Controls
- Left Arrow: move left
- Right Arrow: move right
- Enter: restart after game over

## 5. Win / Lose Conditions
There is no fixed winning score. The player tries to achieve the highest possible score.
The game ends when 3 stars are missed.

## 6. Main Screen
The screen contains:
- Game title
- Score counter
- Miss counter
- Falling star
- Player platform
- Game-over message and restart instruction

## 7. Playable Prototype
The prototype is implemented as a single HTML file using HTML5 Canvas and JavaScript. It includes player movement, falling stars, collision detection, scoring, miss tracking, game-over logic, and restart functionality.

## 8. Testable Game Loop
Move → wait for falling star → catch or miss → update score/misses → spawn next star → continue until 3 misses.
