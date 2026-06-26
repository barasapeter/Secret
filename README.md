# **IDM Activator (Batch Script & GUI)**

[![Codeberg Repository](https://img.shields.io/badge/Codeberg-Repo-blue?logo=codeberg)](https://codeberg.org/oop7/IDM-Activator)
[![Gitflic Backup](https://img.shields.io/badge/Gitflic-Backup-green)](https://gitflic.ru/project/oop7/idm-activator)
![Platform](https://img.shields.io/badge/Platform-Windows-0078d7?logo=windows)
![Latest Release](https://img.shields.io/badge/Release-v5.0.2-blue)

IDM Activator provides tools to help users **test Internet Download Manager (IDM)** functionality by resetting the trial period. This allows for temporary access to evaluate premium features while encouraging license compliance through periodic resets, rather than permanent modification.

**This project now offers two versions:**

1.  **Modern Python GUI:** A user-friendly graphical interface built with Python and tkinter.
2.  **Original Batch Script:** The classic command-line version.

> **⚠️ Disclaimer**
> These tools are provided strictly for **educational and testing purposes only**. The developer does not endorse or condone software piracy in any form:
> - **Intended Use:** For analyzing trial limitation mechanisms and software evaluation.
> - **Support Developers:** Always purchase genuine software licenses for applications you use regularly.
> - **No Liability:** The developers assume no responsibility for any misuse of these tools or consequences thereof. Use at your own risk.

## **Table of Contents**

- [GUI Version (Recommended)](#gui-version-recommended)
  - [Features (GUI)](#features-gui)
  - [Compatibility (GUI)](#compatibility-gui)
  - [Running the GUI](#running-the-gui)
  - [Building the GUI (Optional)](#building-the-gui-optional)
- [Batch Script Version](#batch-script-version)
  - [Features (Script)](#features-script)
  - [Compatibility (Script)](#compatibility-script)
  - [Installation (Script)](#installation-script)
  - [Usage (Script)](#usage-script)
- [General Information](#general-information)
  - [Troubleshooting](#troubleshooting)
  - [BIN Files](#bin-files)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [Contact](#contact)

---

## ✨ **GUI Version**

The Python GUI provides a modern, easy-to-use interface for all activator functions.

*(Insert Screenshot Here - You can add a screenshot of the GUI later)*
<!-- ![GUI Screenshot](path/to/screenshot.png) -->

### 💪 **Features (GUI)**

- ✅ **Reliable Trial Reset:** Extends the IDM trial period for continued evaluation.
- ✨ **Modern User Interface:** Clean and simple graphical interface.
- 📂 **Automatic Path Detection:** Attempts to locate the IDM installation directory automatically using registry keys.
- ⌨️ **Manual Path Option:** Allows browsing for or manually entering the IDM installation path.
- ✨ **Version Compatibility Check:** Verifies that the installed IDM version matches the supported version before activating.
- 🛡️ **Automatic Backup:** Creates backups of `IDMan.exe` and relevant registry keys before making changes.
- 📑 **Extra File Type Support:** Option to add registry entries for additional file extensions recognized by IDM.
- 🔄 **Update Checker:** Connects to the Codeberg API to check if a newer version of the activator is available.
- 📦 **Self-Contained:** Uses resource files from the `src` folder.

### ⚙️ **Compatibility (GUI)**

-   **Requires Python 3.6+**.
-   Specifically tested and confirmed working with **Internet Download Manager**.

*Using the tool with other IDM versions that's not in the release changelog may lead to unexpected behavior or failure.*

### 🚀 **Running the GUI**

1.  **Download**: Get the `IDMActivator_GUI.zip` file from the [Releases Page](https://codeberg.org/oop7/IDM-Activator/releases/latest).
2.  **Extract**: Unzip the downloaded archive to a folder of your choice.
3.  **Check Python Installation**: Ensure Python 3.6+ is installed by opening a terminal and running `python --version`. If not installed or an older version, download and install from [https://www.python.org/downloads/](https://www.python.org/downloads/).
4.  **Run**: Open a terminal in the extracted folder and run `python main.py`.
5.  **Admin Rights**: The application requires Administrator privileges to function correctly (modifying Program Files and Registry). Run the terminal as administrator if prompted.
6.  **Verify Path**: Check if the automatically detected IDM path is correct. Use the **Browse...** button or edit the path if needed.
7.  **Use Buttons**: Click the buttons to perform actions:
    *   **Activate**: Resets the trial period.
    *   **Add Extra FileType Extensions**: Merges the extension registry data.
    *   **Check for Updates**: Checks if a newer version of the GUI is available online.
    *   **Exit**: Closes the application.

### 🏗️ **Building the GUI (Optional)**

If you want to build the GUI from the source code:

1.  **Prerequisites**:
    *   [Python 3.6+](https://www.python.org/downloads/) installed.
    *   Git (optional, for cloning).
2.  **Get the Code**:
    *   Clone the repository: `git clone https://codeberg.org/oop7/IDM-Activator.git`
    *   Or download the source code `.zip` from Codeberg.
3.  **Setup**:
    *   Open a terminal (Command Prompt, PowerShell, or Windows Terminal) in the project directory.
    *   Ensure `main.py` and `src` folder are present.
    *   No build required; Python scripts run directly.
4.  **Run**: Execute `python main.py`.

---

## 📜 **Batch Script Version**

The original command-line version is still available for users who prefer it.

### 💪 **Features (Script)**

- ✅ **Reliable Trial Reset:** Extends the IDM trial period for continued evaluation.
- 🛠 **Simple Menu-Driven Interface:** Easy to use via a command-line menu.
- 📂 **Automatic Path Detection:** Attempts to locate the IDM installation directory automatically.
- ⌨️ **Manual Path Option:** Allows specifying the IDM installation path if auto-detection fails or for non-standard installs.
- ✨ **Version Compatibility Check:** Verifies that the installed IDM version matches the supported version before proceeding.
- 🛡️ **Automatic Backup:** Creates backups of essential IDM files and registry keys before making changes.
- 📑 **Extra File Type Support:** Option to add registry entries for additional file extensions recognized by IDM.
- 💻 **Lightweight Script:** Minimal resource usage and fast execution.

### ⚙️ **Compatibility (Script)**

This script is specifically tested and confirmed working with:

-   **Internet Download Manager v6.43 Build 1**

*Using the tool with other IDM versions that's not in the release changelog may lead to unexpected behavior or failure.*

### 🛠️ **Installation (Script)**

Choose one of the following methods:

### **Method 1: Manual Download**

1.  **Download**: Get the latest release (`.zip` file containing the script and `src` folder) from the [Releases Page](https://codeberg.org/oop7/IDM-Activator/releases/latest).
2.  **Extract**: Unzip the downloaded archive to a folder of your choice (e.g., `C:\IDM-Activator`). Ensure the `src` folder is present alongside `script.bat`.

### **Method 2: PowerShell (Recommended)**

1.  **Open PowerShell as Administrator**:
    *   Right-click the Start menu -> select **Windows PowerShell (Admin)** or **Terminal (Admin)**.
    *   Confirm the User Account Control (UAC) prompt by clicking **Yes**.

2.  **Execute Download & Run Command**: Paste and run the following command in the Administrator PowerShell window:

    ```powershell
    # Downloads the zip, extracts it to the current directory, and runs the script
    $downloadUrl = "https://codeberg.org/oop7/IDM-Activator/releases/download/v5.0.2/IDM-Activator.zip"; # Ensure this URL points to the correct version
    $zipFile = "IDM-Activator.zip";
    $extractPath = ".";
    Invoke-RestMethod -Uri $downloadUrl -OutFile $zipFile;
    Expand-Archive -Path $zipFile -DestinationPath $extractPath -Force;
    cmd.exe /c ".\IDM-Activator\script.bat";
    Remove-Item $zipFile; # Clean up the downloaded zip file
    ```
    *(Note: Make sure the download URL in the command points to the desired release version.)*

### 💻 **Usage (Script)**

1.  **Run the Script**:
    *   Navigate to the directory where you extracted the files (e.g., `IDM-Activator-Script`).
    *   Double-click `script.bat`.
    *   The script will automatically attempt to request Administrator privileges. If prompted by User Account Control (UAC), click **Yes**.
    *   *If it doesn't elevate automatically, right-click `script.bat` and choose "Run as administrator".*

2.  **Automatic Checks & Backup**:
    *   The script will attempt to **automatically detect** your IDM installation path.
    *   It will perform a **version compatibility check**.
    *   If compatible, it will **back up** your original `IDM.exe` and relevant registry keys.
    *   If detection fails, you will be prompted to **enter the path manually**.

3.  **Follow On-Screen Menu**:
    *   Once the initial checks pass, a menu will appear:
        *   `1` to activate (reset trial) for Internet Download Manager.
        *   `2` to add extra FileType Extensions to the registry.
        *   `3` to check for updates (opens browser).
        *   `4` to exit.
    *   Choose an option by typing the number and pressing Enter.
    *   The script will provide feedback on the success or failure of the operation.

---

## 🌐 **General Information**

### ✅ **Troubleshooting**

*(Troubleshooting steps remain largely the same, ensure mentioning Admin rights for both versions)*

-   **Permission Denied / Access Denied**: Ensure you are running the application (`main.py` or `script.bat`) with **Administrator privileges**. These rights are needed to modify files in `Program Files (x86)` and write to the Registry.
-   **Script/GUI Doesn't Run / Errors**:
    *   **GUI**: Ensure [Python 3.6+](https://www.python.org/downloads/) is installed and `main.py` is executable.
    *   **Script**: Make sure all required files (`script.bat`, `src/*.*`) are present and in the correct locations relative to the script.
    *   Your antivirus might be interfering. Temporarily disable it (at your own risk) or add an exception for the executable/script/folder.
-   **IDM Path Not Detected**: If auto-detection fails:
    *   **GUI**: Use the **Browse...** button or type the path manually.
    *   **Script**: The script will ask you to provide the path.
    *   Ensure you enter the correct full path to the IDM installation directory (usually `C:\Program Files (x86)\Internet Download Manager`).
-   **Version Incompatibility Error**: If the tool reports an incompatible IDM version, you *must* install the supported version (**6.42 Build 1**) for it to work correctly.
-   **"Registered with a Fake Serial" Warning**: This often happens due to previous failed activation attempts or conflicting registry entries/host file blocks.
    1.  **Completely uninstall IDM.**
    2.  **Use a reputable third-party uninstaller**: Like [HiBitUninstaller](https://www.hibitsoft.ir/Uninstaller.html) to scan for and remove leftover registry keys, files, and folders related to IDM.
    3.  **Check your `hosts` file** (`C:\Windows\System32\drivers\etc\hosts`) for any entries blocking IDM servers and remove them.
    4.  **Restart your PC.**
    5.  **Reinstall the compatible IDM version (6.42 Build 1).**
    6.  **Run the activator (GUI or Script) again** *before* launching IDM.
-   **Restore Backup**: If activation causes issues, you can manually restore the backups created by the tool (usually stored in a `backup` subfolder within the tool's directory).

### 📄 **BIN Files**

These binary files contain the necessary data for the tool's functions. They are simple data files, **not encrypted**, and can be inspected by renaming their extension (e.g., `.txt`, `.reg`, `.exe`). In the Python GUI version, these files are located in the `src` folder alongside `main.py`.

-   `src/data.bin`: Contains a modified version of `IDM.exe` (based on Ali.Dbg's work) used for the trial reset mechanism.
-   `src/Registry.bin`: Contains the registry values (`.reg` format) needed to reset the IDM trial status.
-   `src/extensions.bin`: Contains registry entries (`.reg` format) to add support for extra file types within IDM.
-   `src/ASCII_art.txt`: (Used by script version only) Contains the ASCII art displayed in the script console.

### 📜 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### ℹ️ **Acknowledgments**

-   Special thanks to **Ali.Dbg** for the insights and modifications instrumental to this tool's core Activator functionality.

### ❓ **Contact**

For questions, bug reports, or suggestions, please open an issue on the [Codeberg repository](https://codeberg.org/oop7/IDM-Activator/issues).