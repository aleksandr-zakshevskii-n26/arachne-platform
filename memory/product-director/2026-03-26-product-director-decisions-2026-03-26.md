<!-- arachne:memory -->
**Recorded:** 2026-03-26
**Role:** product-director
**Instruction:** Record all decisions made today: what was approved, what was rejected, and the reasoning for each. This builds your decision history so future sessions remain consistent and you don't re-evaluate the same ideas.


---

[
  {
    "title": "Pythagorean Theorem Visual Calculator — Core Implementation",
    "body": "Build a single HTML page with two number inputs (side A and side B), a 'Calculate' button, and a canvas that draws a right triangle with the right angle at the origin. On click, compute the hypotenuse via Math.sqrt(a*a + b*b), draw a horizontal leg, a vertical leg, and the hypotenuse connecting them, scaled to fit the canvas. Label all three sides with their numeric values directly on the drawing. The triangle should be visually clear with distinct stroke colors and legible font sizes."
  },
  {
    "title": "Pythagorean Theorem Visual Calculator — Polish and Edge Cases",
    "body": "Add input validation: reject non-positive numbers, non-numeric input, and extremely large values that would break the canvas layout. Display friendly inline error messages (e.g. 'Please enter a positive number for both sides'). Ensure the triangle scales proportionally so very lopsided inputs (e.g. 1 and 100) still render legibly. Make the layout responsive so it looks clean on mobile screens with the inputs stacked above the canvas."
  },
  {
    "title": "Fraction Visualizer — Core Implementation",
    "body": "Build a single HTML page with two number inputs (numerator and denominator), a 'Show Fraction' button, and an SVG circle that visualizes the fraction as a pie chart. Draw the denominator as evenly-spaced radial lines dividing the circle into equal slices, and fill the numerator count of slices with a bright color. Display a plain-language label below the circle (e.g. '3 out of 4 pieces'). Scope to proper fractions only: numerator must be less than or equal to denominator."
  },
  {
    "title": "Fraction Visualizer — Polish and Edge Cases",
    "body": "Add input validation: reject non-integer input, zero denominators, negative numbers, and improper fractions (numerator > denominator) with friendly messages like 'The top number can't be bigger than the bottom number.' Handle edge cases like 0/n (empty circle) and n/n (fully filled circle) gracefully. Make the layout responsive for mobile with inputs above the SVG and readable label text at small screen sizes."
  }
]
