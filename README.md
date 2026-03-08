# AI Resume Critiquer

AI Resume Critiquer is an AI-powered web application that analyzes resumes and provides constructive feedback to help users improve them for job applications.

The application allows users to upload a resume file and receive AI-generated suggestions regarding resume clarity, skills presentation, and experience descriptions. Users can also specify a target job role so that the feedback is tailored to the type of job they are applying for.

The application is built using Python and Streamlit and uses the OpenAI API to generate intelligent resume analysis.

---

## Features

- Upload resumes in **PDF or TXT format**
- Extracts text automatically from uploaded resumes
- AI-generated resume feedback using the OpenAI API
- Feedback focused on:
  - Content clarity and impact
  - Skills presentation
  - Experience descriptions
- Optional **target job role input** for role-specific suggestions
- Simple and interactive **Streamlit web interface**
- Error handling for empty or invalid files

---

## Technologies Used

- **Python** – Core programming language
- **Streamlit** – Web application framework for UI
- **OpenAI API** – Generates AI-based resume analysis
- **PyPDF2** – Extracts text from PDF resumes
- **python-dotenv** – Manages environment variables securely
- **Git & GitHub** – Version control and repository hosting

---

## How the Application Works

1. The user uploads a resume file (PDF or TXT).
2. The application extracts the text from the uploaded file.
3. The extracted resume text is combined with a prompt requesting detailed analysis.
4. The prompt is sent to the OpenAI API.
5. The AI reviews the resume and generates structured feedback.
6. The feedback is displayed to the user within the Streamlit interface.

---

## Project Structure

```
AI-Resume-Critiquer
│
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
├── .env                  # Environment variables (not pushed to GitHub)
└── Screenshot.png        # Application preview
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/akshaythombarework/AI-Resume-Critiquer.git
cd AI-Resume-Critiquer
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate the environment.

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Environment Variables

This project requires an OpenAI API key.

Create a `.env` file in the root folder and add:

```
OPENAI_API_KEY=your_openai_api_key_here
```

This keeps your API key secure and prevents it from being uploaded to GitHub.

---

## Running the Application

Run the Streamlit app with:

```bash
streamlit run app.py
```

After running the command, the application will automatically open in your default browser.

---

## Example Workflow

1. Open the application in the browser.
2. Upload your resume file.
3. Optionally enter the job role you are targeting.
4. Click **Analyze Resume**.
5. The AI generates feedback and displays improvement suggestions.

---

## Future Improvements

Possible improvements for future versions include:

- Support for **DOCX resume files**
- Resume **ATS compatibility scoring**
- Job description matching
- Resume keyword analysis
- Downloadable feedback reports
- Improved UI design

---

## Author

Akshay Thombare

GitHub:  
https://github.com/akshaythombarework

---

## License

This project is licensed under the MIT License.
