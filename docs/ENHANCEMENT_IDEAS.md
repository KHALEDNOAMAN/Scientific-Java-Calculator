# Scientific Calculator - Enhancement Ideas

## UI Improvements
- [ ] Dark mode / light mode toggle
- [ ] Keyboard shortcut support
- [ ] History panel (last 20 calculations)
- [ ] Copy result to clipboard button
- [ ] Responsive layout for different screen sizes

## New Math Functions
| Function | Description | Formula |
|----------|-------------|---------|
| nPr | Permutation | n! / (n-r)! |
| nCr | Combination | n! / (r!(n-r)!) |
| log_b | Log base b | log(x) / log(b) |
| sinh | Hyperbolic sine | (e^x - e^-x) / 2 |
| cosh | Hyperbolic cosine | (e^x + e^-x) / 2 |
| mod | Modulo | a % b |
| gcd | Greatest common divisor | Euclidean algorithm |
| lcm | Least common multiple | (a*b) / gcd(a,b) |

## Unit Converter
Add built-in conversions:
- Length (m, cm, mm, inch, ft)
- Weight (kg, g, lb, oz)
- Temperature (C, F, K)
- Area (m², ft², acre)

## Architecture Tips (Java Swing)
```java
// Use MVC pattern
// Model: CalcEngine (handles math)
// View: CalcUI (Swing components)
// Controller: CalcController (connects them)
```
