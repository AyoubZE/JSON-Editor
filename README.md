# JSON Editor (Two-Level Support)

A simple web-based JSON editor that allows users to upload, edit, and export JSON files. It supports editing up to two levels of nested objects, providing a user-friendly interface to modify JSON values and export the updated structure as a new JSON file.

## Features

- **Upload JSON**: Load a JSON file from your system.
- **View & Edit**: Display and edit key-value pairs in a table format.
- **Two-Level Nesting**: Supports editing JSON files with up to two levels of nesting.
- **Export**: Save and export the modified JSON back as a file.

## Technologies Used

- **HTML5**: For structuring the webpage.
- **JavaScript**: For handling file input, rendering, and data manipulation.
- **jQuery**: For DOM manipulation and event handling.
- **Bootstrap 4**: For responsive design and styling.

## How to Use

1. **Upload a JSON File**: Use the "Choose File" button to upload your JSON file.
2. **Edit the Data**: Modify the values of the JSON directly in the table displayed.
3. **Export the Updated File**: After making changes, click "Export JSON" to download the updated JSON file.

## Example JSON Format

```json
{
  "fruit.basket": {
    "apple": {
      "color": "red",
      "taste": "sweet",
      "info": {
        "origin": "USA",
        "season": "fall"
      }
    }
  }
}
```

Demo
Here's how the editor looks and functions:
https://codepen.io/Ayoub-ZeinEddin/full/GRVWjEZ

Installation
To use the JSON editor locally:

Clone the repository:

bash
Copy code
git clone https://github.com/AyoubZE/JSON-Editor.git
Open index.html in your web browser.

That's it! No additional setup is required.

Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements.

Fork the repo.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Submit a pull request!
License
This project is licensed under the MIT License. See the LICENSE file for more details.

