# file-management-automation
A Python automation script that automatically organizes files into categorized folders based on their file extensions using os and shutil libraries.


  # Python Automatic File Sorter

## Overview

This project is a Python automation script that organizes files into separate folders based on their file types. It automatically creates folders (if they do not already exist) and moves files into their respective directories.

The project uses Python's built-in `os` and `shutil` libraries for file management and automation.

---

## Features

* Automatically creates folders for different file categories
* Sorts CSV files into a dedicated folder
* Sorts image files (`.png`, `.jpg`) into a dedicated folder
* Sorts Word documents (`.docx`) into a dedicated folder
* Prevents duplicate file movement
* Helps keep directories organized and clutter-free

---

## Technologies Used

* Python
* os module
* shutil module

---

## Supported File Types

| File Type | Destination Folder |
| --------- | ------------------ |
| .csv      | csv files          |
| .png      | image files        |
| .jpg      | image files        |
| .docx     | docx file          |

---

## How It Works

1. The script scans a target directory.
2. It checks whether the required folders exist.
3. If a folder does not exist, it creates it automatically.
4. Files are identified by their extensions.
5. Files are moved to their corresponding folders.

---

## Example

Before:

Downloads/
├── sales_data.csv
├── image1.jpg
├── profile.png
└── report.docx

After:

Downloads/
├── csv files/
│   └── sales_data.csv
├── image files/
│   ├── image1.jpg
│   └── profile.png
└── docx file/
└── report.docx

---

## Learning Outcomes

This project helped me practice:

* Python file handling
* Directory management
* Automation scripting
* Loops and conditional statements
* Working with the os module
* Working with the shutil module

---

## Future Improvements

* Support additional file formats
* Add logging functionality
* Create a graphical user interface (GUI)
* Allow users to define custom file categories
* Improve scalability using dictionaries and functions

---

## Author

Akash Kumar
