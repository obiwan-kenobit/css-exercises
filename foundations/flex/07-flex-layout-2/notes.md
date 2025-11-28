Holy Grail Layout – Notes

This exercise replicates the “Holy Grail” layout using flexbox. The layout works correctly and visually matches the expected outcome.

Key differences from the official solution:

HTML structure

The main container is called .content instead of .body, and the cards container is .card-container instead of .container.

Functionally identical, just different naming.

Sidebar spacing

Used display: flex; flex-direction: column; gap: 12px on the ul instead of margin-bottom on li. This approach reduces repetition and keeps spacing consistent.

Cards

Cards have max-width: 270px and padding: 20px, while the official solution uses width: 300px and padding: 16px. Visually, the difference is minimal.

Header / Footer

Header has fixed height + padding; the official solution lets content define height.

Footer uses flex to center content both vertically and horizontally, same as the official solution.

Overall, the layout behaves as intended, is responsive, and aligns with the learning objectives of the exercise. The differences are mostly stylistic or structural and do not affect the final result.