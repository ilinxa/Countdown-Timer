# Countdown Timer

A simple, responsive countdown timer web component built with HTML, CSS, and JavaScript.

## Features

- **Live Countdown:** Displays days, hours, minutes, and seconds remaining until a specified date (default: August 30th).
- **Responsive Design:** Adapts to different screen sizes for mobile and desktop.
- **Celebration Animation:** Shows emoji celebration when the countdown reaches zero.

## Usage

1. **Open `index.html`** in your browser.
2. The timer will automatically count down to the next August 30th.
3. When the countdown ends, a celebration message and emojis are displayed.

## Customization

- To change the countdown date, modify the `dayMonth` variable in the script section of [`index.html`](index.html):

  ```js
  // ...existing code...
  let dayMonth = "08/30/"; // Change to your desired MM/DD/
  // ...existing code...
  ```

- You can also update the headline text by editing the `<h1 id="headline">` element.

## File Structure

- [`index.html`](index.html): Main HTML file containing all markup, styles, and JavaScript.

## License

This project is open source and free to use.
