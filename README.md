# Mobile_Number_validator
# 📱 Mobile Number Validator

A simple and responsive **Mobile Number Validator** built using **HTML, CSS, and JavaScript**. The project features a smartphone-inspired UI where users can enter a phone number using either the keyboard or the on-screen keypad and instantly check whether the number is valid. :contentReference[oaicite:0]{index=0}

---

## ✨ Features

- 📞 Smartphone-style dial pad interface
- ✅ Real-time phone number validation
- ⌨️ Supports keyboard input
- 🔢 Supports on-screen keypad input
- 📱 Responsive and clean user interface
- 🚀 Instant validation on pressing **Enter** or the **Call** button

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Font Awesome Icons

---

## 📂 Project Structure

```
Mobile-Number-Validator/
│── validator.html
│── style.css
│── script.js
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/mobile-number-validator.git
```

2. Open the project folder.

3. Double-click **validator.html** or open it in any modern web browser.

No additional installation is required.

---

## 📖 How It Works

The application validates different common phone number formats by checking:

- 10-digit numbers
- Numbers with country code (1)
- Numbers enclosed in parentheses
- Numbers containing spaces or hyphens

If the entered number matches the expected format, the application displays:

```
Valid phone number! 😃
```

Otherwise, it displays:

```
Invalid phone number! 😕
```

The validation logic is implemented in JavaScript using regular expressions and input processing. :contentReference[oaicite:1]{index=1}

---

## 📸 User Interface

The application includes:

- Phone display
- Number input field
- Numeric keypad
- Call button
- Validation result display

The interface is styled to resemble a modern smartphone dialer using CSS Grid, Flexbox, and custom styling. :contentReference[oaicite:2]{index=2}

---

## 📋 Supported Formats

Examples of valid inputs:

```
5555555555
555-555-5555
(555)555-5555
(555) 555-5555
1 555 555 5555
1(555)555-5555
```

Examples of invalid inputs:

```
5555
123**456789
2 (757) 622-7382
(6054756961)
555)-555-5555
```

---

## 🔮 Future Improvements

- International phone number support
- Copy-to-clipboard feature
- Dark/Light mode
- Phone number formatting while typing
- Country code selector
- Validation history

---

## 👨‍💻 Author

**Debalina Roy**

---

## 📄 License

This project is open source and available under the **MIT License**.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
