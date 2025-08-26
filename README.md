# File Read & Write Challenge 🖋️

This is a Python program that:
- Reads a file specified by the user
- Handles errors if the file does not exist or cannot be read
- Modifies the file content (by default, converts it to uppercase)
- Writes the modified content to a new file

## Features
- **Error Handling**: Gracefully manages `FileNotFoundError`, `PermissionError`, and other unexpected errors.
- **File Processing**: Reads text from a file and applies a simple transformation.
- **Output File**: Saves the modified text to a new file with the prefix `modified_`.

## How It Works
1. The user is prompted to enter a filename.
2. The program attempts to open and read the file.
3. If the file is successfully read, the content is transformed to uppercase.
4. The transformed content is written to a new file.
5. The program confirms the location of the saved file.

## Example
**Input file (`example.txt`):**
