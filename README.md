# 📄 Multilingual Bingo Card Maker

A lightweight, robust, and browser-based **Bingo Card Generator** designed for educators and event organizers. This tool allows for the creation of randomized Bingo cards and matching "Call Lists" with native multi-language support and precise print controls.

## ✨ Key Features

* **Multi-Language Logic**: Supports single-word lists or `English = Vernacular` pairs to allow for instant switching between bilingual and monolingual modes.
* **Unique Randomization**: Features a robust shuffling algorithm that ensures every card in a set is unique.
* **Built-in Wordlist Manager**: Save and load up to three different wordlists using local browser storage.
* **Professional Call List**: Automatically generates a teacher/caller sheet with five tracking checkboxes per word for multiple rounds of play.
* **Advanced Print Customization**: 
    * **Paper Sizes**: Support for A4, Letter, and Legal.
    * **Typography**: Adjustable font sizes and support for custom system fonts.
    * **Layout**: Fine-tune cell height, card spacing, and print margins.

---

## 🚀 How to Use

1.  **Open the Tool**: Simply open the `Bingo - most bug free so far.html` file in any modern web browser.
2.  **Input Your Words**: 
    * Enter words separated by commas or new lines.
    * For bilingual cards, use the format: `English = Vernacular`.
3.  **Manage Wordlists**: Use the "Quick Start" section to upload `.txt` or `.csv` files or save your current list to one of the three slots.
4.  **Configure Settings**: Click **Advanced Settings** to adjust the font size, cell height, or paper margins to fit your specific printer.
5.  **Generate & Print**: Select the number of cards (up to 100), click **Generate**, and then **Print**.

---

## 🛠️ Technical Details

* **Grid Size**: 4x4 (16 cells) - default. 3x3 and 5x5 available in a dropdown select box
* **Zero Dependencies**: Written in pure HTML, CSS, and Vanilla JavaScript—no internet connection required to run.
* **Storage**: Uses `localStorage` to keep your settings and wordlists persistent across sessions.
* **Print Optimization**: Utilizes `@media print` CSS to ensure UI elements like buttons and inputs are hidden on the final paper copy.

---

## 📝 Formatting Guide

To utilize the bilingual toggle features, ensure your input follows this syntax:

```text
Apple = Manzana
Orange = Naranja
Grapes = Uvas
