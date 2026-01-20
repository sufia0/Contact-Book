Nexus Contact Manager

A modern, robust, and user-friendly desktop application for managing personal and professional contacts. Built with Python and Tkinter, Nexus Contact Manager features a sleek dual-panel interface, dynamic profile avatars, and persistent local storage.

📸 Interface Preview

<img width="2871" height="1639" alt="Screenshot 2026-01-20 151503" src="https://github.com/user-attachments/assets/186ea959-1cdf-4598-ac75-c34a515cc92a" />


✨ Key Features

Modern UI/UX:

Dual-Panel Layout: A dark-themed sidebar for navigation and a clean, card-style profile view for details.

Dynamic Avatars: Automatically generates colorful circular avatars with initials for every contact.

Professional Styling: Custom color palette (Indigo/Slate), flat design buttons, and responsive layout.

Core Functionality:

CRUD Operations: Create, Read, Update, and Delete contacts effortlessly.

Comprehensive Details: Store Name, Phone Number, Email, and Physical Address.

Real-time Search: Filter contacts instantly by name or phone number via the sidebar search bar.

Data Persistence:

Auto-Save: All data is stored locally in a contacts.json file.

No Database Required: Lightweight JSON storage ensures your data persists between sessions without complex setup.

🛠️ Technical Stack

Language: Python 3.x

GUI Library: Tkinter (Standard Python library)

Data Handling: JSON, Pathlib

Utilities: UUID (Unique IDs), Random (Avatar colors)

🚀 Getting Started

Prerequisites

Ensure you have Python 3.6+ installed on your system.

Installation

Clone the repository:

git clone [https://github.com/sufia0/nexus-contact-manager.git](https://github.com/sufia0/nexus-contact-manager.git)
cd nexus-contact-manager


Run the application:

python contact_book.py


(Note for Linux users: If you encounter an error, ensure python3-tk is installed: sudo apt-get install python3-tk)

📂 Project Structure

nexus-contact-manager/
├── contact_book.py    # Main application source code
├── contacts.json      # Local storage (created automatically on first run)
├── screenshot.png     # Application screenshot for README
└── README.md          # Project documentation


📖 How to Use

Add a Contact: Click the + Create New Contact button in the sidebar. Fill in the details in the right-hand panel and click Save Details.

View/Edit: Click on any name in the sidebar list. The form will populate with their data. Edit any field and click Update Details.

Search: Type into the search bar at the top left. The list filters automatically as you type.

Delete: Select a contact and click the Delete Contact button. Confirm the dialog to remove them permanently.

🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

Developed with ❤️ using Python.
