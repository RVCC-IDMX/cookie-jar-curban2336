# The Cookie Jar - Layout Challenge

This project is a design and development exercise to create an interesting, responsive layout for a showcase of cookie recipe cards. It is an **exploration assignment** where your creativity, reasoning, and understanding of modern CSS layout techniques are the primary focus.

## Getting Started

1. Using Live Server, open the `index.html` file in the Chrome browser.
2. Then open Chrome Dev Tools.
3. Resize the viewport window from a narrow mobile width to a wide desktop width to observe the default behavior.
4. All of your work will be done in the `css/layout.css` file.

## Project Structure

The project is organized to provide you with a clear starting point. You are encouraged to explore the files, but your primary workspace is `css/layout.css`.

- `index.html`
  - This file contains the complete and semantic HTML structure for the page, including all 8 recipe cards.
  - **Your Role**: You should not need to modify this file for the core assignment, but you are not forbidden from doing so if you have a strong reason, which you should document.

- `css/style.css`
  - This file contains all the base styling, including colors, typography, shadows, and the default mobile-first appearance of the cards. It uses CSS Custom Properties (e.g., `--color-chocolate`, `--space-md`) for design tokens.
  - **Your Role**: Treat this as a read-only library of styles. Your work in `layout.css` will build upon these existing styles.

- `css/layout.css`
  - **This is your workspace.** This file is intentionally empty. All of your layout code should be written here.

- `data/`
  - This directory contains `cookies.json`, which provides the data structure for the recipes.
  - **Your Role**: This is for reference and context only. You do not need to interact with this file for the assignment.

- `images/`
  - This directory contains all the `.png` image files used in the recipe cards.

- `reports/`
  - This directory contains documentation related to the project. It is also where you should save your final reflection document.

## Your Task

Your challenge is to take the default, mobile-first layout and create an engaging, responsive experience for wider viewports (tablet, desktop, and beyond).

The key constraint is to achieve this by exploring modern CSS techniques and **using traditional viewport-based media queries as little as possible**. The goal is to build an *intrinsic* layout that adapts naturally to the space it has.

Focus on exploring:

- **Container Queries** (`@container`)
- **Intrinsic Grid Layouts** (`repeat(auto-fit, minmax())`)
- **CSS Custom Properties** (`--variables`)
- **Modern Image Handling** (`aspect-ratio`, `object-fit`)

This is a playground for learning. There are many valid solutions. Focus on creating something that works well, that you understand, and that you can explain. Good luck!
