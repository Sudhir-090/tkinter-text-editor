# Text Saver 3000
 
A simple desktop notepad built with Python and Tkinter. Type your text, click **save it**, give the file a name, and it is saved as a `.txt` file. A short beep confirms the save.
 
## Features
 
- Large text area to write or paste your text
- **save it** button: enter a file name and save your text as a `.txt` file
- **cancel** button to go back to the editor without saving
- **clear all** button to wipe the text area
- Beep sound when a file is saved
- Light blue window with a custom icon
## Requirements
 
- **Windows** (the app uses the `winsound` module, which is Windows-only)
- Python 3.8 or newer
- [`ttkthemes`](https://pypi.org/project/ttkthemes/)
- `tkinter` (included with the standard Windows Python installer)
- The icon file `Text.ico` must be in the same folder as the program
## Installation
 
```bash
git clone https://github.com/Sudhir-090/tkinter-text-editor.git
cd tkinter-text-editor
pip install ttkthemes
```
 
## Usage
 
Run the program from inside its folder so it can find `Text.ico`:
 
```bash
python <file-name>.py
```
 
1. Type or paste your text into the big text box.
2. Click **save it** (top right).
3. Enter a name for your file (no need to type `.txt`) and click **save**.
4. You will hear a beep, and the file is created.
5. Click **cancel** if you change your mind, or **clear all** to empty the text box.
> **Note:** Files are saved in the folder you ran the program from. If you save with a name that already exists, the old file is overwritten.
 
## Project structure
 
```
.
├── <file-name>.py   # the app
├── Text.ico         # window icon
└── README.md
```
 
## Built with
 
- [Tkinter](https://docs.python.org/3/library/tkinter.html), the GUI
- [winsound](https://docs.python.org/3/library/winsound.html), the save beep
## Ideas for the future
 
- Open and edit existing text files
- Choose the save location with a file dialog
- Work on macOS and Linux (replace the beep)
- Word count and font size options
## License
 
Free to use and modify. Add a license of your choice (for example MIT) if you want others to reuse it.
