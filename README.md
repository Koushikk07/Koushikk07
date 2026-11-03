<h1 align="center">Gudapur Koushik</h1>
<p align="center"><b>Full Stack Developer | Node.js, MongoDB, MySQL | C++ & DSA</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/gudapurkoushik"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:gudapurkoushik52@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://leetcode.com/u/koushikk_7/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
</p>

---

CSE graduate (2026) building full-stack and backend applications with JavaScript, Node.js, MongoDB and MySQL, and practicing data structures and algorithms in C++ every day.

- 🎓 B.Tech in Computer Science & Engineering, Mahatma Gandhi University (2022 to 2026)
- 💼 MERN Stack Intern, Edunet Foundation in collaboration with EY GDS (Jan to Mar 2025)
- 🧩 356 problems solved on LeetCode (contest rating 1,487, 68-day max streak), 500+ across LeetCode and HackerRank
- 📍 Based in Telangana, open to relocation
- 🔎 Open to Software Developer and Full Stack roles

---

### 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | `C++` `JavaScript` `SQL` `Java (basics)` |
| **Frontend** | `HTML5` `CSS3` `React.js` `Bootstrap` `Tailwind CSS` |
| **Backend** | `Node.js` `Express.js` `REST APIs` `JWT` `Nodemailer` |
| **Databases** | `MongoDB (Mongoose)` `MySQL` |
| **Tools & Deployment** | `Git` `GitHub` `Postman` `MongoDB Atlas` `Render` `VS Code` |

---

### 📌 Projects

#### 🏦 Backend Ledger: Bank Transaction API ⭐
A REST API for banking-style money transfers built on a **double-entry ledger**. Balances are never stored; they are calculated from immutable credit and debit entries.
- 8 REST endpoints across 5 MongoDB collections, deployed on Render with MongoDB Atlas
- Balance calculated with a MongoDB **aggregation pipeline** (`$match`, `$group`, `$cond`)
- **Idempotency keys** and atomic **MongoDB transactions**, so a transfer either fully succeeds or does not happen, and retries never charge twice
- JWT authentication, bcrypt hashing, a TTL-indexed token blacklist for logout, a system user for funding accounts, and account-ownership checks
- Nodemailer (Gmail OAuth2) email alerts for registration and transfers
- Tested with Postman; full API reference, data model and design decisions in the README
- **Tech:** Node.js, Express.js, MongoDB, Mongoose, JWT, Nodemailer, Postman
- 🔗 [Source code](https://github.com/Koushikk07/Bank-Transaction-System) | 🌐 [Live API](https://bank-transaction-system-4qad.onrender.com) *(free tier, the first request can take about a minute)*

#### 🏨 Hostel Management System
Web app for managing hostel admissions, rooms, fees and complaints, with separate admin and student logins.
- Built a Node.js REST API with a 12-table MySQL database
- Admin can approve or reject applications, add rooms, allocate rooms, track room status and manage fees
- JWT and session-based authentication, bcrypt password hashing, and account lockout after repeated failed logins
- Nodemailer for email notifications
- **Tech:** HTML, CSS, JavaScript, Node.js, Express, MySQL
- 🔗 https://github.com/Koushikk07/Hostel-Managment-System

#### 🤖 Learning Style Identification (ML)
Predicts student learning styles using semi-supervised self-training with an SVM classifier.
- Trained and evaluated the model on the data_fs1.csv dataset
- **Tech:** Python, Scikit-Learn, Pandas
- 🔗 https://github.com/Koushikk07/Learning-Style-Identification-using-semi-supervised-self-taught-labeling

#### 🍳 Recipe Sharing Platform
React app for browsing, searching and filtering recipes.
- **Tech:** JavaScript, React, CSS
- 🔗 https://github.com/Koushikk07/recipe-sharing-platform

---

### 🏆 Achievements
- LeetCode 50 Days and 100 Days Badges (2026)
- Participant, Chainlink Hackathon: built a blockchain-integrated web concept and earned community rewards
- Participant, National Summer Hackathon 2026 (SkillStation)
- Meta Front-End Developer Capstone (Coursera)

---

### 🌱 Currently
- Extending Backend Ledger with transaction history and summary endpoints using aggregation
- Learning TypeScript and planning a React frontend for the Ledger API
- Solving more Medium-level problems in C++ (graphs and dynamic programming)
- Preparing for software developer roles

<p align="center">
  <img src="https://streak-stats.demolab.com?user=koushikk07&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>
