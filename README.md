# 🔐 Password Manager

A secure cross-platform desktop password manager built using Node.js and Electron.

This application encrypts stored passwords using the AES-256-GCM encryption algorithm and derives encryption keys from the master password provided by the user.

> ⚠️ This project was developed for educational purposes only.

---

## ✨ Features

* 🔒 AES-256-GCM password encryption
* 🧠 Master password-based key derivation
* 🎲 Random IV generation for every encryption operation
* 💻 Cross-platform desktop support
* ➕ Add and manage saved services/passwords
* 🔑 Change admin/master password
* 🗑️ Delete all stored passwords securely
* ⚡ Built with Electron + Node.js

---

## 🛠️ Tech Stack

* Node.js
* Electron
* HTML/CSS/JavaScript
* Materialize CSS
* Material Icons

---

## 📸 Application Screenshots

### Initial Setup

Set the admin/master password during first launch.

> Note: Passwords cannot be recovered if the master password is forgotten.

![Initial Setup](https://user-images.githubusercontent.com/26803384/91870733-abcee780-ec94-11ea-931c-56f74d1b9032.png)

---

### Login Screen

Authenticate using your master password each time the application starts.

![Login](https://user-images.githubusercontent.com/26803384/91870189-5eeb1100-ec94-11ea-9399-0c4f12094e6a.png)

---

### Home Dashboard

View saved credentials, add services, update password, or clear stored data.

![Dashboard](https://user-images.githubusercontent.com/26803384/91870539-9fe32580-ec94-11ea-9d5c-c3b71065e00c.png)

---

### Add New Service

Save credentials securely for any service/platform.

![Add Service](https://user-images.githubusercontent.com/26803384/91871132-c6a15c00-ec94-11ea-868d-60a5c5341bd3.png)

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/J-satvik/Password-Manager.git
cd Password-Manager
```

### Install Dependencies

```bash
npm install
```

### Run Application

```bash
npm start
```

---


---

## 🔐 Security Information

This application uses:

* AES-256 encryption in Galois/Counter Mode (GCM)
* Password-derived encryption keys
* Random Initialization Vector (IV) generation for each encryption process

> Best practice is to avoid storing passwords whenever possible. If passwords must be stored, they should always be encrypted securely.

---

## ⚠️ Resetting the Application

If the master password is forgotten, encrypted passwords cannot be recovered.

To reset the application:

1. Close the application
2. Delete the `.passMan.db` file
3. Restart the application

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

If you would like to contribute:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* Electron
* Node.js
* Materialize CSS
* Material Icons
