# Excel Translator (CFILT API)

Translate text from Excel sheets using the IIT Bombay CFILT API.

## 🔧 Features

- Supports Excel files with multiple sheets
- Translates every text cell to a target language
- Creates new `_translated` sheets
- Keeps formatting intact

## 🚀 Usage

### Installation

1. Clone the repository:

```bash
git clone https://github.com/sourabhd13/excel-translator-ishaan.git
cd excel-translator-ishaan
```

2. Install the dependencies:

```bash
pip3 install -r requirements.txt
```

3. Configure:
Update your API endpoint at the top of `excel_translator.py`:

```python
# API endpoint
API_URL = "Add the API endpoint here."
```

4. Run:
```bash
python3 excel_translator.py --filepath path/to/your/excel_file.xlsx --source <source_language_code> --target <target_language_code>
```

#### Arguments:

* `--filepath`: Path to the Excel file you want to translate (required)
* `--source`: Source language code (default: `en`)
* `--target`: Target language code (default: `ne`)

---

## 🔧 Example

```bash
python3 exceLl_translator.py --filepath my_excel.xlsx --source en --target ne
```

This will create a new Excel file called `translated_my_excel.xlsx` with all sheets translated to Nepali.

---
