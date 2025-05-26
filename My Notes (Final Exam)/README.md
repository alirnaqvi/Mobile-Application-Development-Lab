# 📝 MyNotes - Note Taking App

A simple and elegant note-taking app built using **Flutter** with local data persistence via **sqflite**.  
This project was developed as the final lab exam for:

- **Course Title**: Mobile Application Development Lab  
- **Course Code**: CSL-341  
- **Date**: 26th May, 2025  
- **Faculty**: Mohsin Javaid Butt  
- **Student**: Syed Muhammad Ali Raza Naqvi  
- **Enrollment**: 01-134222-149

---

## 🔧 Features Implemented

### ✅ 1. Home Screen (8 Marks)
- Displays a scrollable list of all saved notes.
- Each note item shows:
  - Title
  - First 2 lines of the content
  - Timestamp
- Includes a Floating Action Button (FAB) to create a new note.
- Tapping on a note navigates to the edit/view screen.

### ✅ 2. Create and Edit Notes (8 Marks)
- A form screen to:
  - Create a new note
  - Edit an existing note (pre-filled data)
- Save button stores the note locally.
- Optional delete button to remove a note permanently.

### ✅ 3. Search Functionality (8 Marks)
- A search bar on the home screen filters notes in real-time by:
  - Title
  - Content

### ✅ 4. Persist Notes Locally (6 Marks)
- All notes are stored using `sqflite` (SQLite).
- Notes are preserved even after app restarts.

---

## 📦 Packages Used

| Package         | Version    | Description                   |
|-----------------|------------|-------------------------------|
| `sqflite`       | ^2.3.2     | SQLite database integration   |
| `path_provider` | ^2.1.2     | Access to device directories  |
| `path`          | ^1.9.0     | Path manipulation utilities   |

---

## 🖼 Screenshots

> 📌 Screenshots are included in the PDF report submitted along with this project.

---

## 📂 Project Structure

lib/
├── db/
│ └── notes_database.dart # SQLite database helper class for CRUD operations
├── models/
│ └── note.dart # Note data model class
├── screens/
│ ├── home_screen.dart # Home screen displaying list of notes with search functionality
│ └── note_detail_screen.dart # Screen to create or edit a note
└── main.dart # Application entry point

---

## 🚀 How to Run

1. Clone or download the repository  
2. Run `flutter pub get` to fetch dependencies  
3. Launch using any emulator or connected device:  
   ```bash
   flutter run


📎 GitHub Repository
🔗 [[My Notes (Final Exam)]](https://github.com/alirnaqvi/Mobile-Application-Development-Lab/tree/main/My%20Notes%20(Final%20Exam))

Syed Muhammad Ali Raza Naqvi
Enrollment: 01-134222-149
