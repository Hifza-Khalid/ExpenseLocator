# 💰 Expense Locator (EL) - Flutter App

Expense Locator (EL) is a smart **financial management** app built with Flutter. It helps users **track expenses, split costs with friends, and visualize financial data efficiently.** Whether you're managing daily spending or splitting costs, EL ensures **seamless and structured financial tracking.**

---

## 🚀 Features & Functionalities

### 1️⃣ **🖥 Splash Screen & Home Screen**
✅ Displays the **Expense Locator logo** for **5 seconds** before transitioning to the home screen.  
✅ The **Home Screen** greets the user dynamically:  
   **"Hello [Name], Welcome to Expense Locator!"**  
✅ Provides structured navigation to:
   - ➕ **Add Expenses**
   - 📜 **View Expense History**
   - 👥 **Split Expenses**

---

### 2️⃣ **📝 Expense Entry & Data Validation**
💡 Users can **add an expense** with the following details:
- 📌 **Title** (TextField with rounded corners)
- 🏷 **Category** (Dropdown: Food, Transport, Bills, Shopping, etc.)
- 💲 **Amount** (Numeric keyboard for easy input)
- 📆 **Date & Time** (Modern date picker)
- 👥 **Expense Sharing** (Checkbox for splitting preferences)
  
✅ Upon clicking the **curved "Save Expense" button**, the system:
- ✅ **Validates** input fields.
- ✅ Displays a **confirmation toast message**.
- ✅ Transfers data for **real-time processing**.

---

### 3️⃣ **📜 Expense List & Data Visualization**
📊 Organizes and displays **expense records** efficiently using **ListView & CardView**.  
Each entry includes:
- **📌 Expense Title**
- **🏷 Category**
- **💰 Amount Spent**
- **📅 Date & Time**
- **👥 Split Details** (if applicable)  

**✨ Enhances:**  
✔ **Financial tracking**  
✔ **Decision-making**  
✔ **User experience**

---

### 4️⃣ **🔢 Expense Splitting & Computation Models**
The app supports **two cost-sharing models** for easy **financial management**:

#### **🔹 Equal Split Model**
📌 **Formula:**  
Each User Pays = `Total Expense / 2`  
💡 **Example:** If the total expense is **PKR 100**, each user contributes **PKR 50**.

#### **🔹 Custom Percentage Split Model**
📌 **Formula:**  
- **User A Share** = `(User A Percentage / 100) * Total Expense`  
- **User B Share** = `(User B Percentage / 100) * Total Expense`  

💡 **Example:**  
If **User A contributes 70%** and **User B contributes 30%** of a **PKR 100** expense:  
✔ **User A pays:** **PKR 70**  
✔ **User B pays:** **PKR 30**  

**✨ Supports:**  
✔ **Fair cost distribution**  
✔ **Flexible expense-sharing**  
✔ **Adaptive financial planning**

---

## 🖥 **App Screens & Navigation**
### 📌 **Page 1: Add New Expense**
✅ **AppBar:** Title + Settings Icon  
✅ **Toggle Button:** Switch between **Expense** & **Income**  
✅ **Expense Form:**
- 📆 **Date Selector**
- 📜 **Dropdown (Category Selection)**
- 🔢 **Numeric Amount Input**
- ➕ **Expense Split Containers**  
✅ **Buttons:** ❌ **Cancel** | ✅ **Save**  
✅ **Bottom Navigation:** 🛎 Notifications | 💰 Income | 🏠 Home | 📋 More  

### 📌 **Page 2: Expense List**
✅ **AppBar:** Receipt Title + Settings Icon  
✅ **Search Bar** 🔍  
✅ **ListTile for Expense Entries** (Dynamically populated)  
✅ **Row with Action Buttons**  
✅ **Bottom Navigation:** 🛎 Notifications | 💰 Income | 🏠 Home | 📋 More  

---

## 📂 **Project File Structure**
```
ExpenseLocator/
│── android/
│── ios/
│── lib/
│   │── models/
│   │   ├── expense_model.dart
│   │   ├── split_expense_model.dart
│   │   ├── category_model.dart
│   │── screens/
│   │   ├── splash_screen.dart
│   │   ├── home_screen.dart
│   │   ├── add_expense_screen.dart
│   │   ├── expense_list_screen.dart
│   │   ├── split_expense_screen.dart
│   │── widgets/
│   │   ├── expense_card.dart
│   │   ├── expense_form.dart
│   │── utils/
│   │   ├── constants.dart
│   │   ├── helpers.dart
│── assets/
│── pubspec.yaml
│── README.md
```

---

## 🛠️ **Installation Guide**
### 🔹 **Prerequisites**
- ✅ Flutter SDK Installed
- ✅ Dart Installed
- ✅ Android Studio / VS Code
- ✅ Emulator or Physical Device

### 🔹 **Steps to Run the App**
1️⃣ Clone the repository:
   ```sh
   git clone https://github.com/Hifza-Khalid/ExpenseLocator.git
   cd ExpenseLocator
   ```
2️⃣ Install dependencies:
   ```sh
   flutter pub get
   ```
3️⃣ Run the app:
   ```sh
   flutter run
   ```

---

## 📌 **Usage Instructions**
- ➕ **Add Expenses** to track your spending.
- 📜 **View & Manage** past expenses.
- 👥 **Split Costs** efficiently using **Equal or Custom Split Model**.
- 📊 **Visualize Expenses** for better financial tracking.

---

## 👥 **Contribution Guidelines**
We welcome contributions to improve **Expense Locator**! 🚀

1️⃣ **Fork the Repository**  
2️⃣ **Create a Feature Branch**  
3️⃣ **Make Necessary Changes & Commit**  
4️⃣ **Push Changes & Open a Pull Request**  

📌 **Guidelines:**
- Follow **clean coding** practices.
- Write **meaningful commit messages**.
- Keep UI/UX **intuitive & user-friendly**.

---

## 📄 **License**
This project is licensed under the **MIT License**.

---

## 📞 **Contact & Support**
For any queries or support, feel free to reach out:  
📧 **Email:** hifzaofpk@.com  
🌐 **LinkedIn:** [Your Profile](https://linkedin.com/in/yourprofile)  
📌 **GitHub Repository:** [Expense Locator](https://github.com/Hifza-Khalid/ExpenseLocator)  
