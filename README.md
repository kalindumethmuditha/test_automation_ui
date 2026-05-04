# PixelsSuite Playwright Automation Testing

## Project Description

This project contains a Playwright automation test created for **IT3040 – ITPM Assignment 1, Option 2: Functional and Usability Testing of a Website**.

The selected website for testing is **PixelsSuite**: https://www.pixelssuite.com/

The automation test verifies the **preview functionality** of an image-related feature by uploading a valid PNG image and checking whether the image is displayed correctly in the preview section.

This project uses **Python**, **Playwright**, and **OpenPyXL** to execute the automated UI test and record the execution result in the provided CSV file.

---

## Assignment Details

| Item | Details |
|---|---|
| Module | IT3040 – ITPM |
| Assignment | Assignment 1 |
| Option | Option 2 |
| Testing Type | Functional and Usability Testing |
| Website | PixelsSuite |
| Automation Tool | Playwright |
| Programming Language | Python |

---

## Automated Test Scenario

| Item | Details |
|---|---|
| Application | PixelsSuite |
| Feature Tested | Image Format Conversion / Image Preview |
| Test Scenario | Verify image preview functionality after uploading a valid PNG image |
| Test Type | Functional UI Automation Testing |
| Test Data | Valid PNG image file |
| Expected Result | Uploaded image should be displayed in the preview section |

---

## Tools and Technologies Used

- Python
- Playwright
- OpenPyXL
- Command Prompt
- GitHub

---

## Project Structure

```text
test_automation_ui/
│
├── image_preview_test.py
├── execution_results.csv
├── README.md
├── sample.png
└── other required project files
```

---

## Prerequisites

Before running the test, make sure Python is installed on your computer.

To check whether Python is installed, run:

```bash
python --version
```

If Python is not recognized, install Python and make sure to select **"Add python.exe to PATH"** during installation.

If the `python` command does not work, try:

```bash
py --version
```

---

## Installation and Setup

### 1. Open the Project Folder

Open Command Prompt and navigate to the project folder:

```bash
cd /d D:\test_automation_ui
```

### 2. Install Required Dependencies

Run the following commands one by one:

```bash
python -m pip install -U pip
python -m pip install playwright openpyxl
python -m playwright install
```

> **Note:** If the `python` command does not work, replace `python` with `py` in all commands above.

---

## Running the Test

Run the following command inside the project folder:

```bash
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```

> **Note:** If the `python` command does not work, use `py` instead:
>
> ```bash
> py image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
> ```

---

