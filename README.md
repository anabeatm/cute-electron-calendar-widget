# 🌸 Cute Calendar Widget

A simple, aesthetic desktop calendar widget built with **Electron**. This application displays the current date in a cute, compact, and semi-transparent window that sits perfectly on your desktop.

![Project Preview](C:\Users\anabe\electron-calendar\sheets\calendar-preview.png)

> _Note: Imagine a cute pink calendar here!_

## 📺 Inspiration

This project is based on the tutorial **"How to code your first cute application from scratch"** by [Nashallery](https://www.youtube.com/watch?v=btxGSJ3Dh8E).

Check out her video for a step-by-step guide!

## ✨ Features

- **Real-time Date:** Displays the current day and month dynamically using JavaScript.
- **Aesthetic UI:** Custom CSS styling with a cute pink theme and rounded corners.
- **Transparent Background:** The app features a semi-transparent background (opacity 0.8) for a modern look.
- **Draggable Window:** Custom title bar logic allowing you to drag the widget anywhere on your screen.
- **Compact Size:** Fixed window size (214x228) designed to be a subtle desktop accessory.

## 🛠️ Technologies Used

- **[Electron](https://www.electronjs.org/)**: Framework for building desktop apps with web technologies.
- **Node.js**: Runtime environment.
- **HTML5 & CSS3**: For structure and styling.
- **JavaScript**: For app logic and date manipulation.

## 📂 Project Structure

```text
├── main.js        # Main process for Electron (window creation, config)
├── index.html     # The layout of the calendar
├── styles.css     # Styling for the "cute" aesthetic
├── script.js      # Logic to fetch and display the current date
├── package.json   # Dependencies and scripts
└── assets/        # Images for backgrounds (optional)
```

## 🚀 Getting Started

Follow these steps to run the application on your local machine.

### Prerequisites

Make sure you have **Node.js** installed. You can download it [here](https://nodejs.org/).

### Installation

1. **Clone the repository** (or download the files):

   ```bash
   git clone [https://github.com/yourusername/cute-calendar-widget.git](https://github.com/yourusername/cute-calendar-widget.git)
   cd cute-calendar-widget
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   npm run start
   ```

## 🎨 Customization

Feel free to tweak the styles.css to change the colors or fonts!
Change Background: Update the body background color or image in CSS.
Window Size: Modify the width and height in main.js to resize the widget.

## 🤝 Contributing

Contributions are welcome! If you have ideas to make it even cuter, feel free to fork the repo and submit a pull request.

## 📝 License

Distributed under the MIT License. See LICENSE for more information.

#### Made with 💖 and code.
