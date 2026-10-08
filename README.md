# T04-1: Draw SVGs – House & Garden

COS30045 Data Visualisation – Swinburne University of Technology

Author: Sakib Ahmed

Live site: https://ahmedsakib1113.github.io/T04-1/

This exercise draws a house and garden scene with inline SVG, using every basic SVG shape plus text. The page shows four versions of the same scene.

## Scenes

1. **Original scene** (`#scene-original`): the base picture, built from `<rect>`, `<circle>`, `<ellipse>`, `<line>`, `<polyline>`, `<polygon>`, `<path>` and `<text>`.
2. **Annotated scene** (`#scene-annotated`): the same picture with a `<g id="annotations">` that labels one example of each shape with its coordinate attributes (`cx`, `cy`, `r`, `x`, `y`, `points`, `d` and so on).
3. **Adjusted scene** (`#scene-adjusted`): a customised copy. The house and tree are repositioned with `transform="translate(...)"`, colours and stroke widths are refined, the fence uses `stroke-dasharray`, and a stone path, mailbox and chimney smoke are added.
4. **Grouped windows scene** (`#scene-grouped`): the two windows are defined once as `<g id="window">` and reused twice with `<use>`, each positioned with `transform="translate(x,y)"`.

## AI use

This work was completed with AI assistance. Commits that include AI-generated content are tagged `[AI-assisted]`.
