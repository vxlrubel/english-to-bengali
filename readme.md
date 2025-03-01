# English to Bengali Converter

A simple JavaScript-based English-to-Bengali phonetic converter that instantly transliterates English text into Bengali as you type.

## Features

- Instant transliteration from English to Bengali.
- Uses JavaScript for real-time conversion.
- Lightweight and easy to integrate.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/vxlrubel/english-to-bengali.git
   ```
2. Open `index.html` in your browser.

## Usage

1. Include the script in your HTML file:
   ```html
   <script src="english-to-bengali.js"></script>
   ```
2. Add an input field and an output area:
   ```html
   <input type="text" id="englishText" placeholder="Type Bangla in English">
   <p>Output: <span id="banglaOutput"></span></p>
   ```
3. Use JavaScript to handle real-time conversion:
   ```html
   <script>
       document.getElementById("englishText").addEventListener("keyup", function () {
           let inputText = this.value;
           let banglaText = RubelMahmud.TranslateToBengali.Convert.parse(inputText);
           document.getElementById("banglaOutput").innerText = banglaText;
       });
   </script>
   ```

## License

This project is open-source and available under the MIT License.

