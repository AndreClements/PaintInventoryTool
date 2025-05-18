# André's Paint Inventory & Mixing Lab

A self-contained HTML, CSS, and JavaScript tool for managing paint inventories and simulating subtractive color mixes based on Kubelka-Munk theory. This project aims to provide artists with a digital way to explore color interactions and materiality.

**[Link to Live Demo Here - You'll get this after setting up GitHub Pages]**

## Background & Context

This tool was developed as part of a digital journey exploring color theory and paint materiality. For more context and the initial thoughts behind this project, please see the blog post:
[Unpacking a Palette: A Digital Journey and Tool for Oil Color Mixing & Materiality](https://andresclements.com/1189/unpacking-a-palette-a-digital-journey-and-tool-for-oil-color-mixing-materiality/)

## Features (v0.10.5)

*   **Paint Inventory Management:**
    *   List paints with details: Brand, Pigment(s), L\*a\*b\* values, HSL(A) values, Series, Temperature, Opacity, and Notes.
    *   Visual swatches for masstone and simulated glazes/mixes.
    *   Global toggle for compact or detailed inventory view.
*   **Selection & Filtering:**
    *   Select/deselect individual paints for mixing.
    *   "Select All Visible" / "Deselect All Visible" functionality.
    *   Filter paints by Opacity (All, Opaque, Semi-Transparent, Transparent).
*   **Kubelka-Munk Mixing Grid:**
    *   Simulates 1:1 (and other ratio) mixes between selected paints using Kubelka-Munk RGB logic.
    *   Sortable rows and columns by various attributes (Name, L\*, a\*, b\*, Hue, Saturation, Opacity, Selection Order, Random).
    *   Click-to-view tooltips showing the mix components.
*   **Customization:**
    *   Changeable page background (Checkered, Neutral Grey, White, Black, Primary/Secondary colors) to test color appearance.
*   **Mobile-Friendly Design:** Responsive layout for use on various devices.
*   **Self-Contained:** Runs entirely in the browser from a single HTML file. No server-side components or external dependencies required.

## Technologies Used

*   HTML5
*   CSS3
*   Vanilla JavaScript (ES6+)

## How to Use

1.  **Live Demo:** Visit the live demo link at the top of this README (once available after GitHub Pages setup).
2.  **Locally:**
    *   Clone this repository: `git clone https://github.com/AndreClements/PaintInventoryTool.git` (replace with your actual repo URL)
    *   Or download the `index.html` file directly.
    *   Open `index.html` in any modern web browser.

## Future Development Ideas

*   Saving/loading palettes (localStorage or file export/import).
*   More advanced glaze simulation options (e.g., variable thickness).
*   Undo/redo for selections.
*   User-defined paints and custom L\*a\*b\* input.
*   Visual representation of K/S values.
*   Integration of spectral data if available for more accurate K-M.

## Contributing

Contributions, issues, and feature requests are welcome! Please feel free to:
*   Open an issue to report bugs or suggest features.
*   Fork the repository and submit a pull request with your improvements.

When contributing, please try to adhere to the existing coding style.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Author

*   **André Clements**
    *   GitHub: [AndreClements](https://github.com/AndreClements)
    *   Blog: [andresclements.com](https://andresclements.com/)

---
_This README is for version 0.10.5 of the tool._