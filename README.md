# File Management System with LFSR Encryption

This is a Java-based **Cross-Platform File Management System** that provides basic file operations and **LFSR encryption** for text files. It operates through a console menu and gives immediate feedback for each command.

## Features

- **Basic File Operations**: Create, read, update, delete, and copy files.
- **Directory Management**: Create, delete, navigate, and check directories.
- **Encryption**: Encrypt and decrypt text files using LFSR encryption.
- **Cross-Platform**: Built for **Windows** but also works on **macOS**.

## Project Structure

- **`encryptor.java`**: Contains the encryption and decryption functionalities based on LFSR.
- **`FileManagementSystem.java`**: Implements the file management operations and program flow for handling files.

## How to Run

1. **Download the files** and place them in a single directory.
2. **Open a terminal** in the directory containing the downloaded files.
3. **Compile the Java files**:
   ```bash
   javac FileManagementSystem.java encryptor.java
   ```
4. **Run the main program**:
   ```bash
   java FileManagementSystem
   ```

This will open an interactive menu in the terminal.

## Usage

After launching, you’ll see a menu with numbered options for different file operations. Choose an action by entering the corresponding number:

```
File Management System
 1. Create a file
 2. Read a file
 3. Update a file
 4. Delete a file
 5. Create a directory
 6. Delete a directory
 7. Check directory
 8. Search for files path
 9. File Details
10. Change Permissions
11. Copy File
12. Paste File
13. Encrypt/Decrypt File
14. Change Directory
15. Go to Parent Directory
16. Exit
```

### Example Usage

- **File Operations**: For actions like `Read a file` or `Encrypt/Decrypt File`, simply enter the file name (e.g., `file.txt`) if the file is in the current directory.
- **Directory Operations**: To change directories, use `Change Directory` and specify the path relative to the current directory.

## Limitations

- **Direct Visibility**: The system can only act on files and directories it can directly see. This means:
  - If a file is in the current directory, you can simply provide its name (e.g., `file.txt`).
  - If the file is in another directory, navigate there first using a combination of the `Change Directory` and the `Go to Parent Directory` options.
- **Cross-Platform Input**: For cross-platform compatibility, inputs are limited to **file names only** (e.g., `file.txt`). Full file paths may not work consistently across operating systems.
- **Compatibility**: Works on **Windows** and **macOS**. Ensure paths are correctly formatted for the OS in use.
- **Encryption Scope**: Only applies to text files.
