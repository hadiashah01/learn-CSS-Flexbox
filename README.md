## Introduction

This repository contains HTML and CSS code created to solve different layout design challenges.  
Each task involves converting a given visual layout into a working webpage using **HTML for structure** and **CSS (Flexbox) for layout, alignment, and styling.**

The repository includes both:

- **Challenge designs**

- **Coded solutions (HTML + CSS)**


## Purpose of This Repository

This repository is created to:

- Practice **HTML structure building** for Flexbox layouts

- Apply **CSS layout and styling techniques**

- Improve understanding of design cloning using code

- Learn how to **break complex layouts into manageable Flexbox sections**


## Challenges

- **Challenge-01: Complex Box Nesting Layout**  
  A box-based layout challenge created using **CSS Flexbox** to practice nesting, alignment, and spacing.  
 [View Challenge](./challenge-01/)

- **Challenge-02: Nested Flexbox Layout with BEM**
This challenge focuses on building a complex UI layout using nested Flexbox containers. The goal was to create a responsive, maintainable structure using BEM for semantic class naming, nested flex layouts, flex ratios, axis control, and alignment techniques.  
[View Challenge](./challenge-02/)


## Intended Structure

```bash
learn-CSS-Flexbox
│
├── challenge-02/
│   ├── index.html        HTML solution
│   ├── style.css         CSS styling
│   ├── images/       Challenge / reference layout
│   └── README.md        Challenge + solution details
│
├── challenge-01/
│   ├── index.html        HTML solution
│   ├── style.css         CSS styling
│   ├── images/        Challenge / reference layout
│   └── README.md        Challenge + solution details
│
└── README.md            Root documentation
```


## Topics Covered

The following concepts are practiced across all tasks:

- `display: flex`,`flex-direction`,`justify-content`,`align-items`

- `box-sizing`,`margin`,`border` and `padding`
  
- main axis vs cross axis
  
- box alignment, gap, alignment and spacing

- Visual layout cloning using code
  
- Nested Flexbox containers – multiple flex containers inside each other (`layout__main-top, layout__main-middle`, etc.)

- Flex ratios / flex-grow – like `.layout__main-middle :nth-child(1) { flex: 2; }`

- Axis control (main & cross axis) – e.g., `align-self: flex-end;`

- BEM methodology – classes like `layout__main-middle, layout__sidebar-item`

- Responsive layout basics – viewport height used (`75vh`)

- Column & row flex directions – using `flexbox--column` and default row

**NOTES:**

 - Focus is on layout and design, not functionality

 - No JavaScript or backend is included

 - Created strictly for learning and assignment purposes 
