# 🐳 UnfollowX - Instagram Non-Followers Manager
<img width="1463" height="781" alt="Screenshot 2025-11-29 173530" src="https://github.com/user-attachments/assets/efda61be-8de3-4d0f-a43c-5c280fe8cf2d" />
<img width="1448" height="837" alt="Screenshot 2025-11-29 173758" src="https://github.com/user-attachments/assets/4c5194bc-a8e5-47a1-899f-e7a4e2c23c47" />

UnfollowX is a **professional Instagram account management automation tool** that helps you analyze your social connections by fetching:

* ✔️ Followers list
* ✔️ Following list
* ✔️ People who don't follow you back
* ✔️ Export results to CSV, JSON, and TXT formats
* ✔️ Unfollow non-followers automatically in safe timed batches
* ✔️ Smart login with saved session support

This tool uses the `instagrapi` library to communicate with Instagram APIs and avoid rate-limit blocks.

---

## 🚀 Features

| Feature                     | Description                                  |
| --------------------------- | -------------------------------------------- |
| Auto login & saved session  | Save login session to avoid repeated login   |
| Fetch followers & following | Accurate real username collection            |
| Identify non-followers      | People you follow but they don't follow back |
| Export data                 | CSV, JSON, TXT formats                       |
| Auto unfollow mode          | Batch unfollowing with smart delays          |
| Safe mode delays            | Helps avoid account bans                     |
| Professional UI             | Banner, themed colors, menus, animations     |

---

## 📦 Requirements

Make sure Python 3.8+ is installed in your system.

Install required packages using:

```bash
pip install -r requirements.txt
```

---

## 🛠 Installation

```bash
git clone https://github.com/AashishCyberH4CKS/UnfollowX.git
cd UnfollowX
pip install -r requirements.txt
python3 unfollow.py or python unfollow.py
```

---

## 🔑 Login

Supports login via:

* Username + Password
* Auto session reuse
* Optional 2FA verification

---

## 📊 Menu Options

```
1. Fetch Instagram Data
2. View Followers
3. View Following
4. View Non-Followers
5. Export Data
6. Unfollow Non-Followers
7. Refresh Data
8. Logout & Clear Session
0. Exit
```

---

## 📤 Data Export

Automatically generates files inside `exports/` folder:

| Format | Usage                          |
| ------ | ------------------------------ |
| .csv   | Table format, easy for Excel   |
| .json  | Structured data for developers |
| .txt   | Simple list display            |

---

## 🧠 Auto-Unfollow Logic

* Processes in **batches of 10**
* **10–15 seconds delay** between users
* **12 seconds delay** between batches

This mimics real human behavior to minimize ban risks.

---

## 📁 Folder Structure

```
UnfollowX
│   unfollow.py
│   requirements.txt
│   README.md
│   instagram_session.json
│
└── exports
    └── generated files
```

---

## 🤝 Contribute

Pull requests are welcome! For major changes, open an issue first to discuss improvements.

---

## ⚖️ Disclaimer

**Use at your own risk! This tool performs automation which may violate Instagram policies.**
Instagram may ban, restrict, or disable accounts that use aggressive automation.

> ⚠️ **Developer is not responsible for any account bans, limitations, or misuse of this tool.**

---

### 📌 Final Note

If you like this project, give it a ⭐ on GitHub and follow for more awesome tools!

**Created by : AashishCyberH4CKS** 🐳💻




