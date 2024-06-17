[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237596&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

  - Access the official <a href="https://code.visualstudio.com/Download">Visual Studio Code Download</a> website.
  - Select the version that’s compatible with Windows 11 the download should start automatically.
  - After the download completes open the installer file.
  - Locate VSCodeSetup.exe file in your Downloads folder.
  - Accept the terms and conditions, license agreement by checking the box and clicking next.
  - Select the folder where you want Visual Studio Code to be installed then click next.
  - Click "Install" to begin the installation process.
  - After the installation is completecheck the box to launch Visual Studio Code click Finish.
  - You can also launch it later from the Start Menu or desktop icon if you created one.
  
  Prerequisites:

  1.6 GHz or faster processor
  1 GB of RAM

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   
- From the cammand palette the Open Settings (JSON) command will let you directly edit the settings JSON file.
- Turn on autosave
- The Open Settings (UI) command will open a user-friendly UI to edit the settings JSON file indirectly.
- Use a formatter such as <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Prettier - Code formatter</a>
 this saves time by automatically formatting pasted code
- <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner">Live Server </a> it creates a local live server for web development
- <a href="https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens">GitLens Extension</a> better manages Git inside VS Code
- <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Python Extension for VS Code</a> as it assists with code debugging and formatting

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

- Activity Bar: allows you to switch between views: explorer, search, version control, debug and extensions.
- Side Bar: contains the active view.
- Editor: this is where you edit files and preview markdown files. You can arrange multiple open files side-by-side.
- Panel: displays different panels: integrated terminal, output panels for debug information, errors and warnings.
- Status bar is at the bottom of the window. It provides information about the current project and files, such as line number, encoding, language, and errors/warnings.
  
4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
  
The Command Palette is a handy feature allows you to quickly search for and execute various commands within the editor without having to navigate through menus or remember specific shortcuts, serves as a central hub for all your actions in VS Code making it a powerful tool for boosting your productivity. 

On the menu options go to view the command palette or pres Ctrl + Shift + P on your keyboard the Command Palette should appear on your screen.

Open File: Allows you to quickly open a file in the editor.

Search Symbols: Helps you find specific symbols within your code.

Run Task: Executes a predefined task, such as building or debugging your project.

Manage Extensions: Allows you to install, update, or remove extensions in VS Code.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 
Extensions enhances productivity and customizing the development environment sch as: registering and executing commands, streamlining coding workflow, navigating and mananging codebase, automating repetitive tasks.

Click on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command Ctrl+Shift+.

Browse the list of the most popular VS Code extensions on the VS Code Marketplace.

Find the extension you want to install and select Download.
After download completes you'll see a notification at the bottom of the Manage Extensions dialog box : The extension is scheduled for install.

The Manage Extensions dialog box is the tool you use to find, install, and manage extensions. 

To open the Manage Extensions dialog choose Extensions then Manage Extensions Or type Extensions in the search box and select Manage Extensions.

<a href="https://html-validate.org/">HTML Validate</a>: Check HTML code for errors and ensure proper syntax.

Web Developer Checklist: Get a checklist of best practices for web development.

ColorZilla: A color picker and gradient generator.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

From the menu use the Terminal then New Terminal or View then Terminal menu commands.

Once the terminal is open, you can type your commands just like you would in a regular terminal window.

Convenience: No need to switch apps or windows to access the terminal.

Customization: Fully customizable terminal settings like shell, fonts, scrollback.

Support for multiple terminal instances: Makes it easier to manage different development tasks simultaneously


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
  
Use the New File and the New Folder buttons at the top of the Explorer View. The New File button is shaped like a piece of paper with a plus sign and the New Folder button is shaped like a folder with a plus sign
Clicking File.

Selecting Open and then selecting the folder you want to open or by running this command in your terminal: code <folder path>using the File then Open folder menu and selecting a folder.

Hold Ctrl and press Tab to view a list of all files open in an editor group. To open one of these files, use Tab again to pick the file you want to navigate to, then release Ctrl to open it. 

Alternatively, you can use Ctrl+Alt+- and Ctrl+Shift+- to navigate between files and edit locations.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
  
To open the Settings editor, navigate to File then Preferences then Settings.

Alternately, open the Settings editor from the Command Palette Ctrl+Shift+P with Preferences: Open Settings or use the keyboard shortcut Ctrl+,

Select the File > Preferences > Theme > Color Theme menu item, or use the Preferences: Color Theme command (Ctrl+K Ctrl+T) to display the Color Theme picker.

Use the Up and Down keys to navigate through the list and preview the colors of the theme.

Select the theme you want and press Enter.

For example, you can change the default dark theme to a light theme or a theme that matches your system settings.
On the menu bar, select Tools > Options.

On the menu bar, select Tools > Options.

In the options list, select Environment > Fonts and Colors.

Click file then Preferences then Keyboard shortcuts.
Use the tab that opens up to edit and find available key bindings and assign them.
Open the keybindings.json file using the button in the tab-bar.
Add your settings to it from VSCode keybinding setting file.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
  
Set Breakpoints: Click on the left margin next to the line numbers where you want to pause execution. 

Start Debugging: Click on the Run button in the Debug view or press F5 to start debugging. Step Through Code: Use the toolbar to step over F10, step into F11, or continue F5 execution.

Breakpointscan be toggled by clicking on the editor margin
Data inspection
Debug Console 

10.   Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Users can integrate Git with VS Code for version control by:
Adding Git to a project folder in VS Code.
Initialize a new Git repository for an existing project folder.
Commit changes to your repository.
Push your changes to a remote repository (e.g., GitHub).

The process of initializing a repository
Navigate to your project folder.
Open the integrated terminal by clicking on View -> Terminal or using the shortcut Ctrl+`.
In the terminal, run the following command to initialize a Git repository: $ git init

Open the Source Control view in Visual Studio Code by clicking on the Git icon in the sidebar or using the shortcut Ctrl+Shift+G.

You will see a list of your modified files. Click on the "+" icon next to the files you want to stage for the commit. 

Alternatively, you can stage all changes by clicking on the "+" icon at the top of the Source Control view.

Enter a commit message in the input field at the top of the Source Control view, describing the changes you made.

Click on the checkmark icon to commit the changes.

This command creates a hidden .git folder in your project, which contains all the necessary files for Git to track changes.

Push the commit to Github click on the three dots ... and click on “Push”.

List of online references

https://code.visualstudio.com/Docs/setup/setup-overview
https://code.visualstudio.com/docs/getstarted/userinterface
https://code.visualstudio.com/docs/introvideos/debugging
https://www.jcchouinard.com/create-your-first-github-project-in-vscode/
https://dev.to/pratik_kale/using-git-with-visual-studio-code-47oi


 Submission Guidelines
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

