# JSON Converter

This simple web page lets you convert a JSON file to CSV.

## Usage

1. Open `index.html` in your web browser.
2. Select a JSON file using the file input.
3. Once loaded, choose the fields you want to include in the CSV.
4. Click **Generate CSV** to preview the result.
5. Review the preview and use the **Download CSV** link to save the file.

Nested objects are flattened using dot notation (e.g. `user.name`). Arrays are stringified.
