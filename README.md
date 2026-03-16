# 📚 Marvellous Study Tracker (Java)

A simple console-based Study Tracking Application developed in Java that helps students record and manage their daily study activities.

The application allows users to log study sessions, view study history, generate summaries, and export study data to a CSV file for future analysis.

---

## 🧠 Project Overview

Marvellous Study Tracker is a command-line Java application designed to help students maintain discipline in their study routine.

The system records important details like:

📅 Study Date

📘 Subject Name

⏱ Study Duration (Hours)

📝 Study Description

It stores all logs in memory and allows users to view, analyze, and export study reports.

---

## ⚙️ Technologies Used

| Technology  |  Purpose |
|--------------|----------------------|
| ☕ Java | Core Programming Language |
| 📚 Java Collections (ArrayList, TreeMap)  | Data Storage & Summaries |
| 📅 LocalDate API | Handling Study Dates |
| 📂 FileWriter | Exporting data to CSV file |
| 🖥 Console I/O | User Interaction |

---

## 📖 Description

| Class  |  Descriptio |
|----------|---------------|
| StudyLog | Represents a single study session |
| StudyTracker | Handles all operations like insert study log, display log, export data,  Generate summaries |
|  Study_Track |  Main class containing program execution |


---

## 🚀 Features

✅ Add new study log

✅ View all study logs

✅ Export logs to CSV file

✅ Summary of total study hours by date

✅ Summary of total study hours by subject

✅ Simple menu-driven console interface

---

## 📊 Menu Options

When the program runs, the user sees the following menu:

1 : Insert new study log
<br>
2 : View all study log
<br>
3 : Export study log to CSV file
<br>
4 : Summary of study log by date
<br>
5 : Summary of study log by subject
<br>
6 : Exit the application

---

## 💻 How to Run the Project

## Compile the Program
javac Study_Track.java
## Run the Program
java Study_Track

## 📄 CSV Export Example

After exporting, a file MarvellousStudyTracker.csv will be generated.

Example:

Date,Subject,Duration,Description
<br>
2026-03-10,Java,2.5,OOP concepts practice
<br>
2026-03-10,Python,1.5,List comprehension

This file can be opened in:

•  Microsoft Excel

•  Google Sheets

•  LibreOffice

---

## 📈 Example Output
2026-03-14 | Java | 2.0 | Studied File Handling
<br>
2026-03-14 | Python | 1.5 | Practiced Functions

---

## 🔍 Functional Modules
📘 Study Log Management

Stores study session details including subject, duration, and description.

## 📊 Summary by Date

Calculates total study hours for each day.

## 📚 Summary by Subject

Calculates total study hours spent per subject.

## 📂 CSV Export

Exports all study logs to a CSV file for external analysis.

## 🛠 Java Concepts Used

•  Classes & Objects

•  Encapsulation

•  ArrayList Collection

•  TreeMap Collection

•  File Handling (FileWriter)

•  Date API (LocalDate)

•  Exception Handling

•  Menu Driven Programming

---

## 🎯 Learning Outcomes

•  This project demonstrates:

•  Java OOP design

•  File handling

•  Data structures usage

•  Real-world productivity tool development

---

## 👨‍💻 Author

### Aditya Dipak Shejwal
🎓 M.Sc Computer Science
