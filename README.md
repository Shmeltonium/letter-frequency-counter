# Letter Frequency Counter

A simple web-based application that counts the frequency of letters (A–Z) in user-entered text, displays it on a bar chart using Chart.js, and allows toggling between alphabetical order and most-frequent-first order.

## Features
- **Real-time Analysis**: Counts letters A–Z (case-insensitive).
- **Toggle Sort Mode**: Switch between alphabetical and descending-frequency sorting.
- **Clear / Reset**: Quickly clear the text input and reset the chart.
- **Data Labels**: Displays exact frequency counts atop each bar.
- **Responsive Chart**: Resizes with the browser window, ensuring a modern look and feel.

## How to Use
1. **Clone** this repository or **download the ZIP**.
2. Open the `index.html` file in your web browser.
3. Type (or paste) text into the text area.
4. Click **Count** to see letter frequencies.
5. **Toggle Sort Mode** to switch between alphabetical and most-frequent-first.
6. **Clear** to reset the text input and chart.

## Technology Stack
- **HTML5** for the structure.
- **CSS** (inline in the `<style>` block) for basic styling.
- **JavaScript** for the logic.
- [**Chart.js**](https://www.chartjs.org/) and [**chartjs-plugin-datalabels**](https://github.com/chartjs/chartjs-plugin-datalabels) for the bar chart and data labels.

## File Overview
- **index.html**  
  Main file containing all of the HTML, CSS, and JavaScript (along with Chart.js + plugin from CDNs).

## Possible Improvements
- Add a log-scale toggle for extremely large letter count differences.
- Support international characters beyond A–Z.
- Display total counts (alphabetic vs. non-alphabetic).

## License
