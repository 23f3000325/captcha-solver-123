# Captcha Solver Frontend

This project provides a simple, responsive frontend interface for displaying captcha images and allowing users to input their solutions. It's designed to be a standalone HTML file, leveraging Tailwind CSS for styling and vanilla JavaScript for interactivity.

## Features

*   **Dynamic Image Loading**: Load captcha images from a URL specified in the query parameter (`?url=https://.../image.png`).
*   **Default Image**: Automatically displays `sample.png` if no URL is provided.
*   **Custom URL Input**: Users can paste any image URL into an input field and load it.
*   **Captcha Solution Input**: A dedicated field for users to type their captcha solution.
*   **Responsive Design**: Built with Tailwind CSS for optimal viewing across various devices.
*   **Client-side interactivity**: Vanilla JavaScript handles image loading and submission display.

## Usage

1.  **Open `index.html` in your browser.**
2.  **Default Display**: The page will initially show `sample.png`.
3.  **Load Custom Image via URL Parameter**: To load a different image directly, append `?url=` followed by the image's URL to `index.html` in your browser's address bar.
    *   Example: `file:///path/to/your/index.html?url=https://example.com/some-captcha.png`
4.  **Load Custom Image via Input Field**: Alternatively, paste an image URL into the "Image URL" input field and click "Load Image".
5.  **Solve Captcha**: Type your perceived captcha solution into the "Enter Captcha" field.
6.  **Submit Solution**: Click the "Submit" button (or press Enter) to see what you entered. In a real-world scenario, this solution would be sent to a backend for validation.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: Utility-first CSS framework for responsive and modern styling.
*   **JavaScript (Vanilla)**: For dynamic image loading, URL parameter parsing, and interactive elements.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
