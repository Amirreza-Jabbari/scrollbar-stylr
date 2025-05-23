


          
# .gitignore Generator

A simple, elegant web application that helps you quickly generate `.gitignore` files tailored to your specific project needs.

## Description

The .gitignore Generator is a tool that helps you quickly generate your .gitignore file adapted to your specific project needs so that unnecessary files and directories are correctly ignored by Git. This tool provides a clean, user-friendly interface for selecting technologies and frameworks to include in your .gitignore file.
# Scrollbar Stylr

A sleek, interactive web application for visually designing custom browser scrollbars and instantly generating the necessary CSS code.

## Description

Scrollbar Stylr empowers developers and designers to effortlessly customize the appearance of browser scrollbars to match their website's aesthetic. Say goodbye to default, clunky scrollbars! With a live preview and intuitive controls, you can tweak colors, dimensions, and border styles, then copy the cross-browser compatible CSS for easy integration.

## Features

-   **Live Preview**: See your scrollbar design update in real-time on the page and in a dedicated preview area.
-   **Comprehensive Controls**: Adjust:
    -   Thumb Color
    -   Track Color
    -   Width Style (Firefox: auto, thin, none)
    -   Width (WebKit: px)
    -   Thumb Border Radius (px)
    -   Thumb Border Width (px)
    -   Thumb Border Style (solid, dotted, etc.)
    -   Thumb Border Color
-   **Cross-Browser CSS Generation**: Outputs CSS for both Firefox (`scrollbar-width`, `scrollbar-color`) and WebKit-based browsers (Chrome, Edge, Safari, Opera - using `::-webkit-scrollbar` pseudo-elements).
-   **Copy to Clipboard**: Easily copy the generated CSS with a single click.
-   **Responsive Design**: A clean, modern UI that works seamlessly across all devices.
-   **Info Modal**: Quick instructions on how to use the tool and understand browser compatibility.
-   **Optional Debugger**: A built-in style debugger for development insights.

## Technologies Used

-   HTML5
-   Tailwind CSS
-   Vanilla JavaScript

## How to Use

1.  **Access the Tool**: Open `index.html` in your web browser.
2.  **Adjust Controls**: Use the input fields and color pickers in the "Customize" panel to design your scrollbar.
3.  **Observe Live Preview**: Watch the scrollbar on the main page and within the "Live Preview" box update instantly.
4.  **Copy CSS**: Once satisfied with your design, click the "Copy CSS" button in the "Generated CSS" panel.
5.  **Integrate**: Paste the copied CSS into your website's stylesheet.
6.  **Learn More**: Click "How does this work?" for a quick guide and compatibility notes.

## Getting Started (Local Setup)

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/your-username/scrollbar-stylr.git](https://github.com/your-username/scrollbar-stylr.git)
    ```
    (Replace `your-username/scrollbar-stylr.git` with the actual repository URL if you host it on GitHub)
    Alternatively, if you have the `index.html` file directly, you can skip this step.

2.  **Navigate to the project directory:**
    ```bash
    cd scrollbar-stylr
    ```

3.  **Open `index.html` in your browser.**

## Browser Compatibility Notes

-   **Firefox**: Uses `scrollbar-width` and `scrollbar-color` properties. These offer less granular control (e.g., no direct way to style thumb border radius).
-   **WebKit Browsers (Chrome, Safari, Edge, Opera)**: Use the `::-webkit-scrollbar`, `::-webkit-scrollbar-track`, and `::-webkit-scrollbar-thumb` pseudo-elements, allowing for more detailed styling.
-   The generated CSS aims to provide the best possible compatibility for both rendering engines. Always test your final design in your target browsers.

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes:

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE) (assuming you will add one).

## Acknowledgments

-   Inspired by the need for simple, effective scrollbar customization.
-   Built with the powerful Tailwind CSS utility-first framework.

---
## Features

- **Search Functionality**: Easily search for technologies from a comprehensive list
- **Multiple Selection**: Add multiple technologies to your .gitignore file
- **Real-time Preview**: Generate and preview your .gitignore content before downloading
- **Download Option**: Download the generated .gitignore file directly
- **Copy to Clipboard**: Copy the generated content to your clipboard with one click
- **Responsive Design**: Clean, modern UI that works on all devices

## Technologies Used

- HTML5
- CSS (TailwindCSS)
- JavaScript (Vanilla)

## How to Use

1. **Search for Technologies**: Type in the search box to find technologies you want to include
2. **Select Technologies**: Click on suggestions to add them to your selection
3. **Generate File**: Click the "Generate file" button to create your .gitignore content
4. **Download or Copy**: Either download the file or copy the content to your clipboard
5. **Remove Technologies**: Click the "×" on any selected technology to remove it


1. Clone the repository:
```bash
git clone https://github.com/Amirreza-Jabbari/gitignore_generator.git
```

2. Open `index.html` in your browser


## Contributing

Contributions are welcome! If you'd like to add more templates or improve the functionality:

## License

This project is open source and available under the [MIT License](LICENSE).
        