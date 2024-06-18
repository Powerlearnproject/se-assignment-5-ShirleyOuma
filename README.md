[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280494&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
  Answer:
   - Installation of VS Code
   - Prerequisites: The system must meet the minimum requirements for VS Code. Windows 11 supports it without any problem.
   - Visit the Visual Studio Code website.
   - Click on the download button for Windows. The site automatically detect your operating system.
   - Installation: Once the download completes, run the installer, follow the installation instructions, Choose the default options.
   - After installation, VS Code should be ready to launch.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
  Answer:
   - Settings: Adjust indentation settings, file associations, and other preferences (File > Preferences > Settings).
   - Extensions: Install essential extensions like ESLint, Prettier, etc. (Extensions view on the Activity Bar).
   - Keybindings: Customize keybindings for a comfortable coding experience. (File > Preferences > Keyboard Shortcuts).

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
  Answer:
   - Activity Bar: The Activity Bar is located on the far left-hand side of the VS Code window. It offers access to file system, enabling user to browse and open files and folders. It also allows user to search across files in their workspace. It againiIntegrates with version control systems like Git, displaying changes and enabling user to commit, pull, and push changes. Provides quick access to run and debug functionalities, like launching and managing debugging sessions. Manages Visual Studio Code extensions, where user can search, install, enable and disable, and manage extensions.
   - Side Bar: It is adjacent to the Activity Bar, the Side Bar offers additional functionality and views. It displays the file and folder structure of user project. It also enables searching within files or across the entire workspace. It shows Git status, enabling user to stage, commit, and manage changes. It lists installed extensions and offers access to the Extensions Marketplace. It offers debugging controls and views when debugging sessions are active.
   - Editor Group: It is the central area of the Visual Studio Code window where text editors are opened. It displays files opened for editing and allows user to split editors horizontally or vertically to view and edit multiple files simultaneously (View > Editor Layout). It offers tabs for easy switching between open files. Lastly it supports previewing files without opening them fully, such as Markdown previews.
   - Status Bar: It is located at the bottom of the VS Code window, the Status Bar provides information about the current state of your workspace and actions you can perform. It displays the programming language associated with the current file and shows the line ending type used in the current file. It also displays the encoding type of the current file. It again shows Git branch information and allows for quick Git actions (commit, pull, push). Highlights errors and warnings in your code. Shows status messages from installed extensions.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
 Answer:
   The Command Palette in VS Code is a powerful tool that enables users to access various commands and features through a searchable interface. It provides a quick way to execute commands without having to navigate through menus or remember specific keyboard shortcuts. It can be accesses by keying Ctrl+Shift+P. Once the user press these keys, a small input box will appear at the top center of the VS Code window where the user can start typing to search for commands.
Examples:
Opening Files: Open File in the Command Palette to open a specific file. Also Open Folder to open an entire folder in VS Code.
Type View: Show All Editors to see all open files in the Editor Group and switch between them. Use Next Editor and Previous Editor to navigate through open files.
Managing Extensions: Install Extensions to search for and install new extensions from the Marketplace and also temporarily disable all installed extensions.
Running Tasks: Run Task to execute predefined tasks such as building your project or running tests. Customize tasks by editing the tasks.json file and execute them using the Command Palette.
Version Control (Git): Clone to clone a repository from a remote URL. Push to pull changes from and push changes to a remote repository.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   - Answer:
   - Extensions in Visual Studio Code (VS Code) enhance its functionality by adding new features, support for different programming languages, integrations with external tools, and more. They allow users to customize and tailor VS Code to suit their specific development needs. Extensions can range from simple utilities like code formatters to complex integrations with cloud services or advanced debugging tools.
   - Finding Extensions: The primary method to find extensions is through the VS Code Marketplace. You can access it directly from within VS Code by clicking on the Extensions view in the Activity Bar (Ctrl+Shift+X).
   - Finding:Use the search bar in the Extensions view to search for extensions by name, functionality, or tags.
   - Installing Extensions: Once the user find an extension, He/She can click the Install button next to it in the Marketplace.
   - Managing Extensions: In the Extensions view, you can disable or enable installed extensions as needed. To uninstall an extension, one can click on the gear icon next to the extension in the Extensions view and select Uninstall. VS Code automatically checks for updates to installed extensions. User can manually update them by clicking on the gear icon and selecting Update.
   - Examples: ESLint, Prettier, Live Server, GitLens, Path Intellisense.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
 Answer:
   - Steps to Open the Integrated Terminal:
Launch Visual Studio Code on computer.
You can use the keyboard shortcut to open that is, if you are using windows, `Ctrl+`` (backtick) or you can open it from the menu by Going to View in the top menu bar then select Terminal from the dropdown menu.
Once the terminal is open, you can use it just like any other command-line interface:
Use cd command to change directories, Execute commands like npm install, git status, etc, Customize the terminal shell by configuring VS Code settings.
External Terminal vs. Integrated Terminal
External Terminal:
Advantages: Might have advanced features or customization specific to the external terminal application.
Disadvantages: Requires switching between VS Code and the terminal, potentially disrupting workflow and reducing productivity.
Integrated Terminal:
Advantages: Seamlessly integrated into VS Code, offering a unified development environment.
Disadvantages: May lack some advanced features that specialized external terminals provide.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
 Answer:
Creating Files and Folders:
Open the Explorer view by clicking on the Explorer icon in the Activity Bar or use Ctrl+Shift+E, Right-click in the Explorer view and choose New File or New Folder, Write the desired name for the file or folder and press Enter to create it.
Using Command Palette: Open the Command Palette by clicking Ctrl+Shift+P on windows, Type New File or New Folder and press Enter to create a new file or folder respectively.
Opening Files:
Double-click on a file in the Explorer view to open it in the editor or right-click on the file and select Open.
Using Command Palette: Open the Command Palette by clicking Ctrl+Shift+P. Open File and enter the path to the file you want to open, or select it from the list.
Managing Files and Folders:
Renaming: In the Explorer view, right-click on a file or folder and choose Rename, then enter the new name and press Enter.
Deleting: Right-click on a file or folder in the Explorer view and select Delete, or press Delete key after selecting it. Confirm deletion in the prompt.
Moving/Copying: Drag and drop files and folders within the Explorer view to move or copy them or use Cut, Copy, and Paste options in the context menu.

Navigating Between Different Files and Directories Efficiently:
Switching Between Files: Use Ctrl+Tab to quickly switch between recently opened files.
Use Ctrl+P to open the Quick Open dialog. Type the file name to navigate directly to it.
Navigating Directories: In the Explorer view, navigate through directories by clicking on folders to expand or collapse them.
Workspaces and Projects: Use VS Code Workspaces to organize related files and folders together. User can save and reopen different workspace configurations.
Search and Go to Symbol: Use Ctrl+Shift+F to search across files in the workspace.
Use Ctrl+Shift+O to navigate to symbols (functions, classes, etc.) within the current file. 

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   - Answer:
Finding Settings: Click on the gear icon (⚙️) in the lower left corner of the VS Code window and select Settings or use the keyboard shortcut Ctrl+ to open the Settings.
Customizing Settings:
Changing the Theme: Go to Settings, In the search bar, type "Color Theme" to find the settings related to themes. Click on Color Theme under Workbench settings. Choose a theme from the list of installed themes or click Install Additional Color Themes to browse and install new themes from the Marketplace.
Example: Change the theme to Dark+ (default dark) or Light+ (default light).

Adjusting Font Size: Go to Settings. In the search bar, type "Font Size". Adjust the Editor to your preferred size.
You can also change the Editor Font Family setting to use a specific font family.
Example: Increase the font size to 16.

Customizing Keybindings: Go to Settings. In the search bar, type "Keybindings". Click on Keyboard Shortcuts to view and customize keybindings. You can search for specific commands or keybindings, and modify them by clicking on the pencil icon next to each binding.
Example: Add a new keybinding for a command by clicking + next to Keybindings and entering the desired key combination and command.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
 Answer:
   - Setting Up and Starting Debugging in VS Code.
   - Steps to Set Up and Start Debugging a Simple Program
Example: Debugging a Simple Python Program
Open the Extensions view by clicking on the Extensions icon in the Activity Bar (Ctrl+Shift+X).
Search for the "Python" extension by Microsoft and click Install.
Open the Explorer view (Ctrl+Shift+E).
Click on the New File icon and name the file plp.py.
Add some sample Python code, for example:

def greet(name):
    return f"Hello, {name}!"

name = "World"
print(greet(name))

Open the Debug View: Click on the Debug icon in the Activity Bar or use the shortcut Ctrl+Shift+D.
Click on the gear icon or the create a launch.json file link in the Debug view to configure the debugger.
VS Code will suggest creating a launch.json file for configuring your debugging environment. Choose Python as the environment.
A launch.json file will be created in a .vscode folder within your workspace. 
Set Breakpoints: Click in the left margin next to the line numbers in your code file (plp.py) to set breakpoints. A red dot will appear indicating a breakpoint.
For example, set a breakpoint on the line print(greet(name)).
Start Debugging: Press F5 or click the green play button in the Debug view to start debugging.
The debugger will start, and execution will pause at the breakpoints you’ve set, allowing you to inspect variables and the program’s state.
Inspect and Control Execution: Use the Debug toolbar that appears at the top of the editor to control the debugging session:
Continue (F5): Resume program execution until the next breakpoint.
Step Over (F10): Execute the next line of code, but without stepping into function calls.
Step Into (F11): Step into the function calls and execute line by line inside them.
Step Out (Shift+F11): Step out of the current function and return to the caller.
Restart (Ctrl+Shift+F5): Restart the debugging session.
Stop (Shift+F5): Stop the debugging session.

Key Debugging Features Available in VS Code
Setting Breakpoints: Pause execution at specific lines of code by clicking in the margin or pressing F9, Conditional Breakpoints: Break only when a specific condition is met. Right-click on the breakpoint and select Edit Breakpoint to add conditions. 
Watch Expressions: Watch Variables: Add variables or expressions to the Watch panel to monitor their values as you step through your code.
Inspect Variables: Hover over variables to see their current values, or use the Variables pane to see all local, global, and closure variables.
Integrated Console:
Evaluate Expressions: Use the Debug Console to evaluate expressions or run commands interactively during a debugging session.
Attach to Process: Attach the debugger to an already running process or server, useful for debugging applications started outside VS Code.
Conditional and Log Points:


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
 Answer:
    - Integrating Git with VS Code for Version Control
First, make sure Git is installed on your system and everything is setup.
Open VS Code and load your project folder. This can be done by clicking on File > Open Folder and selecting your project directory.
Click on the Source Control icon in the Activity Bar on the left (Ctrl+Shift+G).
If the project folder is not already a Git repository, click the Initialize Repository button in the Source Control view. This creates a .git folder in the project, setting it up as a Git repository.


Initialize a Git Repository:
In VS Code: Open your project folder in VS Code. Go to the Source Control view (Ctrl+Shift+G). Click the Initialize Repository button. If it's already a Git repository, the button won’t appear.
Using Terminal: Alternatively, open a terminal in VS Code (`Ctrl+``). Navigate to the project directory and run: git init

Stage and Commit Changes
Stage Files: In the Source Control view, you’ll see a list of changes under Changes. Click on the + icon next to each file to stage it, or click the + icon at the top of the Changes list to stage all files.
Commit Changes: Once files are staged, enter a commit message in the message box at the top of the Source Control view.
Click the checkmark icon or press Ctrl+Enter to commit the changes.

Connect to a Remote Repository on GitHub: Go to GitHub and create a new repository (leave it empty with no README, .gitignore, or license). In the terminal, add your GitHub repository as a remote: git remote add origin https://github.com/shirleyouma/your-repository.git

Push Changes to GitHub
Push to Remote: In the terminal, push your changes to GitHub code: git push -u origin main/master

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

