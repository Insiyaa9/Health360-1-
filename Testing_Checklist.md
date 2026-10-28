# Health360 Website Testing Checklist

## Launch
- [ ] Open `website/index.html` in Chrome or Edge.
- [ ] Confirm charts load (internet connection is required for Chart.js CDN).
- [ ] Confirm the dashboard fits a desktop screen and a mobile screen.

## Filters
- [ ] Change gender and confirm KPIs/charts update.
- [ ] Change minimum and maximum age.
- [ ] Change exercise level.
- [ ] Press Reset filters and confirm all records return.
- [ ] Select a filter combination with no matching records and confirm the empty state appears.

## Data checks
- [ ] Compare the displayed record count with the CSV filter result.
- [ ] Check the average age and average risk score.
- [ ] Verify outcome counts against the corresponding dataset columns.
- [ ] Inspect the first 10 rows in the dataset preview.

## Interpretation
- [ ] Keep descriptions neutral and descriptive.
- [ ] Do not present dataset risk scores as medical diagnoses.
