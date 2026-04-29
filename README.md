# ITPM Assignment 1 - Chat Translator Test Automation
**Student Registration Number:** IT23334410

## Prerequisites
To run this automation script, ensure you have the following installed:
* **Python 3.11+**
* **Playwright**: For browser automation (`pip install playwright`)
* **openpyxl**: For Excel file handling (`pip install openpyxl`)
* **Browser Engines**: `python -m playwright install chromium`

## Execution Instructions
1. Open the project folder in your terminal/VS Code.
2. Ensure the Excel file `IT23334410.xlsx` is closed.
3. Run the following command:
```bash
python test_automation.py --excel "IT23334410.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
