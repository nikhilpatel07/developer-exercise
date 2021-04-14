# Basic ToolBox - How to move basic toolbox left or right guide

## Introduction

### Toolbox will be placed initially on Right Side (as per mock-up). If user like to move toolbox on left side then user need add `@import "module-toolbox-left"` (already available just remove two forward slash //) Please read below steps to move toolbox right and left.

## Instructions for compiling CSS

- You can use different compiling process but if you like you can download "CodeKit" software available free.
- Upload root folder on "CodeKit" and select file `production.scss` basic_toolbox > css > scss > `production.scss` you will find "options" on right side of interface.
- Select `Output Style = Nested`, `Debug info = Print Line Number in CSS`, `After Compiling = Run Autoprefixer on the CSS file`.
- You can select output loaction outside of SCSS folder

## Instruction to switch toolbox left or right

- Open file `_partial-custom` from basic_toolbox > css > scss > `_partial-custom` in code-editor
- Go to line number `#6` and remove two forward slashes `//`. It will make `@import "module-toolbox-left"` file active and upon save CodeKit will compile CSS
- Refresh index.html file or uploading on any Browser you can see Toolbox moved to Left
- To move Toolbox back add two forward slashes `//` on line number `#6` and toolbox will move to right
