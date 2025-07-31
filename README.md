# AI-Powered Resume and Cover Letter Generator

A Streamlit application that generates professional cover letters and resumes using Google's Gemini 2.5 Flash AI model.

## Features

- **Cover Letter Generator**: Create tailored cover letters based on your resume and job descriptions
- **Resume Generator**: Generate professional resumes with comprehensive sections
- **PDF Export**: Download generated documents as PDF or TXT files
- **AI-Powered**: Uses Google's Gemini 2.5 Flash for intelligent content generation

## Setup Instructions

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Get Google API Key
1. Go to [Google AI Studio](https://aistudio.google.com/)
2. Create a new API key
3. Copy the API key

### 3. Set Environment Variables
Create a `.env` file in the project root:
```
GOOGLE_API_KEY=your_google_api_key_here
```

### 4. Run the Application
```bash
streamlit run app.py
```

## Usage

1. **Cover Letter Generator**:
   - Upload your resume or paste resume text
   - Enter job description and company details
   - Adjust AI temperature for creativity
   - Generate and download your cover letter

2. **Resume Generator**:
   - Fill in personal information, experience, education, skills
   - Generate a professional resume
   - Download as PDF or TXT

## API Key Security

- API keys are stored in environment variables
- No logging or tracking of API keys
- Direct integration with Google's secure API

## Requirements

- Python 3.7+
- Google API key with Gemini access
- Internet connection for AI model access 
