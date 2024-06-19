# Visual Studio Code Setup and Usage Guide

## Installation of VS Code

### Steps to Download and Install Visual Studio Code on Windows 11:
1. **Go to the Download Page**:
   - Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).

2. **Download the Installer**:
   - Click on the appropriate installer for Windows to start the download.

3. **Run the Installer**:
   - Open the downloaded file (`VSCodeSetup.exe`) to begin the installation process.
   
4. **Follow Installation Prompts**:
   - Accept the license agreement.
   - Choose the installation location.
   - Select additional tasks (e.g., creating a desktop icon, adding to PATH).
   - Click "Install" and wait for the process to complete.

5. **Launch Visual Studio Code**:
   - Once installed, launch VS Code from the Start menu or desktop shortcut.

### Prerequisites:
- Ensure your system meets the [system requirements](https://code.visualstudio.com/docs/supporting/requirements).
- Administrator privileges may be required to install VS Code.

## First-time Setup

### Initial Configurations and Settings:
1. **Welcome Page**:
   - Explore the welcome page to get an overview of features and setup tips.

2. **Theme and Appearance**:
   - Go to `File > Preferences > Color Theme` and choose a theme that suits your preference.
   - Adjust the font size via `File > Preferences > Settings`, and search for "font size".

3. **Install Extensions**:
   - Open the Extensions view by clicking the Extensions icon in the Activity Bar or pressing `Ctrl+Shift+X`.
   - Install essential extensions such as:
     - Python
     - GitLens
     - Prettier - Code formatter
     - ESLint

### Important Settings:
- **Auto Save**: Enable auto-save via `File > Auto Save`.
- **Tab Size**: Adjust tab size via `File > Preferences > Settings` and search for "tab size".
- **Linting**: Configure linting settings for your preferred languages.

## User Interface Overview

### Main Components of the VS Code User Interface:
1. **Activity Bar**:
   - Located on the far left, it provides access to views like Explorer, Search, Source Control, Run & Debug, and Extensions.

2. **Side Bar**:
   - Adjacent to the Activity Bar, it shows the contents of the selected view (e.g., file explorer, search results).

3. **Editor Group**:
   - The central area where you edit your files. You can have multiple editors open in tabs or split the editor into multiple groups.

4. **Status Bar**:
   - At the bottom of the window, it shows information about the current file, such as line number, encoding, and language mode. It also provides shortcuts to common tasks and displays the state of version control.

### Screenshot:
![bbl](https://github.com/LailaSamared/se-assignment-5-LailaSamared/assets/133321338/40fa085e-18c3-4623-98e8-f3d124dbbcb2)

## Command Palette

### What is the Command Palette?
- The Command Palette is a powerful tool in VS Code that allows you to access all commands and features.

### How to Access:
- Press `Ctrl+Shift+P` or `F1` to open the Command Palette.

### Examples of Common Tasks:
- **Change theme**: Type `>Preferences: Color Theme`.
- **Install extensions**: Type `>Extensions: Install Extensions`.
- **Open settings**: Type `>Preferences: Open Settings (JSON)`.

## Extensions in VS Code

### Role of Extensions:
- Extensions enhance VS Code functionality by adding support for additional languages, debuggers, and tools.

### Finding and Installing Extensions:
1. Open the Extensions view with `Ctrl+Shift+X`.
2. Search for the desired extension.
3. Click "Install" to add the extension.

### Managing Extensions:
- Manage installed extensions from the Extensions view, where you can disable, uninstall, or configure them.

### Essential Extensions for Web Development:
- **Live Server**: Launch a development local server with live reload feature.
- **HTML Snippets**: Adds rich language support for HTML.
- **Prettier - Code formatter**: Formats code automatically.

## Integrated Terminal

### How to Open and Use the Integrated Terminal:
1. Open the terminal with `Ctrl+``.
2. Use the terminal as you would any other command-line interface.

### Advantages:
- **Convenience**: Directly interacts with the file system and source control within the editor.
- **Context**: The terminal operates within the context of the current workspace, making it easier to manage project files.

## File and Folder Management

### Creating, Opening, and Managing Files and Folders:
1. **Create a New File**:
   - Use `File > New File` or press `Ctrl+N`.
2. **Create a New Folder**:
   - Right-click in the Explorer view and select "New Folder".
3. **Open Files and Folders**:
   - Use `File > Open File` or `File > Open Folder`.
4. **Navigate Between Files**:
   - Use the Explorer view or `Ctrl+P` to quickly open files.

## Settings and Preferences

### Customizing Settings:
- Access settings via `File > Preferences > Settings` or `Ctrl+,`.
- **Change Theme**:
  - Go to `File > Preferences > Color Theme`.
- **Change Font Size**:
  - In Settings, search for "font size" and adjust accordingly.
- **Change Keybindings**:
  - Go to `File > Preferences > Keyboard Shortcuts`.

### Screenshot:
![bl](https://github.com/LailaSamared/se-assignment-5-LailaSamared/assets/133321338/6e602cf9-4890-4a8a-9d49-7897caf28070)

## Debugging in VS Code

### Setting Up and Starting Debugging:
1. **Open the Debug View**:
   - Click the Run icon in the Activity Bar or press `Ctrl+Shift+D`.
2. **Configure Launch Settings**:
   - Click "create a launch.json file" to set up debug configurations.
3. **Start Debugging**:
   - Set breakpoints by clicking in the gutter next to the line numbers.
   - Press `F5` to start debugging.

### Key Debugging Features:
- **Breakpoints**: Pause execution at specific lines.
- **Watch**: Monitor variables and expressions.
- **Call Stack**: View the call stack and navigate through it.
- **Debug Console**: Evaluate expressions and interact with the program during debugging.

## Using Source Control

### Integrating Git with VS Code:
1. **Initialize a Repository**:
   - Open the Source Control view and click "Initialize Repository".
2. **Making Commits**:
   - Stage changes, enter a commit message, and click the commit icon.
3. **Pushing to GitHub**:
   - Set up the remote:
     ```bash
     git remote add origin https://github.com/yourusername/repository.git
     git push -u origin master
     ```

### Screenshot:
![last](https://github.com/LailaSamared/se-assignment-5-LailaSamared/assets/133321338/2eaa4024-0b8b-4b64-8cca-31391784a87e)

### References:
- https://code.visualstudio.com/docs
