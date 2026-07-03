# 🚆 Real-Time Indian Railway PNR Status Checker

A Python-based application that fetches real-time Indian Railway PNR status using a Railway API. This project demonstrates how to integrate REST APIs with Python, send HTTP requests, process JSON responses, and display railway booking information in a user-friendly format.

The application communicates with a Railway API using the `requests` library, receives data in JSON format, converts it into Python dictionaries, and displays important travel details such as train information and passenger booking status.

This project was built as a learning project to understand:

- API Integration
- HTTP Requests
- JSON Parsing
- Python Dictionaries
- Error Handling
- Working with External Libraries
- 
## 🚀 Features

- Check real-time PNR status
- Fetch train details using API
- Display train name
- Display train number
- Show source station
- Show destination station
- Display chart preparation status
- Show passenger coach details
- Show berth information
- Show current booking status
- Simple command-line interface
- Error handling for failed API requests

---

## 🛠️ Tech Stack

- Python 3
- Requests Library
- REST API
- JSON
- RapidAPI

---

## 📂 Project Structure

```
PNR-Status-Checker/
│
├── pnr_checker.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/PNR-Status-Checker.git
```

Move into the project folder

```bash
cd PNR-Status-Checker
```

Install dependencies

```bash
pip install requests
```

or

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run the Python file

```bash
python pnr_checker.py

The program will ask for a PNR number.

Example
Enter PNR: 1234567890

## 🔑 API Configuration

This project uses a Railway API available on RapidAPI.

Replace the placeholder API key in the code:

```python
headers = {
    "x-rapidapi-key": "YOUR_API_KEY",
    "x-rapidapi-host": "YOUR_API_HOST"
}
```

with your own RapidAPI credentials.

> **Note:** Never upload your actual API key to GitHub.

---

## 📥 Example Output

```
Enter PNR: 1234567890

Train Name   : Rajdhani Express
Train Number : 12951
From Station : Mumbai Central
To Station   : New Delhi

PNR Status   : Chart Prepared

Passenger Details

Coach  : B2
Seat   : 32
Status : CNF
```

---

## 🧠 Concepts Learned

This project helped in understanding:

- Variables
- User Input
- Functions
- Dictionaries
- Nested Dictionaries
- Lists
- Loops
- Conditional Statements
- HTTP GET Requests
- REST APIs
- JSON Parsing
- Status Codes
- Error Handling
- Python Requests Library

---

## 📚 API Workflow

```
User enters PNR
        │
        ▼
Python Application
        │
        ▼
HTTP GET Request
        │
        ▼
RapidAPI
        │
        ▼
Railway API
        │
        ▼
JSON Response
        │
        ▼
Python Dictionary
        │
        ▼
Display Train & Passenger Details
```

---

## ⚠️ Common Errors

### 401 Unauthorized

- Invalid API Key
- API Subscription Missing

---

### 400 Bad Request

- Invalid PNR
- Missing Parameters
- Incorrect Request Format

---

### No Response

- Internet Connection
- API Server Down

---

## 🔮 Future Improvements

- GUI using Tkinter
- Web Version using Flask
- Streamlit Dashboard
- Save Search History
- SQLite Database Integration
- Export Results to PDF
- Search History
- Multiple Passenger Support
- Better Error Messages
- Logging
- Unit Testing

---

## 🤝 Contributing

Contributions are welcome.

If you would like to improve this project, feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational purposes.

---

## 👨‍💻 Author

**Arpit Saraswat**

Python Developer | Backend Development Learner | API Integration Enthusiast
