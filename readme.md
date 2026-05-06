# Project Report: Tunisia Heritage Quest

**Developed as a Jetpack Compose Android Application**  
**Date:** 2026-05-06

---

## Abstract
This report presents the *Tunisia Heritage Quest*, an interactive educational Android quiz application. Developed using Kotlin and Jetpack Compose, the app integrates modern MVVM architecture and navigation principles. It aims to test and expand the user's knowledge of Tunisian heritage, featuring categorized questions, customizable difficulty levels, and time-based challenges.

---

## 1. Introduction
The Tunisia Heritage Quest application is designed to offer an engaging way to learn about the rich historical and cultural heritage of Tunisia. The app supports various categories such as Roman, Islamic, and Punic sites. It allows users to configure their gameplay experience, providing options for difficulty adjustment and timer settings.

---

## 2. Application Architecture
The project employs modern Android development practices:

- **UI Toolkit:** Jetpack Compose for declarative and responsive UI design.  
- **Architecture Pattern:** Model-View-ViewModel (MVVM) to ensure robust separation of concerns.  
- **Navigation:** Jetpack Navigation component tailored for Compose, enabling smooth transitions between different screens (Splash, Menu, Category, Quiz, and Results).

---

## 3. User Interface and Features
The application consists of several primary screens, each designed for intuitive interaction.

### 3.1 Main Menu
The Main Menu serves as the central hub of the application. It prominently displays the app logo and title, *Tunisia Heritage Quest*, alongside buttons to start the quiz, view instructions, access settings, or exit the game. The clean layout ensures immediate access to core functionalities.

![Main Menu Screen](menu.png)

---

### 3.2 How to Play
To assist new users, the *How to Play* screen provides a straightforward, four-step guide:

1. **Select a Category:** Choose from various heritage sites.  
2. **Configure Your Game:** Adjust difficulty and timer settings.  
3. **Answer Questions:** Earn points for correct answers.  
4. **See Your Results:** Review final scores and performance feedback.

![How to Play Screen](how_to_play.png)

---

### 3.3 Settings Configuration
The Settings screen offers gameplay customization. Users can select the difficulty level (Easy, Medium, Hard) and toggle a 15-second timer for each question. These preferences are persistently managed to tailor the quiz experience to the user's liking.

![Settings Screen](settings.png)

---

### 3.4 Quiz Interface
The core of the application is the Quiz interface. It features dynamic content, including high-quality images of heritage sites, such as the amphitheater of El Jem. The UI displays the current question number, a countdown timer (if enabled), the question text, and multiple-choice options. An additional feature allows users to learn more via external links (e.g., Wikipedia).

![Quiz Interface](quiz.png)

---

### 3.5 Results and Feedback
Upon completing the quiz, the user is presented with the Results screen. It displays the total score (e.g., 50 points), the percentage of correct answers, and a personalized message based on their performance (e.g., "Good job! You know your history well."). Options to try again or return to the main menu are provided.

![Quiz Results Screen](results.png)

---

## 4. Conclusion
The Tunisia Heritage Quest successfully demonstrates the implementation of a fully functional, modular Android application using Jetpack Compose. By combining a modern, responsive user interface with customizable gameplay mechanics, it offers an effective and enjoyable educational tool for discovering Tunisia's historical sites.

---

## AI Usage
AI was used to correct syntax, enhance the overall design, and generate the quiz questions.
