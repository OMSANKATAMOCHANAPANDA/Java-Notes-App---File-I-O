# Java Notes App - File I/O

## 📋 Description
This Java program is a simple command-line notes app using File I/O. It demonstrates how to:
- Write to a file using `FileWriter`
- Read from a file using `BufferedReader`
- Handle exceptions (IOException, FileNotFound)

## 🛠 Technologies Used
- Java
- FileWriter, FileReader, BufferedReader
- Exception handling

## 🚀 How to Run
1. Compile:
   ```
   javac NotesApp.java
   ```
2. Run:
   ```
   java NotesApp
   ```
   output:-
   ========
Microsoft Windows [Version 10.0.26100.4484]
(c) Microsoft Corporation. All rights reserved.

D:\ELEVATOR JAVA INTERNSHIP>javac NotesApp.java

D:\ELEVATOR JAVA INTERNSHIP>java NotesApp

===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Rath Yatra, also known as the Chariot Festival, is a major Hindu festival, particularly prominent in Puri, Odisha, India. It commemorates the annual journey of the deities Lord Jagannath, his brother Balabhadra, and sister Subhadra, from their temple to the Gundicha Temple. This procession involves pulling three massive, elaborately decorated wooden chariots through the streets, allowing devotees to witness and participate in the deities' journey. The festival is a celebration of unity, devotion, and the divine love of the deities.
Note saved successfully!

===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Vrindavan is a sacred city in India, renowned for its deep connection with Lord Krishna and its status as a major pilgrimage site for Hindus. It's believed to be the place where Krishna spent his childhood and performed various divine acts. The city is known for its numerous temples, spiritual atmosphere, and vibrant festivals like Holi and Janmashtami.
Note saved successfully!

===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: The Dwarkadhish Temple, also known as Jagat Mandir, is a revered Hindu temple dedicated to Lord Krishna, located in Dwarka, Gujarat. It is believed to have been originally built by Lord Krishna's great-grandson, Vajranabha, over Krishna's residence. The temple has been destroyed and rebuilt multiple times throughout history, with the current structure dating back to the 16th century.
Note saved successfully!

===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 2

--- Your Notes ---
- Rath Yatra, also known as the Chariot Festival, is a major Hindu festival, particularly prominent in Puri, Odisha, India. It commemorates the annual journey of the deities Lord Jagannath, his brother Balabhadra, and sister Subhadra, from their temple to the Gundicha Temple. This procession involves pulling three massive, elaborately decorated wooden chariots through the streets, allowing devotees to witness and participate in the deities' journey. The festival is a celebration of unity, devotion, and the divine love of the deities.
- Vrindavan is a sacred city in India, renowned for its deep connection with Lord Krishna and its status as a major pilgrimage site for Hindus. It's believed to be the place where Krishna spent his childhood and performed various divine acts. The city is known for its numerous temples, spiritual atmosphere, and vibrant festivals like Holi and Janmashtami.
- The Dwarkadhish Temple, also known as Jagat Mandir, is a revered Hindu temple dedicated to Lord Krishna, located in Dwarka, Gujarat. It is believed to have been originally built by Lord Krishna's great-grandson, Vajranabha, over Krishna's residence. The temple has been destroyed and rebuilt multiple times throughout history, with the current structure dating back to the 16th century.

===== Notes App =====
1. Write a Note
2. View Notes
3. Exit
Enter your choice: 3
Exiting Notes App...


## Features
- Append notes to a text file
- Read and display saved notes
- Uses try-with-resources to manage file streams

## 👨‍💻 Author
Om Sankata Mochana Panda
Submitted for Java Developer Internship Task 4
