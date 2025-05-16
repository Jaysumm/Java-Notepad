📝 Java Swing Notepad Application
A feature-rich Notepad-like text editor built using Java Swing. This project demonstrates GUI development in Java, incorporating file operations, text formatting, background color customization, and clipboard functionality using Stack.

📌 Features
✅ File Menu
New: Start a new document.

Open: Open an existing .txt file.

Save: Save current file.

Save As: Save the current text with a new name.

Exit: Close the application.

✂️ Edit Menu
Copy to Stack / Cut to Stack / Paste from Stack: Custom clipboard functionality using a Stack<String>.

Standard Copy (Ctrl+C) / Cut (Ctrl+X) / Paste (Ctrl+V).

Time & Date: Inserts current time and date at the cursor location.

🛠️ Format Menu
Word Wrap: Toggle line wrapping on or off.

Font Styles: Choose from Arial, Comic Sans MS, and Times New Roman.

Font Sizes: Select from sizes 8, 12, 16, 20, 24, and 28.

🎨 Background Colour Menu
Change editor background to:

White

Black

Blue

🧰 Technologies Used
Java

Java Swing (JFrame, JTextArea, JScrollPane, JMenu, JMenuItem, etc.)

Event Handling (ActionListener)

File handling (FileReader, FileWriter)

Stack-based clipboard operations

Calendar (GregorianCalendar) for timestamp feature

📁 Project Structure
bash
Copy
Edit
📁 src/
  ├── GUI.java         # Main GUI class containing menu logic and setup
  ├── File.java        # Handles file operations (new, open, save, save as)
  ├── Edit.java        # Manages copy/cut/paste functionality with Stack
  ├── Format.java      # Manages word wrap, font style, and size
  └── Colour.java      # Handles text area's background color changes
▶️ How to Run
Compile the code:

bash
Copy
Edit
javac GUI.java
Run the program:

bash
Copy
Edit
java GUI
📸 Screenshots![image](https://github.com/user-attachments/assets/8a87d2f3-82ea-4b9b-a62a-45491bf2f785)
