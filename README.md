# Japanese to English Excel Translator

This Python script automates the process of translating Japanese text in an Excel file to English. The script reads text from the first column of an Excel file, translates it into English using the [Google Translate API](https://py-googletrans.readthedocs.io/en/latest/), and saves the results in the second column of the same file.

---

## Features
- Automatically translates Japanese text to English.
- Reads and updates Excel files directly.
- Saves the translated output in a new file.

---

## Requirements

### **Prerequisites**
Ensure you have the following installed:
1. Python 3.8 or later
2. The following Python packages:
   - `openpyxl` (for handling Excel files)
   - `googletrans` (for translations)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://https://github.com/SapporoAlex/Translator-GoogleTrans-.git
   cd Translator-GoogleTrans-
   ```

2. Install dependencies:
   ```bash
  pip install openpyxl googletrans==4.0.0-rc1
  ``

## Usage
Place the Excel file you want to translate in the same directory as the script.

The file should have Japanese text in the first column.
The script will add the translations in column 2.
Update the script with the name of your file:

```python
file_name = "example.xlsx"  # Replace "example.xlsx" with your file's name
``

Run the script:

```bash
python translator.py
``

The translated file will be saved as:

```php
Translated <original_file_name>.xlsx
Example
Input Excel File (example.xlsx):
Column A (Japanese)	Column B (English)
こんにちは	
元気ですか？	
After Running the Script:
Column A (Japanese)	Column B (English)
こんにちは	Hello
元気ですか？	How are you?
```

## Notes
The script uses the googletrans library, which may occasionally experience outages or limitations. If translation fails, try running the script again later.
Ensure that your internet connection is stable while running the script, as it relies on the Google Translate API.

## Contributing
Contributions are welcome! Please submit a pull request or create an issue for suggestions or improvements.

## License
This project is licensed under the MIT License.
Feel free to replace placeholders like `your-username` and file names with actual details specific to your project!






