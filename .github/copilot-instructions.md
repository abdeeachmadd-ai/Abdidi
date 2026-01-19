# Copilot Instructions for Abdidi

## Project Overview
**Abdidi** is a simple educational Python project that determines whether a given integer is odd (ganjil) or even (genap). The project is written in Indonesian and serves as a beginner-level program demonstrating basic Python concepts.

## Project Structure
- `ganjilgenap.py` - Main program file that contains the core logic
- `README.md` - Project documentation
- `.github/` - GitHub configuration directory

## Core Functionality
The program (`ganjilgenap.py`) follows this simple workflow:
1. Prints a title in Indonesian
2. Prompts user to input a number
3. Uses modulo operator (`%`) to check if the number is divisible by 2
4. Outputs whether the number is "genap" (even) or "ganjil" (odd)
5. Prints a completion message

## Code Patterns & Conventions

### Language & Localization
- Comments and user-facing output are primarily in Indonesian
- Examples: "Masukkan bilangan" (Input a number), "Bilangan genap" (Even number)
- Maintain Indonesian terminology when extending the codebase

### Input/Output Pattern
- Use `input()` for user prompts with Indonesian text
- Use `print()` for all output messages
- Convert input to `int()` explicitly for numeric operations

### Mathematical Logic
- Odd/even detection: `number % 2 == 0` evaluates to True for even, False for odd
- Keep condition simple and readable

## Development Notes

### No Complex Dependencies
This project has no external package requirements—only Python standard library.

### Testing Approach
Manual testing is appropriate given the program's simplicity:
- Test with even numbers: 2, 4, 100
- Test with odd numbers: 1, 3, 99
- Test with edge cases: 0 (even)

### Future Enhancement Ideas
- Input validation (handle non-integer inputs gracefully)
- Support for negative numbers
- Optional menu system for repeated checks without restarting

## Common Tasks

### Running the Program
```bash
python ganjilgenap.py
```

### Extending Functionality
When adding features:
1. Keep the input/output pattern consistent
2. Maintain Indonesian labels for user messages
3. Test manually with various numeric inputs
4. Update README.md if new functionality changes the user workflow
