# Plotter Text Tool

A web-based text generation tool for assistive pen plotters, designed for the TOM Plotter project.

## Features

- **Hershey Single-Stroke Fonts**: Uses Hershey vector fonts optimized for pen plotters - these fonts draw with single strokes rather than outlines, making them ideal for plotting
- **Real-Time Preview**: Interactive canvas showing exactly how your text will be plotted
- **Customizable Text Settings**:
  - Multiple font styles to choose from
  - Adjustable font size
  - Precise X/Y positioning with click-to-place support
- **Text Sequence Queue**: Add multiple text items to create complex compositions
- **G-Code Export**: Export your designs directly to G-Code for use with CNC machines and pen plotters

## Usage

1. Visit the live tool at: https://kblacu.github.io/plotter-text-tool/
2. Enter your text in the input panel
3. Select a font style from the grid
4. Adjust size and position using the sliders or click on the canvas
5. Add text to the sequence queue to build up your design
6. Export to G-Code when ready

## Technology

Built with:
- [p5.js](https://p5js.org/) - Creative coding library for the canvas preview
- [p5-hershey-js](https://github.com/LingDong-/p5-hershey-js) - Hershey font rendering for p5.js

## Credits

Single-line Hershey font resources by [Lingdong Huang](https://github.com/LingDong-) and [Golan Levin](https://github.com/golanlevin):
- [p5-single-line-font-resources](https://github.com/golanlevin/p5-single-line-font-resources/tree/main/lingdong_hfedit)

## About

This tool was created as part of the Adaptive Drawing Machine project at CMU, designed to make pen plotting more accessible.

## License

MIT License

