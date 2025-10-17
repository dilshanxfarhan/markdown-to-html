# Markdown to HTML Converter

This is a simple, single-page web application designed to convert Markdown content from `input.md` into rendered HTML, displayed directly in your browser. It utilizes modern web technologies to provide a responsive and user-friendly experience.

## Features

- Converts `input.md` to HTML dynamically using JavaScript.
- Renders the content directly within the `index.html` page.
- Fully responsive design using Tailwind CSS.
- Lightweight and dependency-managed via CDN for `marked.js` and Tailwind CSS.

## Technologies Used

- **HTML5:** For structuring the web page.
- **Tailwind CSS:** A utility-first CSS framework for rapid and responsive UI development.
- **JavaScript (ES6+):** For fetching the Markdown file and performing the conversion.
- **Marked.js:** A fast Markdown parser and compiler written in JavaScript.

## Setup and Usage

Getting this application up and running is incredibly simple:

1.  **Ensure `input.md` is present:** Make sure the `input.md` file (containing your Markdown content) is located in the **same directory** as `index.html`.
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

That's it! The JavaScript embedded in `index.html` will automatically fetch `input.md`, convert its content to HTML, and display it on the page.

## Project Structure

```
.
âââ index.html          # The main application page
âââ input.md            # The markdown file to be converted and displayed
âââ README.md           # This readme file
âââ LICENSE             # MIT License details
```

## Customization

-   To change the Markdown content, simply edit the `input.md` file.
-   To modify the styling, adjust the Tailwind CSS classes within `index.html` or add custom CSS.
-   To change the Markdown parsing options, refer to the `marked.js` documentation and modify the `marked.setOptions()` call in `index.html`.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.