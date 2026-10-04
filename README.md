# CSS Box Model Diagram (Responsive)

An interactive, responsive visualization of the CSS Box Model (Margin, Border, Padding, and Content) built using nested HTML containers and pure CSS styling.

## Features

* **Visual Box Model Representation:** Color-coded structural containers illustrating the standard CSS Box Model layers:
  * **Outer Container (`.con`):** Outer viewport canvas (Teal)
  * **Margin Area (`.box`):** Margin layer representation (Sky Blue)
  * **Border Area (`.box1` border):** Solid border layer (Navy Blue)
  * **Padding Area (`.box1` content box):** Inner padding space (Blue)
  * **Content Area (`.box2`):** Core content container (Orange)
* **Fluid Responsive Units:** Designed using viewport height (`vh`), viewport width (`vw`), and percentage-based sizing to remain responsive across various screen dimensions.
* **Natural CSS Stacking:** Corrected HTML element DOM order to ensure absolute-positioned labels paint clearly over parent box layers without needing `z-index`.
* **Zero External Dependencies:** Built entirely using vanilla HTML5 and CSS3.

## Project Structure

```text
├── index.html        # Responsive box model diagram and embedded styles
