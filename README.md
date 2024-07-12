# Seamless View Theme for Obsidian

Seamless View is a minimalist theme designed to **reduce the differences** between live preview mode and read mode. This provides a **seamless experience** when editing elements within a canvas, ensuring **consistency of card sizes**.

<p align="center">
  <img src="assets/Seamless View HD.png" alt="screenshot" style="max-width: auto;">
</p>

## Features

-   **Minimalist**: Reduces several unnecessary spaces, hides the mandatory empty line before any table, and adjusts the canvas menu to better utilize space.
-   **Dark mode**: A low-contrast dark mode that can be used during the day with warm colors for the night.
-   **Light mode**: A light mode inspired by Egyptian papyrus with warm colors to avoid straining the eyes.
-   **Newlines in read mode**: A `margin-bottom` of 1em between key elements to emulate empty lines from the live preview and keep the elements spaced out.
    -   between paragraphs, including embeddings.
        -   between a code block and other blocks, blockquotes, and callouts
    -   between a list and paragraphs, blockquotes, and callouts.
    -   between a blockquote or callout and other blockquotes, callouts, and paragraphs.
    -   between all the above elements and headers.
    -   between all the above elements and the end of the document.

<p align="center">
  <img src="assets/Dark Theme.png" alt="dark theme" style="max-width: auto;">
</p>
<p align="center">
  <img src="assets/Light Theme.png" alt="light theme" style="max-width: auto;">
</p>

## Plugin Styles Changes

-   [Admonition](https://github.com/javalent/admonitions): some extra spaces were removed (no `margin-bottom` is added to the element preceding an admonition in read mode).
-   [Dataview](https://github.com/blacksmithgu/obsidian-dataview): the `line-height` of dataview blocks in live preview mode and the style of bullet points in both modes were made consistent
-   [Kanban](https://github.com/mgmeyers/obsidian-kanban): some extra spaces were removed in board view.
-   [List Callouts](https://github.com/mgmeyers/obsidian-list-callouts): the background was aligned between both modes, and the color and thickness of the text were changed.
-   [QuickAdd](https://github.com/chhoumann/quickadd): the space in the settings of the commands was reduced.

## Installation

1. Open Obsidian and go to **Settings > Appearance**.
2. Click on the **Manage** button under the **Themes** section.
3. Search for **Seamless View** and click on the **Install and use** button.

## Support

If you encounter any issues with the Seamless View theme, please feel free to create an issue on the theme's GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the Obsidian community for their continuous support and feedback.

---

Enjoy a truly seamless experience with Seamless View in Obsidian!
