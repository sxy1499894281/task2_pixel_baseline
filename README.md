# Task2 Pixel Editing Baseline (Anonymous Release) - How to View

This directory is meant for quickly checking the differences between the "pixel editing baseline" and the "symbolic editing route" on Task 2. Each case is stored under `case_xxx/`.

## What each file in `case_xxx/` means
- `input.png`: rendered diagram before editing;
- `instruction.txt`: the English editing instruction for this sample;
- `pixel_edited.png`: output of the pixel-editing baseline;
- `xml_edited.png`: rendered PNG from the symbolic editing route;
- `input.xml` (optional): the original mxGraph XML before editing (open in Draw.io if interested);
- `xml_edited.xml` (optional): the mxGraph XML after symbolic edits (open in Draw.io if interested).

## Recommended viewing order
First, check `input.png` and `instruction.txt`. Then compare `pixel_edited.png` and `xml_edited.png` side by side to observe local edit precision, topology preservation, and downstream editability. The XML files are optional for reviewers and can be opened in Draw.io when deeper inspection is needed.

