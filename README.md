# Intro to VS Code
Dive into the world of efficient coding with our upcoming VS Code workshop, tailored specifically for align students looking to streamline their development process. Learn how to customize your coding environment with powerful extensions, debug with ease, and collaborate in real-time with your peers, all within one of the most popular code editors available today.
# Why VS Code?
VS Code has become a pivotal tool in today's programming environment due to its versatility, efficiency, and broad support for programming languages and development tools. It bridges the gap between a lightweight text editor and a full-fledged Integrated Development Environment (IDE), providing developers with a highly customizable platform that can be tailored to fit almost any development workflow. With its extensive library of extensions, it allows programmers to add just about any functionality they need, from language-specific syntax highlighting and code completion to advanced debugging and version control integration.

In summary:
- Versatile: Supports a wide range of programming languages and tools.
- Efficient: Combines the simplicity of a text editor with the power of an IDE.
- Customizable: Extensive library of extensions for personalized development environments. (They have an unbeatable selection of extensions)
- Community Supported: Strong open-source community for continuous updates and support.
- Trend-Compatible: Stays current with the latest technologies and programming practices.
- Lightweight: this is small download (< 200 MB) and has a disk footprint of less than 500 MB (compared to Intellij and Eclipse carry a much heavier memory footprint).
# Installation and Setup
Should be pretty straightforward to download. Instructions for Windows, Linux, and MacOS installations in the link below.
https://code.visualstudio.com/docs/setup/setup-overview
## Basic Overview
### User Interface Overview

- **Editor**: The main area to edit your files. You can open multiple editors side by side.
- **Viewlets**: Sidebar panels that give you access to features like search, Git, and extensions.
- **Command Palette**: Access most commands and features (⇧⌘P on macOS and Ctrl+Shift+P on Windows/Linux).
- **Status Bar**: Information about the opened project and files you're working on, located at the bottom.

### Setting Up Your Workspace

1. **Themes**: Customize the look and feel of your editor through `File > Preferences > Color Theme`.
2. **Font Size**: Adjust the font size in the editor via `File > Preferences > Settings > Editor: Font Size`.
3. **Display Language**: Set your preferred language through `File > Preferences > Display Language`.

## Core Features

### Editing Code

- **Syntax Highlighting**: Automatically applies color and styles to your code for better readability.
- **IntelliSense**: Offers code completions based on variable types, function definitions, and imported modules.
- **Snippets**: Type a snippet prefix and press `Tab` to insert code snippets.

### Debugging

- Navigate to the Run view (`Ctrl+Shift+D` on Windows/Linux, `⇧⌘D` on macOS), and use the **Run and Debug** button to start debugging.
- Configure launch settings by editing the `.vscode/launch.json` file to specify how to run and debug your application.

### Version Control Integration

- **Git Support**: Directly manage your Git repositories within VS Code. Commit changes, branch, merge, and more through the Source Control panel.
- Initiate Git commands through the Command Palette or the Source Control panel.

### Live Share

- **Collaborative Coding**: Share your project with others and code together in real time.
- Install the Live Share extension from the VS Code Marketplace, and start a session via the Live Share viewlet.
## Creating your first VS Code workspace
### What is a 'workspace'?
In VS Code, a workspace is a collection of folders and files that you are working on, often related to a specific project or set of projects. Workspaces help organize, manage, and maintain context for your development tasks, including settings, extensions, and debug configurations, specific to that project or set of tasks.
### Creating a workspace
- Navigate to the main menu
- Click open
- Choose selected directory to make the workspace
  
https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/c7616680-8c79-484d-bd72-2b86c53fd551

### Navigating the workspace
Navigating the workspace in VS Code is straightforward and efficient, allowing you to focus on your development tasks. Here's how to effectively move around and manage your workspace:

- **Explorer View**: Accessible via the `View > Explorer` or by pressing `Ctrl+Shift+E` (Windows/Linux) or `Cmd+Shift+E` (macOS), this is your main hub for browsing files and folders within your workspace.
<img width="1901" alt="Screenshot 2024-04-02 at 1 35 42 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/61cfe0ff-07fe-436f-b82e-3f2dac48171a">

- **Search**: Use the `View > Search` feature or press `Ctrl+F` (Windows/Linux) or `Cmd+F` (macOS) to quickly find files, symbols, or even specific text across your entire workspace.
  <img width="1914" alt="Screenshot 2024-04-02 at 1 35 58 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/7f10f3d0-17ba-4f25-b7f9-333571c402c6">

- **Source Control**: The `View > SCM` option or `Ctrl+Shift+G` (Windows/Linux) or `Cmd+Shift+G` (macOS) shortcut opens the Source Control panel, where you can manage all your version control settings and changes.
<img width="1908" alt="Screenshot 2024-04-02 at 1 36 29 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/a3d8e695-1398-421f-a731-2c50b66c0218">

- **Extensions**: Adding functionality to your workspace is easy through the `View > Extensions` or by using the `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS) shortcut. Here, you can browse, install, and manage extensions.
<img width="1908" alt="Screenshot 2024-04-02 at 1 55 20 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/65fb55c4-ed7b-4b24-935a-a16b86001b4b">

- **Multi-root Workspaces**: For working with multiple projects, you can add folders to your workspace by selecting `File > Add Folder to Workspace...`. This allows you to group and manage related projects under a single workspace window.

- **Tabs and Split View**: Organize open files into tabs for easy access. Split your editor (`View > Editor Layout > Split Up/Down/Left/Right`) to work on multiple files side by side.
<img width="1912" alt="Screenshot 2024-04-02 at 1 56 42 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/e3dfa0e6-2d8d-47c9-b8d4-da5b33360cf2">

- **Terminal and Debug Panels**: Access the integrated terminal via `` Ctrl+` `` (Windows/Linux) or `` Cmd+` `` (macOS) and the Debug panel through `View > Debug` or `Ctrl+Shift+D` (Windows/Linux) or `Cmd+Shift+D` (macOS) to execute commands and debug your application directly within VS Code.
<img width="1917" alt="Screenshot 2024-04-02 at 1 36 46 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/75ce1e35-34c1-4c5e-9e0f-89b13e958704">

### Customizing and configuring VS Code to work for you (Tips)
#### Install language specific extensions to expand intellisense coverage
VS Code comes equipped with built-in IntelliSense support for a core set of languages, including JavaScript, TypeScript, JSON, HTML, CSS, and SCSS. This feature significantly enhances your coding efficiency by providing smart completions and insights directly out of the box. For those working in languages beyond this core set, expanding VS Code's IntelliSense capabilities is as simple as installing language-specific extensions. This flexibility ensures that VS Code's powerful code comprehension and assistance features can be tailored to virtually any programming language.
#### Enable Autosave (thank me later)
VS Code's AutoSave feature automatically saves your changes to your files after a delay, ensuring you never lose your work due to an unexpected interruption.
How to enable: `file < auto-save`.
### Basic Editing

Mastering basic editing in VS Code can significantly streamline your coding workflow. Here are some essential techniques and shortcuts:

- **Highlighting**: Click and drag your mouse over the text, or hold `Shift` and use the arrow keys to select text. For column (box) selection, hold `Shift+Alt` while dragging the mouse, or `Shift+Alt+Arrow Keys`.

- **Cut, Copy, and Paste**: Use the familiar `Ctrl+X` (Cut), `Ctrl+C` (Copy), and `Ctrl+V` (Paste) shortcuts (Windows/Linux), or `Cmd+X`, `Cmd+C`, and `Cmd+V` (macOS).

- **Undo and Redo**: Quickly revert or reapply changes with `Ctrl+Z` for Undo and `Ctrl+Y` or `Ctrl+Shift+Z` for Redo (Windows/Linux), or `Cmd+Z` and `Cmd+Shift+Z` (macOS).

- **Find and Replace**: Open the Find panel with `Ctrl+F` and the Replace panel with `Ctrl+H` (Windows/Linux), or `Cmd+F` and `Cmd+Alt+F` (macOS), to search and replace text within the current file.

- **Line Manipulation**: Move lines up or down with `Alt+Up` or `Alt+Down`, and duplicate lines with `Shift+Alt+Down` or `Shift+Alt+Up` (Windows/Linux), or `Option+Up`/`Option+Down` and `Shift+Option+Down`/`Shift+Option+Up` (macOS).

- **Code Folding**: Collapse or expand sections of code using the folding controls next to the line numbers or through `Ctrl+Shift+[` to fold and `Ctrl+Shift+]` to unfold (Windows/Linux), or `Cmd+Option+[` and `Cmd+Option+]` (macOS).

- **Commenting Code**: Quickly comment or uncomment lines or blocks of code with `Ctrl+/` for line comments and `Shift+Alt+A` for block comments (Windows/Linux), or `Cmd+/` and `Shift+Option+A` (macOS).

Embracing these editing basics will enhance your efficiency, allowing you to focus more on coding and less on navigating through your editor.


