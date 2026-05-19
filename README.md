# SAC-_NODE_EXPORTER
The **SAC Node Exporter** is a utility tool designed to streamline the process of exporting  specific node selections into external files. Instead of saving the entire Nuke script,  this tool allows you to save "snippets" as either `.nk` (Nuke script) or `.txt` (Text) files,  which can be easily shared, archived, or imported into other projects.



-----------------------------------------------------------
 Help Documentation: SAC Node Exporter (v1.0.0)

## Overview
The **SAC Node Exporter** is a utility tool designed to streamline the process of exporting specific node selections into external files. Instead of saving the entire Nuke script, this tool allows you to save "snippets" as either `.nk` (Nuke script) or `.txt` (Text) files, which can be easily shared, archived, or imported into other projects.

---

**INSTALLATION**
*   Just copy-paste into node graph and its good to go.  

 User Interface Controls

 1. Script Path Setup
*   **Get Script Directory :** 
    Automatically populates the **Export Path** field with the directory of your currently open Nuke script. 
    *Note: Your script must be saved to disk for this to work.*
*   **Export Path :** 
    The base directory where the exported files will be saved. You can manually browse for a path using the folder icon.
*   **File Name :** 
    Enter the desired name for your file (e.g., `Color_Grade_Setup`). Do not worry about adding extensions; the tool handles them automatically.

 2. Export Actions
The tool automatically creates a subfolder named **`Exported_Nodes`** within your chosen Export Path to keep your files organized.

*   **Export as .TXT :** 
    Saves the currently selected nodes as a `.txt` file. This is useful for copy-pasting node data into emails, chat apps (like Slack or Discord), or documentation.
*   **Export as .NK :** 
    Saves the selected nodes as a standard Nuke script file. This can be brought back into Nuke via `File > Import` or by dragging the file into the Node Graph.

 3. Utilities
*   **Open Exported Folder :** 
    Opens the file explorer (Windows Explorer, macOS Finder, or Linux Nautilus) directly to the `Exported_Nodes` directory.
