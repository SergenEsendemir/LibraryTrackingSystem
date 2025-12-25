# Library Tracking System (Desktop)

![CSharp](https://img.shields.io/badge/C%23-.NET-green)
![WinForms](https://img.shields.io/badge/UI-Windows%20Forms-blue)
![Database](https://img.shields.io/badge/Database-MS%20Access-orange)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Status](https://img.shields.io/badge/Status-Demo%20Project-yellow)
![License](https://img.shields.io/badge/License-Not%20Specified-red)

A **Library Tracking System** desktop application developed using **C# (.NET Framework)** and **Windows Forms**, with **Microsoft Access** as the database.

This project provides a basic library automation workflow including book lending, user interactions, and page-based form navigation.

---

## 🧠 Overview

This project demonstrates:

- Desktop application development with **C# WinForms**
- Page-based navigation using multiple forms
- Library operations such as **book lending and tracking**
- Database integration using **MS Access**
- Separation of UI logic across multiple form pages

It is suitable for **educational purposes**, **practice projects**, and **small-scale library management demos**.

---

## ✨ Features

- 🔐 Login screen
- 🏠 Main page (dashboard)
- 📚 Book lending (Emanet Kitap)
- 🔄 Borrow / return tracking
- 🖼️ Icon and image-based UI
- 🗂️ Simple and user-friendly Windows Forms interface

---

## 🧰 Tech Stack

- **C#**
- **.NET Framework**
- **Windows Forms**
- **Microsoft Access (MDB / ACCDB)**
- **ADO.NET** for database operations

---

## 📂 Project Structure

```text
KutuphaneTakipProgrami/
├── Properties/                 # Project properties
├── bin/                        # Build outputs
├── obj/                        # Build intermediates
├── icons/                      # UI icons
├── resimler/                   # Images used in UI
├── Anasayfa.cs                 # Main page form
├── Anasayfa.Designer.cs        # Main page UI designer
├── Anasayfa.resx               # Main page resources
├── EmanetKitap.cs              # Book lending form
├── EmanetKitap.Designer.cs     # Lending UI designer
├── EmanetKitap.resx            # Lending resources
├── Giris.cs                    # Login form
├── Giris.Designer.cs           # Login UI designer
├── Giris.resx                  # Login resources
└── README.md
```

> The project follows a **classic Windows Forms structure**, where each page is represented by a separate `.cs` form file.

---

## 🗄️ Database

- Database technology: **Microsoft Access**
- Used for storing:
  - Book information
  - Lending records
  - User/login data
- Database connection is handled via **ADO.NET**
- Connection string is typically defined directly in the code or configuration

---

## 📌 Prerequisites

To run this project locally, you need:

- Windows OS
- Visual Studio 2019 or later
- .NET Framework installed
- Microsoft Access Database Engine

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/SergenEsendemir/LibraryTrackingSystem.git
   ```

2. **Open the solution**
   - Open the `.sln` file in Visual Studio

3. **Check Database Path**
   - Ensure the MS Access database file path is correct in the connection string

4. **Run**
   - Press **F5** or click **Start Debugging**

---

## 🎯 Purpose

This project was created to:

- Learn C# Windows Forms development
- Practice database integration with MS Access
- Understand form-based navigation
- Build a simple library automation system

It is a **learning-focused demo project**, not intended for production use.

---

## 🤝 Contributing

Contributions are welcome:

- UI improvements
- Code refactoring
- Database structure enhancements
- Feature extensions

---

## 👤 Author

**Sergen Esendemir**  
GitHub: https://github.com/SergenEsendemir

---

## 📄 License

No license is currently specified.  
You may add one if required (e.g., MIT License).
