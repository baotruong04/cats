# Computer Aided Typing Software

This project is a fun and educational typing test tool. It features both a command-line interface (CLI) and a graphical user interface (GUI), with support for single-player and multiplayer typing tests. The tool evaluates typing speed, accuracy, and can be extended with additional features.

## Project Structure

### Core Logic
- **cats.py**: Implements the main typing test logic, including speed and accuracy calculation, autocorrection, and progress tracking.
- **utils.py**: Provides utility functions for file handling, string manipulation, and other helper operations.
- **ucb.py**: Contains utility functions specific to CS 61A projects.

### Data Files
- **data/sample_paragraphs.txt**: Paragraphs scraped from Wikipedia used for typing tests.
- **data/common_words.txt**: Common English words ordered by frequency.
- **data/words.txt**: An extended list of English words ordered by frequency.
- **data/final_diff_words.txt**: A large list of English words for advanced features or extensions.
- **data/testcases.out**: Test cases for the optional Final Diff extension.

### GUI Components
- **cats_gui.py**: Hosts a web server for the GUI version of the typing test.
- **gui_files/**: Static files and resources required for the GUI.
- **favicons/**: Icons used in the GUI.
- **images/**: Image resources for the GUI.

### Multiplayer Support
- **multiplayer/**: Code and assets for enabling multiplayer typing competitions.

### Testing
- **ok**, **cats.ok**, **tests/**: Files used for testing and verifying project correctness.

## Getting Started

### Requirements
- Python 3.x
- Flask (for GUI)

### Running the Typing Test
#### CLI Version
```bash
python3 cats.py
