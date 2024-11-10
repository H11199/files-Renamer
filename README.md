# 📁 File Renamer Console Application

## 📝 Overview
The **File Renamer** is a simple and efficient console-based tool designed to help users rename all files within a specified folder sequentially. This tool is perfect for renaming files with a consistent base name followed by numbers (e.g., `V1`, `V2`, `V3`, etc.) while preserving their original extensions.

## ✨ Key Features
- 🔄 Renames all files in the specified folder.
- 🔢 Adds sequential numbering starting from 1.
- 📄 Retains original file extensions.
- ⚡ Quick and user-friendly operation for batch file renaming.

## 🌟 Benefits
- **Time-saving**: Quickly rename large batches of files without manual effort.
- **Consistency**: Ensures uniform file naming for better file organization.
- **Ease of Use**: Simple to use, even for non-technical users.

## 🚀 How to Use
1. **Download the `FileRenamer.exe`** and save it to a convenient location on your computer.
2. **Open Command Prompt**:
   - Press `Win + R`, type `cmd`, and press `Enter`.
3. **Navigate to the directory** containing `FileRenamer.exe`:
   ```bash
   cd path\to\your\directory
4. **Run the application**:
   ```bash
   FileRenamer.exe
   ```

5. **Follow the prompts**:
   - Enter the full path of the folder containing the files you wish to rename.
   - Enter the desired base name for the files (e.g., `V`).

6. **Confirm the renaming** process. The tool will rename all files in the folder to the format `<base_name>1`, `<base_name>2`, etc., while keeping their original extensions.

### 💡 Example
**Input Folder Contents**:
```
file1.jpg
document.pdf
image.png
```

**Base Name Entered**: `V`

**Output Folder Contents**:
```
V1.jpg
V2.pdf
V3.png
```

## ⚠️ Important Notes
- Ensure you back up your files before running the tool, as the renaming process cannot be undone.
- The tool only renames files in the specified folder, not subfolders.

## 🖥️ System Requirements
- **Operating System**: Windows OS
- **Executable**: Python-based `.exe` compatible with most Windows versions

## 🛠️ Technical Details
The tool is built using Python and compiled into an executable for easy distribution and use.
