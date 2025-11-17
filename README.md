# 🔐 Random Password Generator

This project is a simple and secure **Random Password Generator** built with HTML, CSS, and JavaScript. It creates strong 12-character passwords using a mix of:

- ✔️ Lowercase letters  
- ✔️ Uppercase letters  
- ✔️ Numbers  
- ✔️ Special characters  

The generator also includes a **copy-to-clipboard** feature. When the user clicks the copy icon, it temporarily transforms into a checkmark to confirm that the password has been successfully copied.

---

## 🚀 Features

- **Instant password generation**
- **Secure 12-character random output**
- **Copy button with visual feedback**
- **Clean and responsive UI**
- **Fully client-side (no data sent anywhere)**

---

## 🔢 Password Strength & Combinations

The character set contains:

- 26 lowercase letters  
- 26 uppercase letters  
- 10 digits  
- 8 special characters (`!@#$%^&*`)

**Total characters = 70**

Since a password is 12 characters long, the total number of possible combinations is:

### **70¹² ≈ 1.38 × 10²²  
(13 sextillion possible passwords)**

To put that into perspective:

Even if a computer guessed **1 billion passwords per second**, it would still take over:

### ⏳ **400,000 years**  
to try every possible combination.

---

## 🛡️ Security

- **High entropy:** Large character set + 12 characters = extremely difficult to brute-force.  
- **True randomness:** Each character is selected independently with JavaScript’s randomization.  
- **Client-side only:** Passwords are generated locally in your browser.  
  - No servers  
  - No logging  
  - Nothing is stored or transmitted  

This makes the tool safer than many online password generators.

---

## 📁 Technologies Used

- **HTML** – structure  
- **CSS** – styling  
- **JavaScript** – password logic + clipboard functionality  
- **Font Awesome** – icons

---

## 🖥️ Demo

You can try the password generator live here:  
*[Live](https://vamsi-kanakam.github.io/passwordGenerator/)*
