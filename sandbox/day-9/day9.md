# Day 9 — Dark Mode Basics

### Goal for Day 9

By the end of Day 9, you should:

* Understand how Tailwind handles dark mode
* Know how to use dark: variants
* Practice toggling styles mentally (not building a full toggle)

### Day 9 — Core Concepts (Notes)
1️⃣ How dark mode works in Tailwind

Two strategies:

1. media → follows system preference
2. class → you control it with a .dark class

For learning, we’ll assume class-based dark mode.

2️⃣ The dark: prefix

Example:

        bg-white dark:bg-slate-900
        text-slate-900 dark:text-slate-100


When .dark is present on <html> or <body>, the dark:* styles activate.

3️⃣ What should change in dark mode

Usually:

* Background colors
* Text colors
* Borders
* Shadows (subtle)

Spacing and layout usually stay the same.