# folderexploder

# Folder Exploder

**Folder Exploder** is a simple drag-and-drop desktop app that exports all code from a folder (and subfolders) into a single `.txt` file for easy LLM input.

## Features

- Drag and drop one or more folders
- Recursively scans all code files
- Skips binaries and images
- Outputs a single file: `code_dump.txt`
- Cross-platform (Windows/macOS/Linux)

## How to Use

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Run the app:
    ```bash
    python src/folder_exploder.py
    ```

3. Drag folders into the window. `code_dump.txt` will be generated in the current directory.

## Build to EXE (Optional)

Install [PyInstaller](https://pyinstaller.org/):
```bash
pip install pyinstaller
pyinstaller --noconsole --onefile src/folder_exploder.py

