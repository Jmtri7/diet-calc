# Diet Calculator

A single-file, mobile-friendly calculator for body measurements and nutrition needs. Open `index.html` in any browser. There is no build step or dependency.

Results update as you type. The page is split into five tabs, and the active tab is highlighted at the top. On a phone, swipe right for the next page and swipe left for the previous one. Each page shows only the inputs it needs.

| Page | What it calculates |
|---|---|
| Body | lb/kg and in/cm conversion, BMI against a chosen optimal range, ideal body weight (Devine or Hamwi) with ±10% range and target, actual vs ideal ratio, adjusted body weight with ±10% range |
| Energy | Mifflin-St Jeor BMR and daily needs by activity level, plus a weight-based estimate with a choice of 19–24, 25–30 or 30–35 kcal/kg |
| Protein | g/day range from a chosen need level (0.8–2.0 g/kg) |
| Fluid | a choice of 25–30 or 30–35 mL/kg, plus the Holliday-Segar estimate |
| Tube | Formula presets (Jevity 1.5 Cal, Glucerna 1.5 Cal, Nepro with Carb Steady) or custom, bolus or continuous feeding (continuous requires hours per day and gives an mL/hr rate), a final-regimen step where you pick a rate and fluid total and see what it provides against each range (with warnings), a collapsible step-by-step breakdown of the math, formula per feeding from kcal needs and energy density (1.0–2.0 kcal/mL), free water flush before and after each feeding, and the energy, protein and fluid provided each day, as a low–high range |

Energy, protein, fluid and tube feeding can use actual, ideal or adjusted body weight.

Your entries are saved in your browser (localStorage) and restored on your next visit. The Reset all inputs button at the bottom clears them.

Estimates for education only. Not medical advice.
