# Intro to VS Code (Roux Learner Lab)
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

### Debugging

Mastering basic debugging in VS Code can significantly enhance your problem-solving skills. Let's use a simple Python script that attempts to calculate the factorial of a number but contains some errors. We'll walk through how to set up and use the debugger to identify and fix these issues.

#### Example Python Script

```python
def factorial(n):
    if n < 0:
        return "Error: Negative number"
    elif n == 1:
        return 1
    else:
        return n * factorial(n)

print(factorial(5))
```
#### Setting up your debugger
1. Create a .vscode folder in your project root if it doesn't already exist.
2. Add a launch.json file inside the .vscode folder.
3. Configure your Python debugging settings by adding the following configuration to launch.json:

```
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
```
**NOTE**: You can also just boot up the debugger and it will open up an option for you to choose the runtime for the debugger and it will create the launch.json for you
**EXTRA-NOTE**: You can create global launch configerations for debugging so you do not have to do so for each new workspace: ```code < settings < user < debug```
<img width="1899" alt="Screenshot 2024-04-02 at 3 48 48 PM" src="https://github.com/mbrown1103-ME/vscode_intro/assets/155906837/999d508a-7675-4216-82d5-d6020173c4a1">

#### Debugger Commands

Below is a summary of key debugging actions in VS Code and their explanations:

| Action        | Shortcut | Explanation |
|---------------|:--------:|-------------|
| **Continue / Pause** | `F5` | **Continue**: Resume normal program/script execution (up to the next breakpoint).<br>**Pause**: Inspect code executing at the current line and debug line-by-line. |
| **Step Over**  | `F10`   | Execute the next line or method as a single command without inspecting or following its component steps. |
| **Step Into**  | `F11`   | Enter the next function or method to follow its execution line-by-line. |
| **Step Out**   | `⇧F11`  | When inside a function or method, return to the earlier execution context by completing the remaining lines of the current function as though it were a single command. |
| **Restart**    | `⇧⌘F5` | Terminate the current program execution and start debugging again using the current run configuration. |
| **Stop**       | `⇧F5`   | Terminate the current program execution. |

These commands are essential for effectively navigating and understanding the flow of your program during debugging sessions.

#### Debugging the Script

- **Set a Breakpoint**: Click to the left of the line number where you wish to halt execution. For this example, placing a breakpoint at the beginning of the `factorial` function is advisable.
- **Start Debugging**: Press `F5` or click the green play button in the Debugging panel to begin the debugging session.
- **Inspect Variables**: When the execution pauses at a breakpoint, hover over variables to view their current values. In this case, examine the value of `n` during the recursive calls.
- **Step Through Code**: Navigate through your code using the step-over (`F10`), step-into (`F11`), and step-out (`Shift+F11`) commands.
- **Identify the Errors**: Observe that the recursive call fails to decrement `n`, leading to infinite recursion for `n > 1`. Additionally, the base case for `n == 0` is absent.

#### Fixing the Script

To rectify the script, adjust the recursive call to decrement `n` and introduce a base case for `n == 0`:

```python
def factorial(n):
    if n < 0:
        return "Error: Negative number"
    elif n == 0 or n == 1:  # Added base case for n == 0
        return 1
    else:
        return n * factorial(n - 1)  # Corrected recursive call
```

### Version Control Integration with Git in VS Code

VS Code provides seamless integration with Git, a distributed version control system, enabling developers to efficiently manage changes to their codebase. This integration supports a wide range of Git operations directly within the VS Code interface, including committing changes, branching, and merging. Here’s how to leverage these features:

#### Committing Changes

1. **Stage Changes**: In the Source Control panel, select the files you want to commit and click the "+" button to stage them. Alternatively, you can stage all changes by clicking the "Stage All Changes" button.
2. **Commit Staged Changes**: Once changes are staged, type a commit message in the message box and press `Ctrl+Enter` (Windows/Linux) or `Cmd+Enter` (macOS) to commit them. Ensure your commit message is descriptive of the changes made.

#### Branching

1. **Create a New Branch**: Access the branch management features by clicking on the branch name in the bottom left corner of the status bar. Select "Create new branch..." and enter a name for your branch.
2. **Switch Branches**: To switch between branches, click on the branch name in the status bar and select the branch you wish to check out.

#### Merging

1. **Merge Branches**: To merge changes from one branch into another, first switch to the target branch you want to merge into. Then, open the Command Palette with `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) and type "Git: Merge Branch...". Select the branch you want to merge from the list.

#### Resolving Merge Conflicts

1. **Identify Conflicts**: During a merge, conflicts may arise. VS Code will highlight these conflicts in the editor.
2. **Resolve Conflicts**: Edit the files to resolve the conflicts, choosing which changes to keep. Use the "Accept Current Change", "Accept Incoming Change", "Accept Both Changes", or "Compare Changes" options as needed.
3. **Finalize the Merge**: After resolving all conflicts, stage the resolved files and commit the merge. VS Code may automatically commit the merge if all conflicts are resolved through the editor.

#### Viewing History and Reverting Changes

- **View Commit History**: Open the Command Palette and select "Git: View History" to see a log of commits. You can explore changes made in each commit.
- **Revert Changes**: To revert changes made by a commit, right-click on the commit in the history log and select "Revert Commit" or "Reset Current Branch to Here" for more drastic rollbacks.

#### Git Integration Preferences

Customize your Git experience in VS Code by adjusting settings related to Git operations, such as enabling automatic fetching, configuring commit signing, and more through the settings menu (`File > Preferences > Settings`, then search for "Git").

By integrating Git directly into the development environment, VS Code makes version control more accessible and streamlined, allowing developers to focus more on coding and less on command-line operations.

### Live Share: Real-Time Collaborative Coding in VS Code

The Live Share extension for VS Code revolutionizes the way developers collaborate on code by allowing for real-time, interactive programming sessions across different machines and environments. This powerful tool supports a wide range of collaborative activities, from pair programming to large group code reviews, making remote collaboration seamless and efficient.

#### Getting Started with Live Share

1. **Install Live Share**: First, ensure you have the Live Share extension installed. You can find it by searching for "Live Share" in the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X` on macOS) and clicking **Install**.

2. **Start a Session**: Once installed, you can start a Live Share session by clicking on the Live Share icon in the status bar or by opening the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS) and selecting **Live Share: Start Collaboration Session**.

3. **Invite Collaborators**: After starting a session, Live Share generates a unique link that you can share with your collaborators. They can join your session by clicking on the link, which will open the shared project in their own VS Code environment.

#### Features of Live Share

- **Real-Time Editing and Debugging**: Participants can edit and debug code together in real time, with changes reflected across all participants' screens instantly.
- **Independent Navigation**: While you're collaboratively working on the same project, each participant can navigate the codebase independently, allowing for efficient multitasking.
- **Integrated Chat and Audio Calls**: Communicate directly within the session through the integrated chat or start an audio call to discuss the code verbally, facilitating clear and immediate communication.
- **Shared Terminals and Servers**: Share terminals and local servers with your collaborators, enabling them to run and test the code as if they were on the same machine.

#### Best Practices for Using Live Share

- **Code Together Efficiently**: Use Live Share for pair programming sessions, code reviews, or troubleshooting sessions to take advantage of multiple perspectives.
- **Maintain Communication**: Leverage the chat and audio call features to keep communication open and clear among participants, ensuring everyone is aligned on the task at hand.
- **Respect Privacy and Security**: Only share sessions with trusted collaborators and be mindful of sharing sensitive information during a Live Share session.

Live Share in VS Code breaks down geographical barriers and brings developers together in a shared coding environment. Whether you're working on a project with a distributed team, helping a student understand a concept, or troubleshooting code with a colleague, Live Share makes collaborative coding more accessible and interactive than ever before.

### Customization Tips

VS Code offers extensive customization options to tailor your development environment to your needs. Here are some ways to customize your workspace:

#### Customizing Settings

- **User and Workspace Settings**: Access settings by going to `File > Preferences > Settings` or using `Ctrl+,` (`Cmd+,` on macOS). You can customize everything from the theme, font size, and keybindings to editor behavior and code formatting options.

- **Themes**: Personalize your editor with themes by going to `File > Preferences > Color Theme`. VS Code offers a variety of built-in themes, and you can install more from the Extensions Marketplace.

- **Keybindings**: Customize keybindings by opening `File > Preferences > Keyboard Shortcuts`. You can modify existing shortcuts and add new ones to fit your workflow.

### Recommended Extensions

Here are some recommended and essential extensions for various development needs:

- **${chosenProgrammingLanguage}**: Provides rich support for the given language, including features like IntelliSense, linting, debugging, and more.
- **Live Share**: Enables real-time collaborative editing and debugging with teammates.
- **GitLens**: Supercharges the built-in Git capabilities, providing an enhanced visual representation of code authorship and history.
- **Prettier**: A code formatter that supports multiple languages and integrates with VS Code, ensuring consistent code style.
- **ESLint**: Integrates ESLint JavaScript into VS Code, helping to find and fix problems in your JavaScript code.
- **Remote - SSH**: Open any folder on a remote machine using SSH and take advantage of VS Code's full feature set.
- **HTML Boilerplate**: Create html boilerplate with ease.

### Community and Resources

The VS Code community is vibrant and supportive, offering a wealth of resources for learning and troubleshooting:

#### Official Documentation

- **[VS Code Docs](https://code.visualstudio.com/docs)**: The official documentation is a comprehensive resource covering everything from basic usage to advanced features (HIGHLY recommend looking at this).

#### Tutorials and Guides

- **[VS Code YouTube Channel](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA)**: Offers tutorials and updates on new features.
- **[Codecademy](https://www.codecademy.com/)**: Provides courses that integrate with VS Code, offering hands-on learning.
- **[FreeCodeCamp](https://www.freecodecamp.org/)**: A great source for tutorials that include working with VS Code for web development.
