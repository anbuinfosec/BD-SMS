# 📱 BD-SMS

A Python-based SMS bombing tool for **Bangladeshi mobile numbers** — intended strictly for testing and educational purposes.

---

## ⚠️ Disclaimer

- ❌ **Do not** use for spamming, harassment, or illegal activities.
- ⚖️ The developer is **not responsible** for any misuse.
- ✅ Always ensure **explicit permission** before targeting any phone number.
- 🧠 Misuse may result in IP bans or legal consequences — use responsibly.

---

## ✅ Features

- 📞 Supports Bangladeshi numbers: `013`, `014`, `015`, `016`, `017`, `018`, `019`.
- 🔁 Sends SMS requests using public APIs (auto-updatable).
- 🔢 Custom thread count (up to 50 successful requests).
- 🕒 Configurable delay between requests.
- 🎭 Random User-Agent and payloads.
- 🧑‍💻 Interactive and command-line usage.
- 🌐 Auto-update API list with `--update`.

---

## 📲 Install on Termux

```bash
pkg update -y
pkg upgrade -y
pkg install python git -y
git clone https://github.com/anbuinfosec/bd-sms.git
cd bd-sms
pip install -r requirements.txt
````

---

## 🚀 Run the Tool

**Interactive Mode:**

```bash
python main.py
```

**Command-Line Mode:**

```bash
python main.py --number 017XXXXXXXX --thread 20 --delay 1
```

**Update APIs:**

```bash
python main.py --update
```

---

## 📦 Python Requirements

* Python 3.7+
* Install dependencies manually:

```bash
pip install requests fake-useragent
```

---

## 👨‍💻 Author

* **Name:** Mohammad Alamin
* 🐙 GitHub: [@anbuinfosec](https://github.com/anbuinfosec)
* 💬 Telegram: [@anbuinfosec\_official](https://t.me/anbuinfosec_official)
* 📘 Facebook: [Mohammad Alamin](https://www.facebook.com/anbuinfosec)

---

## ⭐ Support

If you find this tool useful:

* 🌟 Star the repo
* 🍴 Fork it
* 🔁 Share with ethical hackers

---

**© 2025 anbuinfosec — All rights reserved.**
