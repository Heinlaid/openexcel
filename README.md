# Open Excel - Chrome Extension

## 📌 Description
**Open Excel** is a Google Chrome extension that lets you **open and view Excel files (.xls, .xlsx) directly in your browser**. You can upload a file via the file dialog or simply drag and drop it into the extension. If you need online collaboration or further editing, you can **upload the file to your Google Drive and edit it in Google Sheets**—all from within this extension.

## 🚀 Features
- **Open & View Excel Files**: `.xls` and `.xlsx` files right in your browser, no external software needed.  
- **Drag & Drop**: Easily drop an Excel file to open it.  
- **Multi-Sheet Support**: Switch between multiple sheets in a single workbook.  
- **Zoom Controls**: Adjust the spreadsheet size for better readability.  
- **Preserves Cell Dimensions**: Column widths and row heights are displayed as in the original file.  
- **Table Borders**: Retains visible cell borders from your Excel workbook.  
- **Save as PDF**: Print or export your Excel sheet as a PDF file.  
- **Edit in Google Sheets**: Optionally upload your file to Google Drive for editing in Google Sheets.

## 📥 Installation
1. Download the extension from the [Chrome Web Store](#).
2. Click **"Add to Chrome"**.
3. Open the extension and select an Excel file to view or drag and drop it into the viewer.

## 🛠 How It Works
1. Click the **extension icon** in your browser toolbar.  
2. Select an Excel file from your computer **or** drag & drop it into the viewer.  
3. Use the **sheet tabs** to switch between multiple sheets.  
4. Adjust the zoom to your liking.  
5. Click **"Save as PDF"** to export the sheet as a PDF file.  
6. Click **"Edit in Google Sheets"** to securely upload your file to your own Google Drive for further editing.

## 🔧 Permissions
This extension requests the following permissions:

- **Storage**: Used to temporarily store the Excel file data while it’s being viewed locally in your browser.  
- **Identity**: Required to obtain an OAuth token when you click **"Edit in Google Sheets"**, so the file can be uploaded to your own Google Drive.  
- **Host Permissions**: Specifically for `docs.google.com` and `www.googleapis.com`, enabling file uploads to Google Drive and opening spreadsheets in Google Sheets.

## 📝 License
This project is licensed under the **MIT License**.  
See the [LICENSE.txt](LICENSE.txt) file for details.

## 📌 Third-Party Attributions
This extension uses:
- **SheetJS (xlsx.full.min.js)** – A JavaScript library for parsing and displaying Excel files.  
  Licensed under the **Apache License 2.0**.  
  Repository: [https://github.com/SheetJS/sheetjs](https://github.com/SheetJS/sheetjs)
- **Icons from Flaticon**:
  - [Zoom out icons](https://www.flaticon.com/free-icons/zoom-out) by **Freepik**  
  - [Logos icons](https://www.flaticon.com/free-icons/logos) by **pocike**
