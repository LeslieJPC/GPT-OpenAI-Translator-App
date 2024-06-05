## Images of File Explorer and UI - accessible for visual deficiancy
![image](https://github.com/LeslieJPC/Translator-App/assets/139573788/87a3ece8-ee70-4544-be22-8e1e44bc8ddb)
![image](https://github.com/LeslieJPC/Translator-App/assets/139573788/16e5837d-0d63-443d-8bc2-3722c2ccb921)

# Translator App

## Overview
The **Translator App** is a GUI application built using Tkinter and OpenAI's GPT-3.5 API. The app allows users to translate text between multiple languages, detect the language of user inputs, convert speech to text, and read out translations using text-to-speech.

## Features
- Language detection for user inputs.
- Translation between multiple languages.
- Text-to-speech functionality for translated text.
- Speech-to-text conversion using the microphone.
- Clear and reverse translation functionalities.
- User-friendly interface with dropdowns and text fields.

## Supported Languages
- English
- Spanish
- French
- German
- Chinese (Simplified)
- Chinese (Traditional)
- Japanese
- Korean
- Italian
- Portuguese
- Dutch
- Russian
- Arabic
- Turkish
- Hindi
- Swedish
- Danish
- Norwegian
- Finnish
- Greek
- Polish
- Hungarian
- Czech
- Romanian
- Hebrew
- Thai
- Vietnamese
- Indonesian
- Malay

## Getting Started

### Prerequisites
- Python 3.6 or higher
- OpenAI API Key
- Tkinter
- pyttsx3
- speech_recognition
- datetime

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/TranslatorApp.git
    ```
2. Install the required Python packages:
    ```sh
    pip install openai pyttsx3 speechrecognition
    ```

3. Place your OpenAI API key in a file named `key.py` with the following content:
    ```python
    API_KEY = "your_openai_api_key"
    ```

4. Run the application:
    ```sh
    python main.py
    ```

### Usage
1. Open the application.
2. Select the desired translation language from the dropdown menu.
3. Enter the text you want to translate in the "What would you like translated?" field.
4. Click the "Translate" button to get the translation.
5. The translation will appear in the "translation:" field.
6. Use the "Reverse Translation" button to translate back to the original language.
7. Use the "Read Translation" button to read out the translated text.
8. Use the "Speech Input" button to convert speech to text and display it in the input field.
9. Use the "Clear" button to clear all fields.

## Code Structure
The application is built using Tkinter for the GUI, OpenAI's GPT-3.5 for language detection and translation, pyttsx3 for text-to-speech, and speech_recognition for speech-to-text.

### Main Components
- `language_detection(inputs, detected_language)`: Detects the language of user inputs.
- `get_translation(inputs, language2, detected_language)`: Translates the user input to the selected language.
- `translate_text()`: Translates the text entered by the user and displays the translation.
- `reverse_translation()`: Reverses the translation to the original language.
- `read_translation()`: Reads out the translated text using text-to-speech.
- `speech_to_text()`: Converts speech to text using the microphone.
- `get_speech_input()`: Gets speech input and displays it in the input field.
- `clear_all_textboxes_and_entry()`, `clear_all_textboxes()`, `clear_entry_text()`: Clears the text fields and dropdowns.
- `get_current_time()`: Returns the current time for display in the GUI.

### GUI Components
- Tkinter `Canvas`: Used to create the GUI layout.
- `Entry`, `Text`: Text fields for user input and output.
- `Button`: Buttons for various functionalities (translate, clear, reverse, etc.).
- `Combobox`: Dropdown for selecting translation languages.
- `PhotoImage`: Images for buttons and backgrounds.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author
- Team: Leslie, Brandon, Oliver

Feel free to reach out for any questions or contributions. Happy coding!

## IDE Recommendations

Here are some IDEs that are well-suited for this task:

### PyCharm:

PyCharm is a popular Python IDE with robust features for developing Python applications. It has excellent support for managing virtual environments and installing dependencies.
How to run the code:
Open PyCharm and create a new project.
Copy the code into a new Python file (e.g., main.py).
Ensure you have a virtual environment set up and install the required packages using pip install pyttsx3 speechrecognition.
Place your frame0 directory with the image assets in the project directory.
Run the script using the run button or Shift + F10.

### Visual Studio Code (VS Code):

VS Code is a versatile and lightweight code editor with excellent Python support through extensions.
How to run the code:
Open VS Code and create a new workspace.
Copy the code into a new Python file (e.g., main.py).
Open the terminal in VS Code and create a virtual environment if you haven't already (python -m venv venv).
Activate the virtual environment and install the required packages (pip install pyttsx3 speechrecognition).
Ensure the frame0 directory with the image assets is in the workspace directory.
Run the script by clicking the run button or using the integrated terminal (python main.py).

### Thonny:

Thonny
Thonny is a simple and beginner-friendly Python IDE that is great for small projects and learning Python.
How to run the code:
Open Thonny and create a new Python file.
Copy the code into the new file.
Use Thonny's package manager to install the required packages (Tools > Manage packages and search for pyttsx3 and speechrecognition).
Ensure the frame0 directory with the image assets is in the same directory as your script.
Run the script by clicking the run button or pressing F5.

### IDLE:

IDLE is Python's built-in IDE, which is simple and lightweight.
How to run the code:
Open IDLE and create a new file.
Copy the code into the new file.
Save the file in a directory that includes the frame0 folder with the image assets.
Use pip to install the required packages in your Python environment (pip install pyttsx3 speechrecognition).
Run the script by pressing F5.

## Helpful Hint

Make sure that your Python environment includes the necessary packages (pyttsx3, speechrecognition) and that the frame0 directory with the required images (all .png files in this repo) is correctly placed in the project directory. You will need to use your own API Key for full functionality also, BE MINDFUL OF YOUR FILE PATH. This setup will help you run the corrected code smoothly in any of the mentioned IDEs.
