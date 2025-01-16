# CSV Merger Tool

The **CSV Merger Tool** is a web-based utility that allows users to easily merge multiple CSV files into a single CSV file. This tool is especially useful for users who need to consolidate data from multiple CSV files into one, saving time and effort. It also provides an option to discard redundant headers when merging.

## Features

- **Drag and Drop Support:** Easily upload CSV files by dragging and dropping them into the tool or selecting them manually.
- **Header Management:** Option to discard redundant headers (except for the first file) to avoid duplication in the merged data.
- **CSV File Parsing:** The tool automatically parses the CSV files and prepares them for merging.
- **Download Merged Data:** After merging the files, download the combined data as a new CSV file.
- **Multiple File Support:** Merge multiple CSV files at once.

## How to Use

1. **Upload Files:**
   - You can either drag and drop the CSV files into the designated area or click to select files from your device.
   - The tool supports multiple file uploads at once.

2. **Choose to Discard Headers:**
   - If you want to discard redundant headers from all files except the first one, check the "Discard headers" checkbox.
   
3. **Merge Files:**
   - Once the files are uploaded, click on the "Merge CSV Files" button. The tool will process the files and merge them into a single dataset.

4. **Download Merged Data:**
   - After the files have been merged, you will be able to download the merged CSV file by clicking the "Download Merged Data" button.

## Installation

This tool is a web-based application, so there is no need for installation. Simply open the HTML file in your browser to start using the tool.

### Requirements

- A modern web browser (Chrome, Firefox, Safari, etc.)
- Internet connection (for accessing external libraries like PapaParse and FileSaver.js)

## Dependencies

- **[PapaParse](https://www.papaparse.com/):** A JavaScript library used for parsing CSV files.
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/):** A library for saving files on the client-side, used to download the merged CSV file.

Both libraries are included via CDN links in the HTML file.

## Contributing

Contributions to improve the tool are welcome! If you find any bugs or have suggestions for new features, feel free to submit an issue or pull request.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Feel free to share this tool with others and use it for your data merging needs!
