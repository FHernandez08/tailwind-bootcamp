# Day 8 — Layout Containers & Section Spacing
### Goal for Day 8
By the end of Day 8, you should:

* Understand how to contain content properly
* Stop guessing margins and padding
* Have a repeatable section layout pattern you can reuse everywhere

This day makes your site feel clean and professional instead of cramped or chaotic.

### Day 8 — Core Concepts (Notes)
1️⃣ Why layout containers matter

Without containers:

* Content stretches too wide
* Spacing feels inconsistent
* Layout looks amateur

With containers:

* Everything lines up
* Spacing feels intentional
* Sections feel breathable

2️⃣ The standard Tailwind container pattern

You’ll use this everywhere:

max-w-5xl mx-auto px-4 sm:px-6 lg:px-8


What each part does:

* max-w-* → limits content width
* mx-auto → centers content
* px-* → horizontal padding for mobile → desktop

3️⃣ Vertical spacing between sections

Instead of random margins:

* Use section padding consistently

Common patterns:

* py-16
* py-20
* space-y-12 (inside a section)

4️⃣ Section anatomy (mental model)

Every section should look like:

1. Container
2. Section header
3. Content (grid, text, cards)

Same structure → less thinking → better consistency