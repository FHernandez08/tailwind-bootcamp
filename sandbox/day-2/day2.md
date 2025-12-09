# Day 2 Notes - Flexbox

### Make sure that for this to work, at the start of every Tailwind CSS code, it will start with flex
EX: div class="flex ..."

- Making a Flex Container: flex
- Direction: 
    - flex-row = horizontal
    - flex-col = vertical

- Main Axis Alignment (justify-):
    - justify-start
    - justify-center
    - justify-end
    - justify-between
    - justify-around
    - justify-evenly

- Cross Axis Alignment (items-)
    - items-start
    - items-center
    - items-end
    - items-baseline

- Gap Between Items
    - gap-2
    - gap-4
    - gap-6
    - gap-8

- Responsive Flex
(Will need "md:" to make it responsive to the website)
    - flex-col <b>md</b>:flex-row
    - flex-row-reverse

- Flex Growth & Equal Columns
    - flex-1 = grow to fill space
    - flex-none = fixed width
    - flex-auto = auto width