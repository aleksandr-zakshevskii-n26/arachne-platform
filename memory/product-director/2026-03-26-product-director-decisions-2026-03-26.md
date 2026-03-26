<!-- arachne:memory -->
**Recorded:** 2026-03-26
**Role:** product-director
**Instruction:** Record all decisions made today: what was approved, what was rejected, and the reasoning for each. This builds your decision history so future sessions remain consistent and you don't re-evaluate the same ideas.


---

[
  {
    "title": "Fraction Visualizer — Core Implementation",
    "body": "Build a single HTML page with two number inputs labelled 'Top number' (numerator) and 'Bottom number' (denominator), both constrained to 1–12, where numerator ≤ denominator. On input, draw an SVG or canvas circle divided into N equal slices (where N = denominator) with M slices filled in a bright color (where M = numerator). Label the fraction as 'M out of N' below the visual. The entire logic is: divide 360° by denominator to get slice angles, fill numerator slices, done."
  },
  {
    "title": "Fraction Visualizer — Polish and Edge Cases",
    "body": "Add input validation: reject numerator > denominator with a friendly message ('The top number can't be bigger than the bottom number — that would be more than a whole!'), reject 0 and non-integers, and clamp values to the 1–12 range. Make the layout responsive so it looks clean on mobile (inputs stacked above the circle, circle centered). Add a subtle animation when slices fill in so the visual feels alive."
  },
  {
    "title": "Times Table Grid Highlighter — Core Implementation",
    "body": "Build a single HTML page displaying a 10×10 multiplication grid as an HTML table. Row and column headers show numbers 1–10. Each cell contains the product (e.g., cell at row 3, col 7 shows '21'). When a user taps/clicks any row or column header, highlight that entire row or column with a distinct background color and update each highlighted cell to also show the equation (e.g., '7 × 3 = 21'). Perfect squares along the diagonal get a subtle default highlight on page load. Implementation is a table with a click handler that toggles a CSS class on the relevant row/column cells."
  },
  {
    "title": "Times Table Grid Highlighter — Polish and Edge Cases",
    "body": "Add tap-to-toggle behavior so tapping a highlighted header removes the highlight, and tapping a different header replaces it (or optionally allows multi-select with distinct colors for up to 2–3 simultaneous tables). Ensure the grid is responsive on mobile — cells should remain legible on small screens, potentially using a smaller font and compact padding. Add a 'Clear all' button to reset highlights."
  },
  {
    "title": "Coin Flip Probability Simulator — Core Implementation",
    "body": "Build a single HTML page with three large buttons: 'Flip 10 times,' 'Flip 100 times,' and 'Flip 1000 times.' When pressed, run a loop of Math.random() calls, count heads vs tails, and display results as two horizontal bars (green for heads, blue for tails) whose widths represent percentages. Show running totals as text: 'Heads: 487 / Tails: 513 (48.7% / 51.3%).' Results accumulate across presses (a 'Reset' button clears). The bars animate their width transitions with CSS. Color the percentage text green when within 2% of 50/50, orange otherwise."
  },
  {
    "title": "Coin Flip Probability Simulator — Polish and Edge Cases",
    "body": "Add a brief coin-flipping animation (a simple H/T text that rapidly toggles for ~0.5 seconds before showing final results) so the flip feels physical. Disable buttons during the animation to prevent spam. Make the layout mobile-friendly with stacked buttons above the bar chart. Add a small note below results that says 'Try flipping more — what happens to the percentages?' to nudge discovery of convergence."
  }
]
