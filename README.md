# Text-Encryptor
🛡️ Text Encryptor – Java Swing GUI

A desktop application that performs text encryption using a custom Caesar-Cipher–based shifting algorithm. Designed with Java Swing and AWT, the tool provides a simple, clean interface for encrypting any ASCII text.

🚀 Features

Caesar Cipher–based Encryption
Shifts each character by a user-defined value (0–94) within the ASCII printable range.

Interactive GUI (Java Swing)
Easy-to-use interface with fields for plain text, shift value, and encrypted output.

Input Validation
Detects invalid or special characters and displays helpful error messages.

Utility Buttons

Encrypt – Generates encrypted text.

Clear – Resets all fields.

Exit – Closes the application.

Prevents Crashes
Handles empty inputs, invalid numbers, and non-ASCII characters.

🧩 Tech Stack

Java

Java Swing

Java AWT

📌 How It Works

Enter your plain text.

Enter an integer shift value.

Click Encrypt to generate the encoded output.

The algorithm converts each ASCII character (32–126) and applies:

encrypted_char = (ASCII - 32 + shift) % 95 + 32



📦 Running the Project

Clone the repository:

git clone <your_repo_url>


Open the project in any Java IDE (NetBeans / IntelliJ / Eclipse).

Run the Text_Encryptor.java file.

📄 License

Free to use, modify, and learn from.
