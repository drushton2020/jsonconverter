# JSON Converter

This simple web page lets you convert a JSON file to CSV.

## Usage

1. Open `index.html` in your web browser.
2. Select a JSON file using the file input.
3. Once loaded, choose the fields you want to include in the CSV.
4. Click **Generate CSV**.
5. Download the generated CSV using the provided link.

Nested objects are flattened using dot notation (e.g. `user.name`). Arrays are stringified.
