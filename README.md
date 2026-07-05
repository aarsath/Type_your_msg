# Character Counter Textarea

A simple, lightweight character counter for text input, built with vanilla HTML, CSS, and JavaScript. Users can type a message and see a live count of characters used out of a 200-character limit, with a warning displayed once the limit is reached.

## Features

- 📝 Live character count as you type
- 🚫 Enforces a maximum limit of 200 characters
- ⚠️ Displays a warning message when the limit is reached
- 🎨 Clean, responsive, centered card-style UI
- 📦 No dependencies — pure HTML, CSS, and JavaScript

## Demo

Simply open `index.html` in any modern web browser to try it out.

## Project Structure

```
├── index.html   # Main HTML file with embedded CSS and JavaScript
└── README.md    # Project documentation
```

## How It Works

1. The user types a message into the `<textarea>`.
2. An `input` event listener tracks the number of characters typed.
3. The character count is displayed live (e.g., `45/200 characters`).
4. If the input reaches the 200-character limit:
   - Further typing is blocked (input is trimmed to 200 characters).
   - A warning message ("Character limited!") is displayed in red.

## Getting Started

### Prerequisites

No installation or dependencies required — just a web browser.

### Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```bash
   cd your-repo-name
   ```
3. Open `index.html` in your browser:
   ```bash
   open index.html   # macOS
   start index.html  # Windows
   ```

## Customization

- **Change the character limit:** Update the `maxChars` variable in the `<script>` section of `index.html`.
- **Change colors/styling:** Modify the CSS rules inside the `<style>` section (`.container`, `.warning`, `body`, etc.).

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla, ES6)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) if you want to contribute.

## Author

Made with ❤️ by [Your Name](https://github.com/your-username)
