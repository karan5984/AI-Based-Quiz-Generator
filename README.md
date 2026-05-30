# 🧠 AI-Based Quiz Generator

An AI-powered web application that automatically generates multiple-choice quizzes from a given topic or uploaded text document. The system uses the Groq API with the Llama 3.3 model to create intelligent, relevant, and difficulty-based quiz questions in real time.

---

## 📌 Features

* Generate quizzes from any topic
* Support for Easy, Medium, and Hard difficulty levels
* Upload text files to generate context-based questions
* AI-generated Multiple Choice Questions (MCQs)
* Automatic answer validation
* Instant score calculation and result display
* Clean and responsive user interface

---

## 🛠️ Technologies Used

### Backend

* Python
* Flask
* Groq API
* python-dotenv

### Frontend

* HTML5
* CSS3
* JavaScript

### AI Model

* Llama 3.3 70B Versatile

---

## 📂 Project Structure

```text
AI Base Quiz Generator/
│
├── app.py
├── .env
├── templates/
│   ├── index.html
│   ├── quiz.html
│   └── result.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
└── how to open this site.txt
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Based-Quiz-Generator.git
cd AI-Based-Quiz-Generator
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install flask groq python-dotenv
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
FLASK_SECRET_KEY=your_secret_key
```

Get your Groq API key from:

https://console.groq.com

---

## ▶️ Running the Application

Start the Flask server:

```bash
python app.py
```

You will see output similar to:

```text
Running on http://127.0.0.1:5000
```

Open the URL in your browser.

---

## 📖 How It Works

1. Enter a quiz topic.
2. Select the difficulty level.
3. (Optional) Upload a text file.
4. Click **Generate Quiz**.
5. AI creates 5 MCQ questions.
6. Answer the questions.
7. Submit the quiz.
8. View your score instantly.

---

## 🎯 Use Cases

* Student self-assessment
* Online learning platforms
* Competitive exam preparation
* Classroom quizzes
* Corporate training programs
* Knowledge evaluation

---

## 📸 Screenshots

Add screenshots of:

* Home Page
* Quiz Page
* Result Page

Example:

```text
screenshots/
├── home.png
├── quiz.png
└── result.png
```

---

## 🔮 Future Enhancements

* PDF and DOCX support
* User authentication
* Question history storage
* Timer-based quizzes
* Download quiz as PDF
* More question formats
* Performance analytics dashboard

---

## 👨‍💻 Author

Developed by **Karan**

If you found this project useful, consider giving it a ⭐ on GitHub.
