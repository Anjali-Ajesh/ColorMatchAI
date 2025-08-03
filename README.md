# ColorMatchAI
An interactive web application that uses color theory rules and simulated machine learning to help users generate, evaluate, and explore color palettes for UI/UX, branding, or any creative project.
## Features

-   **Color Palette Generator:** Input a base color using a color picker or hex code and instantly generate palettes based on established color harmonies:
    -   Complementary
    -   Analogous
    -   Triadic
    -   Split-Complementary
    -   Monochromatic
-   **Emotion-Based Suggestions:** Type a keyword (e.g., "luxury," "calm," "energetic") to get a curated color palette that matches the mood. (Simulated ML)
-   **Color Naming:** Enter a hex code, and the tool will predict its common name (e.g., #87CEEB → "Sky Blue"). (Simulated ML)
-   **WCAG Accessibility Checker:** Check the contrast ratio between any two colors to ensure your text is readable and your design is accessible.
-   **Live UI Preview:** See your generated palettes applied instantly to a set of mock UI components (buttons, cards, text) to get a real-world feel for your color choices.

## Technology Stack

-   **HTML5:** For the application structure.
-   **Tailwind CSS:** For a modern, responsive layout.
-   **Vanilla JavaScript:** For all application logic, including color theory calculations, DOM manipulation, and interactive features.
-   **Chroma.js:** A powerful JavaScript library for color conversions and calculations, loaded via CDN.

## Setup and Usage

This project is a single, self-contained HTML file and requires no installation or build steps.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Anjali-Ajesh/colormatch-ai.git](https://github.com/Anjali-Ajesh/colormatch-ai.git)
    cd colormatch-ai
    ```

2.  **Open the HTML File:**
    Simply open the `index.html` file in any modern web browser to start using the tool.
