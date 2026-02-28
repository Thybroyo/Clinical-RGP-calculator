# Clinical-RGP-calculator
Clinical RGP calculator is a unified, clinical-grade web tool for rigid gas permeable lens calculations. It combines General RGP Modification, Low Toric Stimulation bitoric RGP, Mandell-Moore Bitoric RGP, and BVD Conversion into a single, beautiful interface with 4-significant-figure output precision, validated input ranges. 
- Overview

- Single-page web application for clinical RGP lens calculations.
- Produces results in 4 significant figures for consistent clinical precision.
- Includes tabbed calculators with unified styling, validation, and clear output sections.
- Calculators Included

- General RGP Modification
- Low Toric Stimulation bitoric RGP
- Mandell-Moore Bitoric RGP
- BVD Conversion (Spectacle → Corneal plane)
- Input Ranges

- K values: 33–63 D
- Spectacle sphere (D): -25 to +25
- Spectacle cylinder (D): -25 to 0
- Axis (°): 0–180
- Back vertex distance: 5–20 mm
- Flat meridian BC adjustment: -2.00 to +2.00 mm (0.05 mm steps)
- Steep meridian BC adjustment: -2.00 to +2.00 mm (0.05 mm steps)
- Over-refraction sphere (D): -25 to +25 (0.25 D steps)
- Over-refraction cylinder (D): -25 to 0 (0.25 D steps)
- Over-refraction axis (°): 0–180
- Usage

- Open the HTML file directly in any modern browser.
- Choose the calculator tab.
- Enter values within valid ranges; the “Calculate” button enables when inputs are valid.
- Review output cards: conversion summaries, base curve adjustments, tear lens power, and final lens powers.
- Mobile Support

- Optimized for iPhone Safari and Google Chrome.
- Mobile numeric keyboards enabled via inputmode=decimal and pattern.
- Spinner controls removed for cleaner numeric entry.
- Validation runs on both input and change events; tab switching triggers validation so buttons enable correctly.
- Accuracy and Precision

- Outputs presented with 4 significant figures and consistent mm↔D conversions.
- Key formulas: D = 337.5 / mm; Ocular Rx = Spectacle Rx / (1 - d × Rx) with d = BVD in meters; 0.05 mm BC change ≈ 0.25 D tear lens change.
- Tech Stack

- Tailwind CSS via CDN for styling.
- Font Awesome via CDN for icons.
- Pure client-side JavaScript; no server required.

