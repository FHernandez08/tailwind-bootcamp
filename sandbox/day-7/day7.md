# Day 7 — Transitions & Hover States
### Goal for Day 7

By the end of Day 7, you should be able to:

* Add subtle, intentional motion to UI elements
* Understand how transition, duration-*, and hover:* work together
* Make buttons, cards, and links feel interactive, not static
* Avoid over-animation (very important)

This is about polish, not flash.

### Day 7 — Core Concepts (Notes)
1. Why transitions matter

    * Without transitions:

            UI feels stiff
            Interactions feel abrupt
            With subtle transitions:
            UI feels modern
            Feedback feels natural
            Quality goes up instantly

2. Core transition utilities (the foundation)

    * You’ll use these constantly:

            transition → enables transitions
            transition-all → transitions most properties
            duration-150, duration-200, duration-300
            ease-in-out (optional)
            Rule of thumb
            Buttons: duration-200
            Cards: duration-200 or duration-300
            If you notice the animation → it’s probably too slow

3. Common hover patterns (use these everywhere)
    * Buttons

            hover:bg-*
            hover:text-*
            Optional: hover:opacity-90

    * Cards

            hover:-translate-y-1
            hover:shadow-lg

    * Links

            hover:text-sky-400
            Optional underline or subtle color shift

4. What NOT to do

    * Avoid:

            Big translations (-translate-y-4)
            Long durations (duration-700)
            Multiple animations on one element
            Day 7 polish should be felt, not noticed.