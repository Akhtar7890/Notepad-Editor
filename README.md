**📝 Notepad Editor (Java Swing)**

A simple yet powerful Notepad Editor application built using Java Swing.
It provides basic text editing functionalities similar to Windows Notepad — including creating, editing, saving, and opening text files — with an easy-to-use graphical interface.

**🚀 Features**

* 🆕 **Create New File –** Start a new text document easily.
* 📂 **Open Existing File –** Load and edit any .txt file from your system.
* 💾 **Save File –** Save your work to an existing file or a new one.
* ✂️ **Cut, Copy, Paste, and Select All –** Full clipboard functionality.
* 🔍 **Find and Replace (optional) –** Search and modify text quickly.
* **🎨 Font Customization –** Change font size, style, and color.
* **❌ Exit Confirmation –** Prompt before closing unsaved work.
  

**🧰 Tech Stack**

| Component             | Description                                                       |
| --------------------- | ----------------------------------------------------------------- |
| **Language**          | Java                                                              |
| **GUI Framework**     | Java Swing                                                        |
| **IDE (Recommended)** | IntelliJ IDEA / Eclipse / NetBeans                                |
| **File Handling**     | Java I/O (BufferedReader, BufferedWriter, FileReader, FileWriter) |


**📁 Project Structure**
```  
NotepadEditor/
    ├── Notepad.java 
    ├── NotepadEditor.java
    ├── notepadIcon.png
    ├── README.md
```
Structure may vary depending on implementation.

**⚙️ How to Run the Project**

**1. Clone the Repository**
* git clone https://github.com/yourusername/NotepadEditor.git

**2. Open in Your IDE**

* Open the project in **IntelliJ IDEA, Eclipse**, or **NetBeans**.
* Ensure your IDE has **Java 8+** configured.

**3. Compile and Run**
* javac NotepadEditor.java
* java NotepadEditor

Or simply run the main class directly from your IDE.

**🔒 Error Handling & Validation**

* Prompts for unsaved changes before exiting or opening a new file.
* Displays error messages if file operations fail.
* Gracefully handles empty file selections or invalid inputs.

**💡 Future Enhancements**

* Add syntax highlighting for different file types.
* Implement auto-save functionality.
* Add word/character counter.
* Support multiple tabs (multi-document interface).

**👨‍💻 Author**

Mohammad Akhtar babu

