# smidig-prosjekt
# Memory Forensics GUI using Volatility 3
This project is a GUI application designed to interface with Volatility 3, a memory forensics framework. The application provides an easy-to-use interface for performing memory forensics analysis, making it accessible to both beginners and experienced users. The application allows users to load memory dumps, run various analysis plugins, and view results in a user-friendly manner.


# Features
* User-Friendly Interface: Simplifies interaction with Volatility 3 through a graphical user interface
* Plugin Integration: Supports a wide range of Volatility 3 plugins for comprehensive memory forensics analysis
* Result Visualization: Displays analysis results in an organized and readable format.
* Multi-Platform Support: Compatible with major operating systems including Windows, macOS, and Linux

# Requirements
* Python 3.7 or higher
* Required Python libraries: `tkinter`, `customtkinter`, `volatility3`, `reportlab`
* memory dumpfile

# Installation 
1. Download the repository from this GIThub link repository as ZIP:
    * https://github.com/alez001/smidig-prosjekt.git 
2. extract the directory to where you wish to store the directory
3. Open command Prompt as Adminstrator
4. Navigate to where you downloaded/extracted the GUI directory
   * `cd X:\path\to\GUI-directory`
5. install the required libraries from requirements.txt: 
   * `pip install -r requirements.txt`
6. run the main.py script from that directory.
   * `python main.py`



# Usage
1. Launch the application from command prompt in adminstrator mode:
    *  `python main.py`
2. Load a memory dump: Use the GUI to select and load a memory dump file for analysis.
3. Select a plugin: Choose from the list of available Volatility 3 plugins to run on the loaded memory dump.
4. Run the analysis: Execute the selected plugin and view the results directly within the application.
5. For further assistance with usage of the program, launch python main.py and click on the help button. 

# Acknowledgments
* Thanks to the developers of `Volatility 3` for providing the tools that made this project possible.
* Thanks to the contributors of `tkinter`, `customtkinter`, `volatility3`, and `reportlab` for their invaluable libraries.




