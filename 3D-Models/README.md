# 3D Model Files for Disposable Vape Power Bank

This directory contains 3D model files for creating enclosures and cell holders for the disposable vape power bank project. The models are organized by USB board type and compatible cell lengths to make it easy to find the appropriate files for your build.
If your cells are not 30mm, 35mm or 40mm in length, you can modify the cell holder and enclosure .step models to fit your particular cell size.


## Overview
The project supports **two USB board types** and **three common cell lengths**:

### USB Board Types
1. [**Type 1 (Recommended)**](https://s.click.aliexpress.com/e/_oBGOqhR)
   - This is the primary USB board featured in the project video.
   - It is recommended for most users.
2. [**Type 2**](https://s.click.aliexpress.com/e/_oBXyxIH)
   - Features a larger screen and more USB ports.
   - Requires slightly different 3D printed parts due to the board's size and layout.

### Cell Lengths
The models are optimized for the following common cell lengths:
- **30mm cells**: Typically referred to as 13300 cells.
- **35mm cells**: Typically referred to as 13350 cells.
- **40mm cells**: Typically referred to as 13400 cells.

Each folder contains the necessary 3D models to build the enclosure and cell holder for the specified cell length.

---

## Directory Structure

The file structure is organized as follows:

```
├───USB Board Type 1
│   ├───30mm_cell
│   │   ├───Step
│   │   └───STL
│   ├───35mm_cell
│   │   ├───Step
│   │   └───STL
│   └───40mm_cell
│       ├───Step
│       └───STL
└───USB Board Type 2
    ├───30mm_cell
    │   ├───Step
    │   └───STL
    ├───35mm_cell
    │   ├───Step
    │   └───STL
    └───40mm_cell
        ├───Step
        └───STL
```

### Folders and File Types
- **Step Folder**: Contains `.step` files for the parts required for each different cell type, which can be used in CAD software for further modifications.
- **STL Folder**: Contains `.3mf` files optimized for 3D printing.
  - Includes parts like:
    - `cell_holder`
    - `enclosure_bottom`
    - `enclosure_top`
    - (for Type 2) `enclosure_top_tab`

---
