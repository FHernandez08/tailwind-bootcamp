Day 4 Topic: Responsive breakpoints (sm:, md:, lg:)

Goal for Day 4

Understand how Tailwind’s responsive prefixes work: sm:, md:, lg:.

Learn how to change font sizes, layout direction, and spacing at different screen sizes.

Prepare to build a responsive hero by practicing:

* flex-col md:flex-row
* responsive text (text-2xl md:text-4xl)
* responsive padding (p-4 md:p-10)

Key Tailwind Concepts (Day 4)

Mobile-first design

* Base class (no prefix) = applies to all screen sizes.
* Prefixed class (e.g., md:text-4xl) = overrides base at that breakpoint and larger.

Common breakpoints

* sm: → small screens and up (e.g., ≥ 640px)
* md: → medium screens and up (e.g., ≥ 768px)
* lg: → large screens and up (e.g., ≥ 1024px)


Responsive text
Example pattern:

text-2xl | sm:text-3xl | md:text-4xl | lg:text-5xl


* On very small screens: text-2xl
* At sm: and up: text-3xl
* At md: and up: text-4xl
* At lg: and up: text-5xl

Responsive layout

flex flex-col md:flex-row
* Default: vertical stack
* At md: and up: horizontal row

Responsive spacing & width

* p-4 md:p-10
* w-full md:w-1/2
* gap-4 md:gap-8