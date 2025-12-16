# 🧠 Day 6 — Reusable UI Patterns
## 🎯 Goal for Day 6

By the end of Day 6, you should be able to:

* Recognize repeatable UI patterns
* Build them once and reuse them mentally everywhere
* Stop “winging it” on buttons, section headers, and tags

This is about consistency, not creativity.

### Day 6 — Core Concepts (Notes)
1. What “Reusable UI Patterns” really means

    * Instead of styling things randomly every time, you define:

        * One primary button style
        * One secondary button style
        * One section header style
        * One tag/pill style

    Then you reuse those everywhere.

    This:
    * Speeds you up
    * Makes your site feel professional
    * Makes Tailwind easier to reason about

2. Common reusable patterns you’ll use in your portfolio
Buttons

    * You almost always need:

        * Primary button → main CTA
        * Secondary button → alternative action

    * Typical traits:

        * Padding: px-6 py-3
        * Shape: rounded-lg
        * Font: font-semibold
        * Clear color difference between primary & secondary

3. Section Headers

    * Used for:

        * About
        * Projects
        * Skills
        * Experience

    * Usually include:

        * Small label (optional)
        * Section title
        * Short description

    Traits:

        Clear hierarchy

        Consistent spacing

        Same look across all sections

    Tags / Pills

    Used for:

        Skills

        Tech stack

        Categories

    Traits:

        Small text

        Rounded shape

        Subtle background

        Not visually dominant