# SMS Bomber Tool

This Python script automates sending multiple SMS requests to target phone numbers using publicly available APIs. It is designed for testing or stress-testing purposes only.

---

## ⚠️ Disclaimer

- **This tool is intended for educational and authorized testing purposes ONLY.**
- Unauthorized or malicious use to harass or spam individuals is **illegal** and unethical.
- The author is NOT responsible for any misuse or damages caused by this script.
- Use responsibly and ensure you have explicit permission before targeting any phone number.
- **Use this tool at your own risk.**

---

## Features

- Automatically fetches a list of APIs to send SMS requests.
- Validates Bangladeshi phone numbers starting with: `013`, `014`, `015`, `016`, `017`, `018`, `019`.
- Sends requests sequentially with customizable delay and count.
- Randomizes payload fields and User-Agent headers for each request.
- Provides colored terminal output for request status and errors.
- Supports command-line arguments or interactive input prompts.
- Limits maximum successful requests (threads) to 50.

---

## Requirements

- Python 3.7+
- Install dependencies with:

```bash
  pip install -r requirements.txt
```

---

## Usage

Run with command-line arguments:

```bash
python script.py --number 017XXXXXXXX --thread 20 --delay 1
```

Or run interactively without arguments:

```bash
python script.py
```

You will be prompted to enter:

* Phone number (Bangladesh format)
* Number of successful SMS requests to send (max 50)
* Delay between requests in seconds

---

## Important Notes

* Excessive or unauthorized use may lead to your IP or number being blocked by services.
* The tool depends on third-party APIs, which may change or become unavailable.
* Always test responsibly and ethically.

---

## Author

Mohammad Alamin — Backend Programmer
