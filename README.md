# -Smart-Study-Buddy
AI-powered Smart Study Buddy built with Python, Streamlit, LangChain, and Google Gemini. Generates topic explanations, simple and real-life examples, 5 MCQs, 5 interview questions, and summaries based on the selected difficulty level.
# 📚 Smart Study Buddy

An AI-powered study assistant built using Streamlit, LangChain, and Google Gemini. It helps students generate complete study material on any topic according to their selected difficulty level.

## 🚀 Features

- **Topic-Based Learning:** Enter any topic to generate study material.
- **Difficulty Levels:** Choose Easy, Medium, or Hard.
- **AI-Generated Explanation:** Get a detailed explanation of the selected topic.
- **Simple Example:** Understand concepts with an easy example.
- **Real-Life Example:** Learn how the topic is used in real-world situations.
- **MCQs:** Generate 5 multiple-choice questions with options and correct answers.
- **Interview Questions:** Generate 5 interview questions for practice.
- **Summary:** Get a concise summary in bullet points.
- **Interactive UI:** Simple and user-friendly interface built with Streamlit.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Streamlit | Web application interface |
| LangChain | Prompt management and LLM integration |
| Google Gemini | AI-powered study material generation |
| python-dotenv | Environment variable management |

## 📂 Project Structure

```text
Smart-Study-Buddy/
│
├── Smart_study_budy.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Smart-Study-Buddy.git
cd Smart-Study-Buddy
```

### 2. Create a Virtual Environment

```bash
python -m venv env
```

Activate the environment:

**Windows:**

```bash
env\Scripts\activate
```

**Mac/Linux:**

```bash
source env/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Google Gemini API Key

Create a `.env` file in the project folder and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_google_api_key
```

Replace `your_google_api_key` with your actual API key.

### 5. Run the Application

```bash
streamlit run Smart_study_budy.py
```

The application will open in your browser.

## 📖 How to Use

1. Open the Smart Study Buddy application.
2. Enter a topic in the input field.
3. Select a difficulty level: Easy, Medium, or Hard.
4. Click on **Generate Study Material**.
5. View your explanation, examples, MCQs, interview questions, and summary.

## 🎯 Use Cases

- Students preparing for exams.
- Beginners learning new technical concepts.
- Students preparing for interviews.
- Quick revision of important topics.
- Self-paced learning and practice.

## 🔮 Future Improvements

- Download generated study material as PDF.
- Add a quiz mode with score tracking.
- Save previous study sessions.
- Add support for multiple languages.
- Include topic recommendations based on user interests.

## 👨‍💻 Author

Lakshay

## 📄 License

This project is created for educational and learning purposes.
