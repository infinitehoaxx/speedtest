# Speed Test Website with Dark Mode

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup](#setup)
5. [Usage](#usage)
6. [How It Works](#how-it-works)
7. [Customization](#customization)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This project is a simple, yet effective speed test website that allows users to measure their internet download and upload speeds. It features a clean, modern interface with the added functionality of a dark mode toggle for enhanced user experience.

## Features

- **Download Speed Test**: Measures the user's download speed in Mbps.
- **Upload Speed Test**: Measures the user's upload speed in Mbps.
- **Real-time Progress**: Displays progress bars for both download and upload tests.
- **Dark Mode Toggle**: Allows users to switch between light and dark themes.
- **Responsive Design**: Adapts to different screen sizes for optimal viewing on various devices.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Cloudflare Speed Test API](https://speed.cloudflare.com)

## Setup

1. Clone the repository or download the source code.
2. If you're using Replit:
   - Create a new HTML/CSS/JS repl.
   - Copy the contents of the provided HTML file into the `index.html` file in your repl.
3. If you're using a local environment:
   - Save the HTML file with a `.html` extension.
   - Open the file in a modern web browser.

No additional dependencies or build steps are required.

## Usage

1. Open the website in a web browser.
2. Click the "Start Speed Test" button to begin the test.
3. Wait for both download and upload tests to complete.
4. View your results displayed in Mbps.
5. To switch between light and dark modes, click the sun/moon icon in the top-right corner.

## How It Works

### Speed Test
- The speed test uses the Cloudflare Speed Test API to measure download and upload speeds.
- It performs a series of downloads and uploads over a 5-second period for each test.
- The speed is calculated based on the amount of data transferred in the given time.

### Dark Mode
- The dark mode toggle uses CSS classes to switch between light and dark themes.
- It changes the color scheme of the entire application, including backgrounds, text, and UI elements.

## Customization

You can customize various aspects of the speed test website:

1. **Colors**: Modify the CSS variables in the `<style>` section to change the color scheme.
2. **Test Duration**: Adjust the `testDuration` variable in the JavaScript code to change the length of each test.
3. **UI Elements**: Modify the HTML structure to add or remove elements as needed.

## Contributing

Contributions to improve the speed test website are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b infinitehoaxx/speedtest`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin infinitehoaxx/speedtest`).
5. Open a Pull Request.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

Feel free to reach out if you have any questions or need further assistance with the project!
