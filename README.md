# Triangle Construction Tool

Self-contained single-file web app for drawing and measuring triangles with real centimeter-scale lengths.

## Features

- **Right triangle constructor** – enter two legs in cm, optional custom labels (numbers or unknowns like `x`)
- **SSS triangle constructor** – any three sides (checks triangle inequality)
- **Auto-calculated angles** and hypotenuse
- **True-to-scale canvas** with adjustable px/cm scale so drawings match a physical ruler
- **Aligned cm rulers** (horizontal + vertical) that auto-size to the triangle extents
- **Measure mode** – click three points to measure any angle
- **Export PNG** of the diagram
- Toggle grid, labels, angles, and rulers

## Usage

Open `triangle-drawer.html` in any modern browser (no build step, no dependencies).

Or use the live version if GitHub Pages is enabled.

## Example

Draw a right triangle with legs 8 cm and 15 cm, then read the angle adjacent to the 8 cm side (≈ 61.93°).
