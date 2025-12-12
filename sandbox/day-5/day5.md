Day 5 Topic: Grids & Cards + Project Setup (Conceptual)

🎯 Goal for Day 5

Understand how Tailwind’s grid system works.

Learn how to build card-style UI blocks (used for Projects, Skills, Experience).

Be able to explain when to use grid vs flex.

Light practice with grids + cards.

Conceptually prepare for React + Tailwind project setup (actual setup happens outside this file).

## Key Tailwind Concepts (Day 5)
### Grid basics

* grid → enables grid layout
* grid-cols-1, grid-cols-2, grid-cols-3

### Responsive grids:

* grid-cols-1 md:grid-cols-2

* grid-cols-1 sm:grid-cols-2 lg:grid-cols-3

### Spacing:

gap-4, gap-6, gap-8

### Mental model:

* Flex → one-dimensional (row or column)
* Grid → two-dimensional (rows and columns)

## Card fundamentals

A “card” usually includes:

* Background: bg-slate-800
* Padding: p-4, p-6
* Shape: rounded-xl
* Depth: shadow, shadow-lg
* Border (optional): border border-slate-700

Cards are reusable:

* Project cards
* Skill cards
* Feature cards

Experience entries

3️⃣ Hover & interaction (light touch)

This will be more expanded when I reach day 7 of this bootcamp!

* transition
* hover:-translate-y-1
* hover:shadow-lg

Just enough to understand the pattern.

### Where this applies in your portfolio

* Projects section → grid of cards
* Skills section → grid of tags or mini-cards
* Experience section → stacked cards or grid
