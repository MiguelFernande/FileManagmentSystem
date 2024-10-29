# File Management System with LFSR Encryption

This repository contains a Java-based **File Management System** developed as a class project for an **Operating Systems course**. The system includes standard file management functions as well as a unique feature: **LFSR-based encryption** for text files. This project was managed and primarily developed by me, with additional functions and bug fixes contributed by teammates.

## Features

- **File Management**: Basic file operations like creating, deleting, and managing files.
- **LFSR Encryption**: Uses a Linear Feedback Shift Register (LFSR) encryption mechanism to secure text files.
- **Cross-Platform**: Built for **Windows**.

## Project Structure

- **`encryptor.java`**: Contains the encryption and decryption functionalities based on LFSR.
- **`FileManagementSystem.java`**: Implements the file management operations and program flow for handling files.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)** installed (version 8 or higher recommended).
- **Windows Operating System** (Optimized for Windows but may work with minor adjustments on other OSs).

### Running the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/FileManagementSystem.git
   cd FileManagementSystem
   ```

2. **Compile the Java Files**:
   ```bash
   javac FileManagementSystem.java encryptor.java
   ```

3. **Run the Main Program**:
   ```bash
   java FileManagementSystem
   ```

   This will launch the File Management System, allowing you to perform file operations and encrypt text files using the LFSR encryption function.

## Credits

- **Project Management and Code Base**: Majority developed by me.
- **Additional Contributions**: Teammates provided function implementations and bug fixes.
