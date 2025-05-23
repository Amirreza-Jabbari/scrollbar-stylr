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