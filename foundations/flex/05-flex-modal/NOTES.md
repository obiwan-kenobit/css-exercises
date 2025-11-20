What I built

I completed the modal layout using Flexbox. My version is visually very close to the reference image, but after comparing it with the official solution I noticed several structural differences that are worth documenting.

What I did differently

I added two wrapper divs (1 and 2) mostly out of convenience. They weren’t meaningful or necessary, and in a real project I wouldn’t name classes like that.

I kept the header text and the close button in separate elements. At the time I didn’t think about grouping them in a single flex container.

I used padding to create spacing between elements instead of using margins.

I didn’t create one unified container for the whole “right section” of the modal (header, text, buttons), so my structure was more fragmented than it needed to be.

What I learned

The icon doesn’t need to be wrapped in its own container; Flexbox can handle it directly.

The header and close button should be inside the same container because they’re two parts of the same visual block. Putting them in one flex container makes layout much simpler and cleaner.

Padding is for internal spacing, margin is for space between siblings. In this kind of component, margins create a more predictable vertical rhythm.

A single container for the whole right-hand content makes the structure easier to control. It isolates the responsibilities: icon on the left, structured content on the right.

Why this matters

I realized I tend to create more containers than necessary. I still arrive at the correct visual result, but with more complexity. This is part of the learning process: the more I recognize common layout patterns, the more natural it will become to choose simpler structures.