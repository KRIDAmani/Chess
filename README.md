# ♟️ Chess – Real-time Web Chess Game (Prototype)
![Game Interface Screenshot](interface_game.png)

![Made with Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-black?style=for-the-badge&logo=socketdotio&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Prototype in Progress](https://img.shields.io/badge/Status-Prototype_in_Progress-orange?style=for-the-badge)

Welcome to our **web-based chess game** built with HTML, CSS, JavaScript, and Node.js. The goal of this project was to create a dynamic and user-friendly interface for playing chess, with authentication, session management, and an attempted real-time multiplayer feature.

## 🚀 Features

- Full chessboard with piece movement
- Basic game logic and rules validation
- User authentication system
- SQLite database for user management
- Session and security management (Helmet, rate limiting, sanitize-html)
- Attempted implementation of real-time multiplayer with Socket.IO (incomplete due to time constraints)

## 🛠 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: SQLite
- **Real-time Communication**: Socket.IO
- **Security**: Helmet, Express Rate Limit, sanitize-html
- **Authentication**: bcrypt, express-session

## 📁 Project Structure

/Chess
├── front-end/ │ ├── accueil.html │ ├── game.html │ ├── accueil_script.js │ └── game.js 
├── back-end/ │ ├── server.js │ └── database.db
├── package.json └── README.md


## 📦 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KRIDAmani/Chess.git
   cd Chess ```

2. **Install dependencies**:
    ```npm install ```

3. **Run the server**:
  ```cd back-end
   node server.js```

4. **Access the game**: After running the server, open your browser and go to:
   ```http://localhost:3000/accueil.html```

## ⚠️ About Multiplayer

We planned to include a **real-time multiplayer mode** allowing two players to play on the same chessboard using **Socket.IO**.  
However, due to **limited time**, this feature wasn't fully implemented.

If you have experience in real-time multiplayer logic using **WebSockets** or **Socket.IO**, feel free to reach out — I’d love to discuss and learn more! 💬

---

## 👩‍💻 Author

**Amani Krid**  
🔗 [LinkedIn](https://www.linkedin.com/in/amani-krid-63aa3723a)  
📫 Contact: [kridamani.pro@gmail.com]

---

## 📄 License

This project is licensed under the **ISC License**.
