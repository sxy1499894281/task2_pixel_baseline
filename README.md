# Task2 Pixel Editing Baseline (Anonymous Release) - How to View

This directory is meant for quickly checking the differences between the "pixel editing baseline" and the "symbolic editing route" on Task 2. Each case is stored under `case_xxx/`.

## What each file in `case_xxx/` means
- `rendered_input.png`: rendered diagram before editing;
- `instruction.txt`: the English editing instruction for this sample;
- `pixel_edited.png`: output of the pixel-editing baseline;
- `diagram_gemini_edited.xml`: the full mxGraph XML produced by the symbolic editing route after applying the patch;
- `gemini_edited_render.png`: the PNG obtained by rendering the above XML with the Draw.io pipeline consistent with the paper.

## Recommended viewing order
First, look at `rendered_input.png` and `instruction.txt`. Then compare `pixel_edited.png` with `gemini_edited_render.png` side by side to directly observe differences in local edit precision, topology preservation, and downstream editability.

