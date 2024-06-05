## File-manager

### Description:
File-manager is a versatile file management tool designed to streamline the organization, sorting, and renaming of files on your local system. With an intuitive graphical user interface (GUI), users can easily select a folder, choose sorting criteria, rename files, organize files by type, and even undo recent operations. This tool simplifies file management tasks, enhancing productivity and efficiency.

### Installation:
1. **Clone the repository:**
git clone https://github.com/yourusername/File-manager.git

2. **Navigate to the project directory:**
cd File-manager

3. **Install the required dependencies:**
pip install -r requirements.txt

4. **Run the application:**
python file_management_tool.py

### Documentation:

1. **User Guide:**
- Start by selecting a folder using the "Select Folder" button.
- Choose sorting criteria (e.g., name, date, type, size) using the radio buttons in the "Sort Options" section.
- Optionally, enable the "Rename all files" checkbox in the "Rename Options" section to rename files with a custom pattern.
- Optionally, enable the "Organize files by type" checkbox in the "Organize Options" section to group files into folders based on their types.
- Click the "Run" button to execute the selected operations.
- To undo the last operation, click the "Undo" button.

2. **Developer Guide:**
- The `file_management.py` module contains functions for file operations such as listing files, sorting files, renaming files, organizing files by type, and undoing operations.
- The `file_management_tool.py` script initializes the GUI application using Tkinter and integrates the file management functions.
- To extend or modify the functionality, developers can edit the existing functions in `file_management.py` or add new functions as needed.
- Ensure to maintain proper error handling and documentation for any changes made to the codebase.

3. **Contributing:**
- Contributions are welcome! Fork the repository, make your changes, and submit a pull request with a clear description of the proposed changes.
- For major changes, please open an issue first to discuss the potential impact and ensure compatibility with the project's goals.

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
