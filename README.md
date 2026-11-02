# Conformance Calculator

A lightweight, browser-based calculator for estimating the out-of-conformance time available while meeting a workforce conformance goal.

## Use

Open `index.html` in a modern web browser. No installation, build step, or server is required.

Enter your shift length, conformance goal, and average work days per week and month. You can also choose a schedule preset, then copy the calculated daily, weekly, and monthly allowances.

## Calculation

The calculator uses:

```text
daily allowance = hours per work day × (1 − conformance goal ÷ 100)
weekly allowance = daily allowance × work days per week
monthly allowance = daily allowance × work days per month
```

Allowances are displayed to the nearest minute. Schedule presets are starting values and can be adjusted.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select the branch containing `index.html` and the repository root (`/`), then save.
4. Open the published URL shown in the Pages settings.
