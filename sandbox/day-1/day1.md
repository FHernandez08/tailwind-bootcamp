# Day 1 Notes - Utility-First Mindset & Core Utilities

This is the link needed to access Tailwind CSS inside HTML as script src tag:
https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4

1. Utility-First Mental Model
    - In Tailwind:
        - DO NOT write custom CSS
        - compose UI by stacking small utility classes inside class=""
        - utilities map directly to CSS properties

2. Background Colors (bg-)
    - Common choices:
        - bg-slate-900
        - bg-slate-800
        - bg-slate-700
        - bg-white
        - bg-black
        - bg-red-500
        - bg-blue-600
        - bg-emerald-500

3. Text Utilities (text-, font-, tracking-)
    - Font sizes (text-*):
        - text-xs
        - text-sm
        - text-base (default)
        - text-lg
        - text-xl
        - text-2xl
        - text-3xl
        - text-4xl

    - Weights (font-*):
        - font-normal
        - font-medium
        - font-semibold
        - font-bold

    - Colors (text-*_):
        - text-slate-300
        - text-white
        - text-black
        - text-sky-400

    - Letter Spacing (tracking-*):
        - tracking-tight
        - tracking-wide
        - tracking-wider

4. Spacing (padding/margin)
    - Padding:
        - p-4 = padding: 1rem
        - px-6 = padding-left/right: 1.5rem
        - py-8 = padding-top/bottom: 2rem

    - Margin:
        - m-4 (overall margin)
        - mt-2 (margin top)
        - mb-6 (margin bottom)
        - mx-auto (horizontal auto margin)

    - Vertical spacing between siblings:
        - space-y-4
        - space-y-8


5. Border Radius
    - rounded
    - rounded-md
    - rounded-lg
    - rounded-xl
    - rounded-2xl
    - rounded-full