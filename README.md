# Grading Slope Solver

Free, browser-only calculator for site grading, by Gouse Shaik (BIM Manager, MSCEB).
Lock the values you know, read off the rest, check them against a standard, and get exactly what to type into Revit.

**Live app:** https://gs-786.github.io/Grading-Slope-Solver/
**Sister app:** [Revit Formula Solver](https://gs-786.github.io/Revit-Formula-Solver/)

## Solvers

| Code | Solver | What it works out |
|---|---|---|
| G-01 | Slope | Rise & run, grade %, angle, H:V ratio, slope length |
| G-02 | Spot Levels | Start level, end level, distance and grade between them |
| G-03 | Contours | Which contours cross between two spots, and where |
| G-04 | Cut & Fill Batter | Daylight offset, batter height and length, cut or fill |
| G-05 | Cross Fall | Width, cross fall and fall for crowned or one-way surfaces |
| G-06 | Site Ramp | Runs, landings and total length from a total rise |

## Features

- **Standards check** against Good practice (typical), US ADA 2010 + IBC 2021, UK Approved Document M + BS 8300, or your own custom standard (export/import as JSON).
- **Use it in Revit**: the exact tool, field and value to type (slope arrows, Modify Sub Elements, Site Settings, ramp type properties).
- **Family formulas** (optional switch) for parametric Revit families.
- Units: m, mm, ft, ft-in, in. Ten colour themes. Print / Save as PDF from Chrome or Edge.
- Runs entirely in the browser. Nothing is uploaded; settings are saved only in your browser.

## Edit your details

Open `index.html`, find `const PROFILE = {` near the top of the script, and change the name, title, photo, links and bio.

## Publish on GitHub Pages

The app is a single file (`index.html`), so no build step is needed.

1. Create a new **public** repository on GitHub named `Grading-Slope-Solver`.
2. Upload `index.html`, `README.md` and `.nojekyll` (or push this folder with git).
3. In the repository: **Settings › Pages › Build and deployment › Source: Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. After a minute the app is live at `https://gs-786.github.io/Grading-Slope-Solver/`.

To update the live app later, replace `index.html` in the repository (upload again or push a new commit).

## Disclaimer

Standards limits are summarised from the published documents for quick checking. Always confirm against the current edition and your authority's requirements. Revit is a trademark of Autodesk, Inc.; this tool is independent and not affiliated with Autodesk.
