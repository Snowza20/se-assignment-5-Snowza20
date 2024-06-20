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
  
- Click on the "Download for Windows" button your operating system will be detected and the downloading will then start.
  
- After the download is complete to your Downloads folder the file should be have VSCodeSetup-x64-{version}.exe naming.

- Now, double click on the installer file to start the installation process.
Click yes to allow the installer to make changes to your device.

- When the VS Code setup wizard opens, click next to continues

- Accept the terms and conditions, license agreement by checking the box and clicking next.

- Choose where you want to install VS Code or leave it as the default, continue by clicking next.

- You can add to you desktop, click install to start the installation process.

- When the installation is complete then click finish.

- Launch VS Code from desktop file created or go to windows start menu and search Visual Studio Code.

Prerequisites:

- Your windows 11 should meets the minimum requirements specified by Visual Studio Code.

- A web browser

- A stable internet connection to download

- Have enough space on disk to download

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   
- You can choose a theme you like by clicking on file located in the top menu – preferences – colour theme.

- You can choose your preferred indentation by clicking on file located in the top menu – Preferences – Settings - Text Editor - Tabs.
  
- Install extensions you will work with by clicking View - Extensions or Ctrl+Shift+X  

- Use a formatter such as <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Prettier - Code formatter</a>
 this saves time by automatically formatting pasted code.

- <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner">Live Server </a> it creates a local live server for web development.
 
- <a href="https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens">GitLens Extension</a> better manages Git inside VS Code.
  
- <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Python Extension for VS Code</a> as it assists with code debugging and formatting.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

- Activity Bar: allows you to switch between views: explorer, search, version control, debug and extensions.
  
- Side Bar: contains the active view, integrates with version control systems like Git
  
- Editor: this is where you edit files and preview markdown files. You can arrange multiple open files side-by-side.
  
- Panel: displays different panels: integrated terminal, output panels for debug information, errors and warnings.
  
- Status bar is at the bottom of the window. It provides information about the current project and files, such as line number, encoding, language, and errors/warnings.
  
4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
  
The Command Palette is a handy feature that allows you to quickly search for and execute various commands within the editor without having to navigate through menus or remember specific shortcuts, serves as a central hub for all your actions in VS Code making it a powerful tool for boosting your productivity. 

- Click on View in the menu bar at the top of the VS Code window.
  
- Select Command Palette from the dropdown menu.
  
- You also use your keyboard press Ctrl+Shift+P
  
Examples of common tasks that can be performed using the Command Palette:
  
- To quickly open a file in your workspace by typing "Open File" and selecting the the one you want from the list.
  
- To open recent files type "Open Recent" and selecting from the list of recently opened files.

- To Save the current file type "Save".
  
- To close the current file you are working on type "Close File".

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 
Extensions enhances productivity and customizing the development environment such as registering, executing commands, streamlining coding workflow, navigating and mananging codebase and automating repetitive tasks.

- Open VS Code.

- Click on the Extensions icon in the Activity Bar on the side or use Ctrl+Shift+X

- You can use Extensions view to browse and search for extensions by 
opening the Command Palette Ctrl+Shift+P 

- Type Extensions: Install Extensions.

- Search for extensions by typing keywords or browse through the results.
  
Installing Extensions:

- Once you find the extension you want, click on the "Install" button next to the extension name.
  
- This will be automatically be downloaded and installed.
  
Managing Extensions:

- In the Extensions view (Ctrl+Shift+X), you can manage installed extensions.
  
- Click on the gear icon next to an extension to access options such as enabling, disabling, updating, or uninstalling.
  
- VS Code automatically checks for updates to installed extensions.
  
- You can also click on the "Update" button in the Extensions view to check for updates.
  
- To uninstall an extension, go to the Extensions view.
Find the extension you want to uninstall and click on the gear icon.

- Select "Uninstall" from the dropdown menu.

Examples of essential extensions for web development:

JavaScript ESLint: Provides JavaScript code linting static analysis and integrates with ESLint for code quality and style checking.

HTML CSS Support: Improves HTML and CSS language support with auto-completion, formatting and error detection.

Live Server: Launches a local development server with live reload capability for dynamic web development.

GitLens:Provides insights to code history and repository navigation.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

- Open VS Code.
  
- Click on View in the menu bar.
  
- Select Terminal from the dropdown menu.
  
- Choose New Terminal to open a new instance of the integrated terminal.

- Or you can open the Command Palette Ctrl+Shift+P 

- Type View: Toggle Integrated Terminal and press Enter to open or close the integrated terminal

- Execute any command-line tool or script directly in the terminal.

- You can switch the integrated terminal to use a different shell by clicking on the dropdown arrow in the terminal panel and selecting your preferred shell Select Default Shell.

- Customize the terminal behavior and appearance by accessing VS Code settings File - Preferences - Settings

What are the advantages of using the integrated terminal compared to an external terminal?

- You don’t need to switch between your code editor and a separate terminal window. This reduces distractions and allows you to focus on coding without losing context.
  
- The integrated terminal opens at the root of your workspace by default, giving you direct access to files and directories related to your project.
  
- Execute commands and scripts directly within the same window where you're editing code.
  
- Debugging sessions can be initiated and managed directly from the integrated terminal, providing a seamless transition between coding and troubleshooting.

- You can choose which shell to use (e.g., Bash, PowerShell) based on your preference or project requirements
  
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

- Open VS Code.
  
- Click on File in the menu bar.
  
- Select New File to create a new file.

- Click on File in the menu bar.
  
- Select New Folder to create a new folder.

- Click on File in the menu bar.
  
- Select Open File to open a specific file.
  
- Click on File in the menu bar.

- Select Open Folder to open an entire folder as a workspace in VS Code.

Managing Files and Folders:

- Right-click on the file or folder in the Explorer sidebar.

- Select Rename and enter the new name.
  
- Drag and drop files or folders within the Explorer sidebar to move them.
  
- Or use Ctrl+X to cut and Paste Ctrl+V to move files or folders.
  
- Right-click on the file or folder in the Explorer sidebar.
  
- Select Delete to move the file or folder to the Recycle Bin.
  
- Use the Ctrl+P on your keyboard to open the Quick Open box.

- Type the name of the file you want to open and press Enter.

How can users navigate between different files and directories efficiently?

- View by clicking on the Explorer icon in the Activity Bar on the side Ctrl+Shift+E
  
- Navigate Files and Folders: Click on a file or folder in the Explorer to open it.

- Collapse/Expand Folders: Click on the arrow icon next to a folder to collapse or expand its contents.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

- Click on File in the menu bar 

- Select Preferences, then choose Settings or use Ctrl+ to directly open the Settings
  
- Open the Command Palette Ctrl+Shift+P
  
- Type Preferences: Open Settings and press Enter to open the Settings view.

- To open the Settings editor, navigate to File then Preferences then Settings or open the Settings editor from the Command Palette Ctrl+Shift+P with preferences: Open Settings or use Ctrl+

Provide examples of how to change the theme, font size, and keybindings.

- To change the theme:

- Open VS Code.

- Click on File in the menu bar.

- Select Preferences - Color Theme.

- Choose your desired theme from the list.

- Open the Command Palette Ctrl+Shift+P 

- Type Preferences: Color Theme and press Enter.

- Select your preferred theme from the list.

- Open VS Code.

- Click on File  in the menu bar

- Select Preferences - Settings.

- In the search bar, type "editor.fontSize".

- Adjust the value in the Editor: Font Size setting to your desired font size.

- Open VS Code.

- Click on File in the menu bar.

- Select Preferences - Keyboard Shortcuts.

- You can view and search through all default keybindings here.

- Open the Command Palette Ctrl+Shift+P 

- Type Preferences: Open Keyboard Shortcuts (JSON) and press Enter.

- Add or modify keybindings in the JSON file as per your preference

10. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
  
- Ensure that the debugger extension for your programming language is installed.
  
- Open the folder containing your project files in VS Code
  
- Click on File in the menu bar.
  
- Select Open Folder and choose the folder where your project is located
  
- Launch Configuration: VS Code uses launch configurations to specify how to start your program for debugging.
  
- Click on the Debug icon in the Activity Bar on the side or use Ctrl+Shift+D

- Click on the gear icon and select the environment you want to debug
  
- VS Code will generate a basic launch.json file if it doesn't exist and open it for editing.
  
- Adding Breakpoints: Place breakpoints in your code where you want the debugger to pause and allow you to inspect variables and step through the code.
  
- Click in the gutter next to the line number where you want to set a breakpoint. A red dot will appear to indicate the breakpoint.
  
- Starting Debugging Session: Once your launch configuration and breakpoints you can start debugging.
  
- Press F5 or click on the green play button in the Debug view.
  
- Control Buttons: Use the debug toolbar to control the debugging session. Common controls include Continue execution, Step Over, Step Into, Step Out, and Stop.
  
- Debugging Sidebar: The Debug view sidebar Ctrl+Shift+D shows variables, watches, and the call stack during debugging. You can inspect variable values and navigate through function calls.
  
- Wide Language Support: VS Code supports debugging for a variety of programming languages such as JavaScript, TypeScript, Python, Java.
  
- Extensible: Additional language support can be added through extensions, providing flexibility for different development environments.
  
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Users can integrate Git with VS Code for version control by:

Adding Git to a project folder in VS Code.

Initialize a new Git repository for an existing project folder.

Commit changes to your repository.

Push your changes to a remote repository (e.g., GitHub).

Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

- Launch Visual Studio Code

-	Open the folder of your project in VS Code File - Open Folder

-	Open the integrated terminal in VS Code by selecting View  - Terminal from the menu bar, or by pressing Ctrl+ `

- In the terminal that appears at the bottom of VS Code, type the following command to initialize a Git repository: git init
  
- To stage changes: open the Source Control view by clicking on the Source Control icon in the Activity Bar on the side of the window or use Ctrl+Shift+G
  
- You will see a list of changed files.
   
- Click the + button next to each file you want to stage, or click the + next to "Changes" to stage all changes.
  
- After staging your changes, enter a commit message in the text box at the top of the Source Control view.
  
- Press Ctrl+Enter or click the check mark icon √ to commit your changes.
  
- Ensure you have a GitHub repository created where you want to push your changes, if not already authenticated sign in using your GitHub credentials, VS Code will prompt you to do so when needed
  
- After committing your changes locally, you'll want to push them to your GitHub repository
  
- Click on the ellipsis ... next to your branch name in the Source Control view at the bottom left corner of VS Code
  
- Select Push from the dropdown menu
  
- If this is your first time pushing to this repository, enter the URL of your GitHub repository, paste the URL and press Enter.
  
- If you haven't authenticated yet, VS Code will prompt you to sign in to your GitHub account, follow the prompts to authenticate.
  
- VS Code will push your changes to GitHub, you can monitor the progress in the integrated terminal

- Once the push is complete, you can visit your GitHub repository in a web browser to see your changes

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

