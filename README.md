# Keylogger Program

This is a basic keylogger implemented in C that captures keystrokes and logs them into a file called `keylog.txt`. It detects both regular characters and special keys such as SHIFT, CTRL, BACKSPACE, and others.

## Features

- Logs alphanumeric and special character keys.
- Recognizes common special keys such as:
  - Space
  - Enter
  - Shift
  - Tab
  - Backspace
  - Escape
  - Control (CTRL)
- Stores logged keystrokes in a file for later review.

## Prerequisites

- **Operating System**: This program is built to run on Windows, as it uses the `windows.h` library.
- **C Compiler**: You need a C compiler (like `gcc` or Microsoft Visual Studio) to compile the program.

## How to Compile

### Using GCC (MinGW)
1. Install `MinGW` from the official website.
2. Open the command prompt and navigate to the folder containing the program file.
3. Compile the program using the appropriate command.

## How to Run

Once the program is compiled, run the executable from the terminal or command prompt.

The program will begin recording keystrokes and writing them to `keylog.txt` in the same directory. The file will be updated in real-time, logging each key press.

### Stopping the Program
To stop the program, you will need to terminate it manually (e.g., from the Task Manager or by closing the terminal window).

## Logged Output

The program logs both regular characters and special keys, such as:

- **Regular characters**: 
  - Letters (a, b, c, ...)
  - Numbers (1, 2, 3, ...)
  - Symbols (@, #, $, ...)
  
- **Special keys**:
  - [SHIFT], [CTRL], [ESCAPE], [BACKSPACE], [TAB], etc.
  
## Example Output in `keylog.txt`

If you type `Hello World!` and press Enter, the output in `keylog.txt` will look like:

- [SHIFT]Helloworld[SPACE]World![ENTER]

Each special key press is logged with its respective label, while regular characters are logged as typed.

## Security Consideration

This program is for educational purposes only. Be aware that running keyloggers without user consent is illegal in many jurisdictions. Always get permission before using or distributing this software.

## License

This project is provided under the MIT License.
