[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15370725&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.


Visual Studio Code Installation

Prerequisites:
Operating System: Windows 11
Administrator access: Required to install software
Internet connection: Required to download the installer
Steps to Download and Install Visual Studio Code:
Open Your Web Browser:

Launch your preferred web browser (e.g., Chrome, Edge, Firefox).
Visit the Visual Studio Code Website:

Go to the official Visual Studio Code download page: Visual Studio Code.
Download the Installer:

On the homepage, click on the "Download for Windows" button.
The download should start automatically. If not, choose the appropriate version (User Installer or System Installer) from the list.
Run the Installer:

Once the download is complete, locate the installer file (e.g., VSCodeSetup.exe) in your Downloads folder.
Double-click the installer file to run it.
Begin Installation:

A User Account Control (UAC) prompt might appear asking for permission to make changes to your device. Click "Yes" to proceed.
The Visual Studio Code Setup Wizard will open.
Accept the License Agreement:

Read through the license agreement.
Check the box to accept the terms of the agreement.
Click "Next" to continue.
Choose Install Location:

You can use the default location or click "Browse" to choose a different installation folder.
Click "Next" to proceed.
Select Additional Tasks:

You can choose to create a desktop icon, add Open with Code actions to the context menu, register code as an editor for supported file types, add to PATH, and other options.
Select the options you prefer and click "Next."
Install Visual Studio Code:

Click the "Install" button to begin the installation.
Wait for the installation process to complete. This may take a few minutes.
Launch Visual Studio Code:

Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the box.
Click "Finish" to close the setup wizard.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.


Initial Configurations in VS Code:
User and Workspace Settings:

Open VS Code and go to File > Preferences > Settings (or press Ctrl + ,).
Adjust settings such as font size, theme, and tab size to your preference.
Themes:

Go to File > Preferences > Color Theme (or press Ctrl + K, Ctrl + T).
Choose a theme that suits your visual preference. Popular themes include "Dark+ (default dark)" and "Light+ (default light)".
Font Settings:

In the settings, search for editor.fontFamily and editor.fontSize to set your preferred font and size. Common choices are Fira Code and 16.
Auto Save:

Enable auto-saving to prevent losing changes. Search for files.autoSave in settings and set it to afterDelay or onWindowChange.
Format on Save:

To automatically format your code upon saving, search for editor.formatOnSave in settings and check the box.
Essential Extensions:
Language Support:

Python: ms-python.python
JavaScript/TypeScript: esbenp.prettier-vscode, dbaeumer.vscode-eslint
C/C++: ms-vscode.cpptools
Java: vscjava.vscode-java-pack
HTML/CSS: ecmel.vscode-html-css
Code Formatting:

Prettier - Code formatter: esbenp.prettier-vscode
Linting:

ESLint: dbaeumer.vscode-eslint
TSLint: ms-vscode.vscode-typescript-tslint-plugin
Git Integration:

GitLens: eamodio.gitlens
IntelliSense:

Visual Studio IntelliCode: VisualStudioExptTeam.vscodeintellicode
Debugging:

Debugger for Chrome: msjsdiag.debugger-for-chrome
Python: ms-python.python (includes debugging tools)
Live Server:

Live Server: ritwickdey.LiveServer (for web development)
Snippets:

JavaScript (ES6) code snippets: xabikos.javascriptsnippets
Python Snippets: donjayamanne.python-extension-pack
Version Control:

Git Graph: mhutchie.git-graph (visual representation of Git repositories)

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

Main Components of the VS Code User Interface:
Activity Bar:

Location: The vertical bar on the far left side of the window.
Purpose: Provides quick access to different views and functionality. It contains icons for various panels, such as:
Explorer: For file and folder navigation.
Search: For searching files within the workspace.
Source Control: For version control integration.
Run and Debug: For launching and managing debugging sessions.
Extensions: For browsing and installing extensions.
Customization: You can customize which icons appear by right-clicking on the Activity Bar.
Side Bar:

Location: Directly next to the Activity Bar.
Purpose: Displays different panels depending on the selected activity. It typically shows:
Explorer Pane: Lists the files and folders in the current workspace.
Search Pane: Provides search functionality within the workspace.
Source Control Pane: Manages version control operations.
Extensions Pane: Allows browsing and managing extensions.
Other Panels: Such as the Debug Pane, depending on the selected activity.
Functionality: Helps manage project files, search, and interact with source control.
Editor Group:

Location: The central part of the window, where you edit your code.
Purpose: The main area for opening, editing, and comparing files. Key features include:
Multiple Tabs: You can open multiple files in tabs and switch between them.
Split View: Allows you to split the editor horizontally or vertically to view multiple files simultaneously.
Diff View: For comparing two files side-by-side.
Customization: You can customize editor settings like font size, color theme, and indentation style.
Status Bar:

Location: The horizontal bar at the bottom of the window.
Purpose: Displays important information about the currently opened file and the overall state of the editor. This includes:
File Information: Such as line and column number, encoding, and language mode.
Git Branch and Status: Displays the current Git branch and status of the repository.
Background Processes: Indicates ongoing processes like running tasks or background extensions.
Quick Access: Provides shortcuts to toggle settings like line endings, spaces vs. tabs, and more.
Interactivity: Clicking on items in the Status Bar often opens related settings or information.
Additional UI Components:
Command Palette:

Access: Via Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (macOS).
Purpose: Provides a quick way to access commands, settings, and features without navigating through menus.
Panel:

Location: At the bottom of the window, it can be toggled to display different views.
Purpose: Shows additional information such as the terminal, output, problems, and debug console.
Minimap:

Location: A small overview of your file located on the right side of the editor.
Purpose: Allows quick navigation within a large file.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

Accessing the Command Palette:
Windows/Linux: Press Ctrl + Shift + P
macOS: Press Cmd + Shift + P
Alternatively, you can access it by clicking on the View menu and selecting "Command Palette."

Common Tasks Performed Using the Command Palette:
Opening Files and Folders:

Command: Open File...
Example: Quickly open a specific file without navigating through the file explorer.
Running Extensions:

Command: Extensions: Install Extensions
Example: Search for and install new extensions directly from the Command Palette.
Changing Settings:

Command: Preferences: Open Settings (UI)
Example: Open the settings UI to adjust configurations like theme, font size, and more.
Changing Themes:

Command: Preferences: Color Theme
Example: Switch between light and dark themes or select a new color theme.
Formatting Code:

Command: Format Document
Example: Automatically format the currently open document according to the configured code style.
Git Commands:

Command: Git: Commit
Example: Commit changes to the Git repository directly from the editor.
Running Debug Configurations:

Command: Debug: Start Debugging
Example: Start a debugging session for the currently open project.
Opening Terminals:

Command: Terminal: Create New Integrated Terminal
Example: Open a new integrated terminal within VS Code.
Navigating to Symbols:

Command: Go to Symbol in Workspace...
Example: Quickly navigate to a function, variable, or class within the workspace.
Refactoring Code:

Command: Refactor...
Example: Perform refactoring operations like renaming a symbol or extracting a method.
Searching Files:

Command: Search: Find in Files
Example: Perform a search across all files in the workspace.
Installing Language Packs:

Command: Configure Display Language
Example: Change the display language of the VS Code interface.
Examples of Using the Command Palette:
Opening a File:

Open the Command Palette (Ctrl + Shift + P).
Type Open File and press Enter.
Select the file you want to open.
Changing the Color Theme:

Open the Command Palette (Ctrl + Shift + P).
Type Color Theme and press Enter.
Choose a theme from the list.
Formatting the Current Document:

Open the Command Palette (Ctrl + Shift + P).
Type Format Document and press Enter.
Installing an Extension:

Open the Command Palette (Ctrl + Shift + P).
Type Extensions: Install Extensions and press Enter.
Search for the desired extension and install it.
Starting a Debugging Session:

Open the Command Palette (Ctrl + Shift + P).
Type Debug: Start Debugging and press Enter.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Role of Extensions in VS Code
Extensions play a crucial role in Visual Studio Code by enhancing its functionality and adapting it to specific needs. They allow users to add features, integrate with other tools, and customize the editor to support various programming languages, frameworks, and workflows. Extensions can provide functionalities such as syntax highlighting, linting, debugging, code formatting, snippets, and version control integration, among others.

Finding, Installing, and Managing Extensions
Finding Extensions
Using the Extensions View:

Click on the Extensions icon in the Activity Bar on the side of the window (or press Ctrl + Shift + X).
This opens the Extensions View, where you can search for extensions by name, category, or keyword.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P).
Type Extensions: Install Extensions and press Enter.
Search for the desired extension.
Installing Extensions
From the Extensions View:

Search for the extension you want to install.
Click on the Install button next to the extension's name.
VS Code will download and install the extension automatically.
From the Marketplace Website:

Visit the Visual Studio Code Marketplace.
Search for the extension.
Click on the extension and follow the installation instructions, which typically involve opening the extension directly in VS Code.
Managing Extensions
Viewing Installed Extensions:

Go to the Extensions View (Ctrl + Shift + X).
The installed extensions are listed under the "Installed" section.
Disabling or Enabling Extensions:

In the Extensions View, right-click on the installed extension.
Select Disable to temporarily disable it or Enable to re-enable it.
Uninstalling Extensions:

In the Extensions View, right-click on the installed extension.
Select Uninstall to remove the extension from VS Code.
Updating Extensions:

VS Code usually checks for updates automatically and shows an Update button next to the extension if an update is available.
Click the Update button to update the extension.
Essential Extensions for Web Development
Live Server:

Extension ID: ritwickdey.LiveServer
Purpose: Launches a local development server with live reload feature for static and dynamic pages.
Prettier - Code Formatter:

Extension ID: esbenp.prettier-vscode
Purpose: Formats code automatically according to a consistent style.
ESLint:

Extension ID: dbaeumer.vscode-eslint
Purpose: Integrates ESLint into VS Code to provide JavaScript and TypeScript linting.
HTML CSS Support:

Extension ID: ecmel.vscode-html-css
Purpose: Enhances support for HTML and CSS files.
JavaScript (ES6) Code Snippets:

Extension ID: xabikos.javascriptsnippets
Purpose: Provides a comprehensive collection of JavaScript code snippets.
Debugger for Chrome:

Extension ID: msjsdiag.debugger-for-chrome
Purpose: Enables debugging of JavaScript code running in Google Chrome directly from VS Code.
Path Intellisense:

Extension ID: christian-kohler.path-intellisense
Purpose: Autocompletes filenames as you type.
Bracket Pair Colorizer:

Extension ID: CoenraadS.bracket-pair-colorizer-2
Purpose: Colors matching brackets to make them easier to identify.
GitLens:

Extension ID: eamodio.gitlens
Purpose: Enhances Git capabilities in VS Code, providing insights into code changes, authorship, and more.
Auto Rename Tag:

Extension ID: formulahendry.auto-rename-tag
Purpose: Automatically renames paired HTML/XML tags.
6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Opening and Using the Integrated Terminal in VS Code
Opening the Integrated Terminal:
Using the Menu:

Go to View > Terminal.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P).
Type Terminal: Create New Integrated Terminal and press Enter.
Using Keyboard Shortcut:

Press Ctrl + (backtick) to open the integrated terminal directly.
Using the Integrated Terminal:
Basic Operations:

New Terminal: Click the + icon in the terminal panel or use the Ctrl + Shift + shortcut.
Close Terminal: Click the trash can icon next to the terminal tab you want to close.
Switch Between Terminals: If you have multiple terminal sessions, you can switch between them by clicking on their tabs.
Split Terminal: Click the split terminal icon to create a new terminal instance side-by-side with the current one.
Customizing the Terminal:

Change Shell: You can change the default shell by navigating to File > Preferences > Settings, searching for terminal.integrated.shell.windows (or the appropriate setting for your OS), and setting the path to your preferred shell (e.g., PowerShell, Git Bash, WSL).
Appearance: Customize the terminal’s appearance by adjusting settings like font size, cursor style, and background color in the settings (Ctrl + ,).
Running Commands:

The integrated terminal allows you to run commands just like any other terminal. You can run build scripts, start servers, use version control commands, etc.
Example commands:
git status to check the status of your Git repository.
npm start to start a Node.js server.
python script.py to run a Python script.
Advantages of Using the Integrated Terminal Compared to an External Terminal
Seamless Workflow Integration:

Context Switching: Reduces the need to switch between different applications. You can stay within the same VS Code window, which helps maintain focus and productivity.
Project Context: The integrated terminal opens in the context of your workspace, automatically setting the working directory to your project folder.
Enhanced Productivity:

Multiple Terminals: Easily create and manage multiple terminal sessions within the same window.
Split View: Split terminals allow you to view and interact with multiple terminal sessions side-by-side, facilitating multitasking.
Shared Environment: The terminal shares the same environment as the VS Code editor, making it easier to execute commands related to the currently open project.
Customization and Consistency:

Consistent Look and Feel: The integrated terminal inherits the appearance settings from VS Code, providing a consistent look and feel.
Custom Keybindings: You can set up custom keybindings to open, close, or switch between terminals, tailoring the experience to your preferences.
Integration with Editor Features:

Problem Matchers: VS Code can parse terminal output to link errors and warnings back to the source code, allowing for quick navigation and fixes.
Terminal Commands: Execute VS Code commands directly from the terminal using the code command, such as code . to open the current directory in a new VS Code window.
Enhanced Debugging:

Debug Console Integration: The integrated terminal works seamlessly with the VS Code Debugger, making it easier to run and debug applications without leaving the editor.
Environment Consistency:

Shared Environment Variables: The integrated terminal can share environment variables with VS Code, ensuring consistency across your development tools.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Creating, Opening, and Managing Files and Folders in VS Code
Creating Files and Folders:
Using the Explorer View:

Create a New File:
Open the Explorer view by clicking the Explorer icon in the Activity Bar or by pressing Ctrl + Shift + E.
Right-click on the folder where you want to create a new file and select New File.
Enter the name of the new file and press Enter.
Create a New Folder:
Right-click on the folder where you want to create a new folder and select New Folder.
Enter the name of the new folder and press Enter.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P).
Type File: New File or File: New Folder and press Enter.
Using Keyboard Shortcuts:

New File: Press Ctrl + N to create a new untitled file.
Opening Files and Folders:
Using the Explorer View:

Open a File:
Navigate to the file in the Explorer view and click on it to open it in the editor.
Open a Folder:
Click the Open Folder button in the Explorer view or go to File > Open Folder... and select the desired folder.
Using the Command Palette:

Open a File:
Open the Command Palette (Ctrl + Shift + P).
Type File: Open File... and press Enter.
Open a Folder:
Open the Command Palette (Ctrl + Shift + P).
Type File: Open Folder... and press Enter.
Using Keyboard Shortcuts:

Open File: Press Ctrl + O to open the file dialog and select a file.
Open Folder: Press Ctrl + K, Ctrl + O to open the folder dialog and select a folder.
Managing Files and Folders:
Rename:

Right-click on the file or folder in the Explorer view and select Rename.
Enter the new name and press Enter.
Delete:

Right-click on the file or folder in the Explorer view and select Delete.
Confirm the deletion if prompted.
Move:

Drag and drop the file or folder to the desired location in the Explorer view.
Copy and Paste:

Right-click on the file or folder and select Copy.
Right-click on the target location and select Paste.
Efficient Navigation Between Files and Directories
Explorer View:

Use the Explorer view to navigate through your project’s files and folders quickly.
Click on a file to open it, and use the arrow keys to navigate up and down the list.
Quick Open:

Press Ctrl + P to open the Quick Open dialog.
Start typing the name of the file you want to open, and VS Code will display a list of matching files.
Use the arrow keys to select the file and press Enter to open it.
Go to Definition:

Use F12 or right-click on a symbol and select Go to Definition to navigate to the definition of a function, variable, or class.
Go to Symbol:

Press Ctrl + Shift + O to open the Go to Symbol dialog.
Start typing the name of the symbol you want to navigate to and select it from the list.
Breadcrumb Navigation:

Use the breadcrumb navigation bar at the top of the editor to navigate to parent directories or sibling files.
Open Recent:

Press Ctrl + R to open the list of recently opened files and folders.
Select the file or folder you want to reopen.
File Tabs:

Use the file tabs at the top of the editor to switch between open files.
Use Ctrl + Tab to cycle through open files.
Side Bar Views:

Utilize the Search view (Ctrl + Shift + F) to find files and navigate to them quickly.
Use the Source Control view to manage and navigate changes in your project.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Finding and Customizing Settings in VS Code
VS Code settings can be customized to enhance your development experience. Users can find and modify these settings using the Settings UI or directly editing the settings.json file.

Accessing Settings
Using the Settings UI:

Open the Settings UI by clicking on the gear icon in the lower left corner and selecting Settings.
Alternatively, you can open the Settings UI by pressing Ctrl + ,.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P).
Type Preferences: Open Settings (UI) and press Enter.
Editing settings.json Directly:

Open the Command Palette (Ctrl + Shift + P).
Type Preferences: Open Settings (JSON) and press Enter.
Customizing Settings Examples
Changing the Theme
Using the Settings UI:

Open the Settings UI (Ctrl + ,).
In the search bar at the top, type color theme.
Click on Color Theme under Preferences.
Select your desired theme from the list.
Using the Command Palette:

Open the Command Palette (Ctrl + Shift + P).
Type Preferences: Color Theme and press Enter.
Select your desired theme from the list.
Changing the Font Size
Using the Settings UI:

Open the Settings UI (Ctrl + ,).
In the search bar at the top, type font size.
Find the setting Editor: Font Size.
Enter your desired font size (e.g., 16).
Using settings.json:

Open the settings.json file (Ctrl + Shift + P, then type Preferences: Open Settings (JSON)).
Add or modify the following line:
json
"editor.fontSize": 16
Changing Keybindings
Using the Keybindings UI:

Open the Keybindings UI by clicking on the gear icon in the lower left corner and selecting Keyboard Shortcuts.
Alternatively, press Ctrl + K, Ctrl + S.
Search for the command you want to change.
Click on the pencil icon next to the command and press the new key combination.
Using keybindings.json:

Open the Command Palette (Ctrl + Shift + P).
Type Preferences: Open Keyboard Shortcuts (JSON) and press Enter.
Add or modify keybindings in the keybindings.json file. For example, to change the keybinding for saving a file to Ctrl + S:
json
[
  {
    "key": "ctrl+s",
    "command": "workbench.action.files.save"
  }
]
Examples
Changing the Theme to a Dark Theme:

Open the Command Palette (Ctrl + Shift + P).
Type Preferences: Color Theme and press Enter.
Select Dark+ (default dark) or any other dark theme.
Changing the Font Size to 18:

Open the Settings UI (Ctrl + ,).
In the search bar, type font size.
Find Editor: Font Size and set it to 18.
Changing the Keybinding for Opening a New File to Ctrl + Alt + N:

Open the Keybindings UI (Ctrl + K, Ctrl + S).
Search for File: New File.
Click on the pencil icon next to it.
Press Ctrl + Alt + N.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Steps to Set Up and Start Debugging a Simple Program in VS Code
Let's go through the process of setting up and debugging a simple Python program as an example. The steps are similar for other languages with minor adjustments.

1. Install Necessary Extensions
For Python:
Install the Python extension by Microsoft.
Open the Extensions view (Ctrl + Shift + X).
Search for "Python" and install the extension by Microsoft.
2. Create a Simple Program
Create a New File:

Open VS Code.
Create a new file (Ctrl + N) and save it with a .py extension, e.g., hello.py.
Write Your Code:

Add some simple Python code to the file:
python
def greet(name):
    print(f"Hello, {name}")

if __name__ == "__main__":
    user_name = "World"
    greet(user_name)
3. Configure the Debugger
Open the Debug View:

Click on the Debug icon in the Activity Bar on the side of the window or press Ctrl + Shift + D.
Create a Debug Configuration:

Click the gear icon (Configure or Fix 'launch.json') to open the launch.json file.
If prompted to select an environment, choose "Python".
VS Code will generate a launch.json file with a configuration similar to the following:
json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Python: Current File",
            "type": "python",
            "request": "launch",
            "program": "${file}",
            "console": "integratedTerminal"
        }
    ]
}
4. Set Breakpoints
Setting Breakpoints:
Click in the gutter to the left of the line numbers where you want to set a breakpoint, or place the cursor on a line and press F9.
5. Start Debugging
Run the Debugger:
Click the green play button in the Debug view or press F5.
6. Interact with the Debugger
Debug Controls:
Continue (F5): Continue execution until the next breakpoint.
Step Over (F10): Execute the next line of code but don’t step into functions.
Step Into (F11): Step into functions to debug inside them.
Step Out (Shift + F11): Step out of the current function.
Restart (Ctrl + Shift + F5): Restart the debugging session.
Stop (Shift + F5): Stop debugging.
Key Debugging Features Available in VS Code
Breakpoints:

Set breakpoints to pause execution at specific lines of code.
Watch:

Monitor the value of variables and expressions in the Watch panel. Add variables or expressions by clicking the + icon in the Watch section.
Variables:

View and inspect variables in the Variables panel. It shows local, global, and closure variables and their current values.
Call Stack:

View the call stack to understand the sequence of function calls leading to the current point of execution.
Debug Console:

Execute arbitrary Python expressions and commands in the context of the paused program. It allows for on-the-fly debugging and variable inspection.
Integrated Terminal:

Use the integrated terminal to run shell commands without leaving VS Code.
Exception Handling:

Configure the debugger to break on handled and unhandled exceptions, allowing for detailed inspection of errors.
Conditional Breakpoints:

Set breakpoints that only trigger when a specified condition is met, helping to debug complex scenarios more effectively.
Logpoints:

Use logpoints to output messages to the console without pausing execution. These are useful for adding debug output without modifying your code.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Install Git:

Ensure Git is installed on your system. You can download it from git-scm.com and follow the installation instructions.
Sign up for GitHub:

If you haven't already, sign up for a GitHub account at github.com.
Initializing a Repository
Open VS Code:

Launch Visual Studio Code.
Open a Folder:

Open the folder containing your project or create a new folder (File > Open Folder...).
Initialize Git Repository:

Open the Command Palette (Ctrl + Shift + P).
Type Git: Initialize Repository and press Enter.
Select the folder you want to initialize as a Git repository.
Making Commits
Stage Changes:

In the Source Control view (Ctrl + Shift + G), you'll see a list of changes. Click the + button next to each file or use the + button at the top of the panel to stage all changes.
Commit Changes:

Enter a commit message in the textbox at the top of the Source Control view.
Press Ctrl + Enter or click the checkmark icon to commit the changes.
Pushing Changes to GitHub
Create a GitHub Repository:

Go to GitHub and create a new repository if you haven't already.
Add Remote Repository:

Copy the URL of your GitHub repository.
In VS Code, open the Command Palette (Ctrl + Shift + P).
Type Git: Add Remote and press Enter.
Paste the GitHub repository URL.
Push Changes:

Open the Source Control view (Ctrl + Shift + G).
Click the three dots (ellipsis) next to the checkmark icon and select Push.
VS Code will prompt you to select the branch to push. Choose the branch you want to push to GitHub and click OK.
Enter your GitHub credentials if prompted.
Key Features and Tips
Branches: Manage branches using the Source Control view. Create, switch, and merge branches directly in VS Code.

History and Diffs: View commit history, compare changes (diffs), and revert changes using the Source Control view and the GitLens extension.

Pull Requests: After pushing changes to GitHub, you can create pull requests directly from GitHub to collaborate with others.

Extensions: Consider installing GitLens (eamodio.gitlens) for advanced Git features and better visualization of Git repository data.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

