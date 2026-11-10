# GTU Maths 1 arc length calculator (Simpson's rule)

Arc length, surface or volume of revolution came in 8 of 9 official GTU Mathematics-1 (3110014) papers in GTU Hero's count (Summer 2022 to Summer 2026). Same-sum alert: length of the curve y = x³/12 + 1/x from x = 1 to 4 appeared in 3110014 S2022 Q.1(c) and W2025 Q.1(c). Answer is exactly 6. Ye page koi bhi y = f(x) ki arc length numerically nikalta hai so you can check your integral.

Live page: https://princeadvant.github.io/gtu-maths-1-arc-length-calculator/

## Formulas

- L = ∫ from a to b of √(1 + (dy/dx)²) dx
- For y = x³/12 + 1/x: dy/dx = x²/4 − 1/x², so 1 + (dy/dx)² = (x²/4 + 1/x²)²
- L = [x³/12 − 1/x] from 1 to 4 = 6

## Test

`node test.js` checks the formulas against hand-worked values and prints `All checks passed`.

## Tips

- The trick in the x³/12 + 1/x sum: 1 + (dy/dx)² becomes a perfect square. Look for that before integrating.
- Use Math names for functions, for example sin(x), sqrt(x), log(x) (natural log).
- Numerical answer is for checking only. In the exam write the integral steps.

Old papers and repeat counts: [GTU Hero](https://gtuhero.com/) (GTU Hero is my project).
