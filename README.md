# 📊 AI-Powered Smart Budgeting App

### 💰 AI-driven expense tracking & budgeting app built with Flutter, NestJS (GraphQL), and Firebase.

## 📖 Overview

The **AI-Powered Smart Budgeting App** helps users track their expenses, categorize transactions automatically using AI, and visualize their financial health through interactive charts. Users can link their bank accounts securely and manage their budget efficiently.

This project is **fully open-source** and built to showcase best practices in **Flutter (BLoC, GraphQL, Firebase)** and **NestJS (GraphQL API, PostgreSQL, Firebase Auth).**

---

## 🚀 Features  

✅ **Secure Authentication** – Firebase Auth (Google Sign-in)  
✅ **Bank Account Linking** – Integrate with Plaid API / Rwanda’s FinTech APIs  
✅ **AI-powered Expense Categorization** – Machine learning-based expense tracking  
✅ **GraphQL Backend** – Fast, scalable API for transactions & analytics  
✅ **Data Visualization** – Beautiful charts & graphs for financial insights  
✅ **Cloud Storage** – Secure data storage with PostgreSQL & Firebase  

---

## 🛠 Tech Stack  

### 🖥 Frontend:  
- **Flutter** (State Management: BLoC)  
- **GraphQL Client** (for API integration)  
- **Flutter Charts** (for data visualization)  

### 🖥 Backend:  
- **NestJS** (GraphQL API)  
- **PostgreSQL** (Database)  
- **Firebase Auth** (for authentication)  
- **Docker** (for containerized deployment)  

### ⚙ DevOps:  
- **GitHub Actions** (CI/CD for automated testing & deployment)  
- **Docker** (Containerized environment for the backend)  

---

## 📂 Project Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/ai-budgeting-app.git
cd ai-budgeting-app
```
### 2️⃣ Install Flutter Dependencies
```sh
    flutter pub get
```
### 3️⃣ Set Up Firebase
- Create a Firebase project on Firebase Console
- Enable Firebase Authentication and set up Google Sign-In.
- Download the required config files:
    - For Android: google-services.json → place it in android/app/
    - For iOS: GoogleService-Info.plist → place it in ios/Runner/

