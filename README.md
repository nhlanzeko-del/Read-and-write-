# Python File Operations Lab 🖋️🧪

This module teaches essential file handling and error management in Python through practical challenges.

## Lab Challenges

### 1. File Read & Write Challenge 🖋️
**Objective**: Create a program that:
- Reads content from a source file
- Modifies the content (e.g., converts to uppercase)
- Writes the modified version to a new file

### 2. Error Handling Lab 🧪
**Objective**: Build a robust program that:
- Prompts the user for a filename
- Gracefully handles:
  - FileNotFoundError (missing files)
  - PermissionError (read restrictions)
  - Other I/O exceptions

## Learning Outcomes 🎉
By completing this module, you'll be able to:
✅ Read and write files efficiently  
✅ Implement professional error handling  
✅ Process file content programmatically  
✅ Build resilient file operations  

## Example Solutions

### File Transformer
```python
# Read, modify, and write files
with open('input.txt', 'r') as source:
    content = source.read().upper()

with open('output.txt', 'w') as destination:
    destination.write(content)
