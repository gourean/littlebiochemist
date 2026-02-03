# Little Biochemist

This is an interactive educational sandbox designed to help users visualize and experiment with biochemical pathways, enzymes, and molecules. Built with simplicity and interactivity in mind, it provides a drag-and-drop interface to explore metabolic processes like Glycolysis, the TCA Cycle, Beta-Oxidation, and more.

## Features

-   Interactive Workbench: A play area where you can drag and drop molecules, enzymes, and pathways to see how they interact.
-   Dynamic Visualization: Molecules are rendered dynamically using SVGs, showing structural details like carbon chains, bonds, and specific atoms.
-   Enzyme Logic: Drop molecules into enzyme boxes to trigger reactions. Valid reactions produce new products, while invalid ones are rejected with visual feedback.
-   Comprehensive Library: Includes a wide range of biochemical entities:
    -   Molecules: Glucose, Pyruvate, Fatty Acids (various chain lengths), ATP, NADH, etc.
    -   Enzymes: Pyruvate Dehydrogenase, Citrate Synthase, Fatty Acid Synthase, and many more.
    -   Pathways: High-level abstractions of complex processes like the TCA Cycle and Electron Transport Chain.
-   Responsive Design: optimized for both desktop and touch devices.
-  Topic mode: Structured learning paths to master metabolic concepts one step at a time.

## Game Modes

### Sandbox Mode
The classic experience. Free exploration of all molecules, enzymes, and pathways without restrictions. Build complex reactions and see what happens!

### Topic Mode
A structured learning experience with specific objectives.
-   Lipolysis: Break down fats into glycerol and fatty acids.
-   Activatio*: Prepare fatty acids for oxidation.
-   Beta-Oxidation: Generate energy from fatty acids.
-   Ketogenesis: Produce ketone bodies in the liver.
-   TCA Cycle:Complete the cycle from OAA

## How to Run

This is a static web application with no build step required.

1.  Clone the repository or download the source code.
2.  Simply open `index.html` in any modern web browser.
3.  Start experimenting!

## Technology Stack

-  HTML5: Semantic structure and SVG generation.
-   CSS: Styled with [Tailwind CSS](https://tailwindcss.com/) (via CDN) and custom CSS for specific animations and effects.
-   JavaScript (Vanilla): Handles all game logic, state management, drag-and-drop mechanics, and SVG rendering.

## Controls & Mechanics

1.  Choose Your Mode: Start with **Sandbox** for free play or **Campaign** to solve specific biochemical puzzles.
2.  Select Items: Use the sidebar tabs (Molecules, Enzymes, Pathways) to browse available items.
3.  Add to Workbench: Click an item in the inventory to spawn it on the workbench.
4.  Experiment: Drag molecules into Enzyme or Pathway boxes.
    -   If the inputs are correct (e.g., Pyruvate into Pyruvate Dehydrogenase), a reaction occurs, and products are generated.
    -   If incorrect, the box will shake to indicate rejection.
5.  Clean Up: Drag items to the trash bin to remove them from the workspace.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


