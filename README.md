# ATS Resume Expert

## Overview
ATS Resume Expert is a Streamlit-based web application that leverages Google's Gemini AI to analyze resumes against job descriptions. It provides insights into a candidate's profile, evaluates alignment with job roles, and offers recommendations for skill improvement. Additionally, it calculates the percentage match of a resume with a given job description.

## Features
- **Resume Analysis:** Get a professional evaluation of a resume against a job description.
- **Skill Improvement Suggestions:** AI-generated recommendations to enhance a candidate's skills.
- **ATS Compatibility Check:** Analyze resumes using an ATS scanner to assess keyword matches and job suitability.

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python
- **AI Model:** Google Gemini 1.5 Flash
- **File Processing:** pdf2image, PIL (Pillow)

## Installation
### Prerequisites
Ensure you have Python installed (>=3.7) and set up a Google API key for Generative AI.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ats-resume-expert.git
   cd ats-resume-expert
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the environment variable:
   - Create a `.env` file in the root directory and add:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```
5. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Enter the job description in the text area.
2. Upload a PDF resume.
3. Click one of the available buttons:
   - **Tell Me About the Resume**: Get AI feedback on strengths and weaknesses.
   - **How Can I Improve My Skills**: Receive step-wise skill enhancement suggestions.
   - **Percentage Match**: Get an ATS-based percentage match and missing keywords.

## File Structure
```
ats-resume-expert/
├── app.py  # Main application file
├── requirements.txt  # Required dependencies
├── .env  # API key storage (excluded from repo)
├── README.md  # Project documentation
```

## Dependencies
- `streamlit`
- `google-generativeai`
- `pdf2image`
- `Pillow`
- `python-dotenv`

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please reach out at [akshatsri2005@gmail.com](mailto:your-akshatsri2005@gmail.com).

