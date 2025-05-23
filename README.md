# FireBase
**Project Cost Tracker** is a simple web application that helps users manage project expenses by adding items and miscellaneous costs.  
It dynamically calculates and displays the total project cost, with data securely stored in Firebase Firestore under each user account.

### Project Overview
A video demonstration is provided to guide viewers through the entire project workflow. It explains how to access and navigate the project, showcasing each step involved in the process.(Recording.mp4)



## 📁 Project Structure

```
project-cost-tracker/
│
├── costmanager/
│   ├── index.html
│   ├── script.js
│   └── styles.css
│
├── login.html
├── login.js
├── register.html
├── register.js
└── styles.css
```

**Instructions**

## 🔐 **How to Use**

### 👉 **First-Time User (Registration)**
1. Open **`register.html`** in your browser.  
2. Fill in your **username(email)** and **password**.  
3. Click **Register** – this will create a new account using **Firebase Authentication**.  
4. After registering, you'll be **redirected** or prompted to **log in**.
![Screenshot 2025-05-23 142432](https://github.com/user-attachments/assets/8be3a807-2856-4a28-8f28-82f917527568)


### 👉 **Returning User (Login)**
1. Open **`login.html`** in your browser.  
2. Enter your **useraname(email)** and **password**.  
3. Click **Login**.
 ![Screenshot 2025-05-23 142353](https://github.com/user-attachments/assets/9d043856-1f4b-44ff-b9e7-78888dbf1d35)
  
4. You'll be redirected to the **Project Cost Manager dashboard** (`costmanager/index.html`) where you can:  
   - **Add** or **delete** items and other costs.  
   - View your **project’s total cost** in real-time.
 **Before adding items**
![image](https://github.com/user-attachments/assets/0c411ea1-d3b8-4b64-8271-32baf30b17de)
**After adding items**
![image](https://github.com/user-attachments/assets/46f3f771-068d-4d74-aa03-696c4a5ff5f4)



> ✅ **Note:** Ensure **Firebase is configured properly** and you are **connected to the internet**, as the app uses **Firebase Auth** and **Firestore**.



## **Firebase Images**
![Screenshot 2025-05-23 144114](https://github.com/user-attachments/assets/7c3b8c67-c0f1-4452-8a32-ec45270d6b73)
![image](https://github.com/user-attachments/assets/a701431a-7559-45db-94ab-8d25a3699404)


