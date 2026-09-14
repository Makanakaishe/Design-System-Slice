**Design Sytem Slice**

Everything for this project is packaged in the design-system-slice.zip file in this repository — unzip it to get the full folder structure (components, tokens, Storybook config, and styles) ready to install and run.

**What this is**

A small, foundational slice of a design system: a shared set of design tokens (colors, spacing, typography) and four core UI components built on top of them, each documented and previewable in Storybook.

It's meant as a starting point that can grow — new components follow the same pattern already set up here (a .tsx file, a .module.scss file, and a .stories.tsx file per component).

**What's inside the zip**

Design tokens — a single source of truth for color, spacing, and typography, available both as SCSS variables (for styling) and a plain TypeScript object (for anywhere else you need the values)

Button — primary/secondary variants, small/medium sizes, disabled state

Input — labeled text field with an error state

Badge — status pill in neutral/success/danger tones

Card — simple bordered container for grouping content

Storybook setup — so every component and its states can be viewed and clicked through in the browser, without building a real app around them

Stylelint config — keeps the SCSS consistent as more components are added

**Getting started**

Unzip design-system-slice.zip
npm install
npm run storybook

Storybook opens at http://localhost:6006 with every component listed on the left.
