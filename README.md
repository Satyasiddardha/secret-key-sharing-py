# Secret Key Sharing Web Application

A Flask-based web application that demonstrates various **secret sharing schemes** used in cryptography, including:

- **Shamir's Secret Sharing Scheme**
- **Blakley's Secret Sharing Scheme**
- **Mignotte's Secret Sharing Scheme**

These schemes allow a secret to be divided into parts (shares), giving each participant its own unique share. Only a certain threshold of shares is needed to reconstruct the original secret.

---

## What is Secret Sharing?

Secret sharing is a cryptographic technique where a secret (e.g., a password or encryption key) is split into pieces and distributed to multiple participants. Only when a **minimum number of pieces** are combined can the original secret be reconstructed.

---

## Features

- Interactive web interface to input and split a secret.
- Three cryptographic schemes implemented:
  - Shamir's
  - Blakley's
  - Mignotte's
- Visual display of:
  - Generated shares
  - Reconstructed secret
- Educational tool for learning and demonstrating secret sharing

---

## Technologies Used

- **Backend:** Python, Flask
- **Frontend:** HTML (with templates like `shamir.html`, `blakley.html`, `mignotte.html`)
- **Cryptography Logic:** Custom Python implementations in:
  - `shamir.py`
  - `blakley.py`
  - `mignotte.py`

---

## Project Structure

├── app.py # Flask application logic

├── shamir.py # Shamir's scheme implementation

├── blakley.py # Blakley's scheme implementation

├── mignotte.py # Mignotte's scheme implementation

├── requirements.txt # Python dependencies

├── vercel.json # Deployment config (for Vercel)

├── templates/

│ ├── homepage.html # Home page

│ ├── shamir.html # UI for Shamir's scheme

│ ├── result_shamir.html # Result for Shamir

│ ├── blakley.html # UI for Blakley's scheme

│ ├── result_blakley.html # Result for Blakley

│ ├── mignotte.html # UI for Mignotte's scheme

│ └── result_mignotte.html# Result for Mignotte


---


