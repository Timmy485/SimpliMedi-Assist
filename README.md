# SimpliMedi-Assist


SimpliMedi-Assist is a Streamlit web app that simplifies medical reports for users. It offers an intuitive interface for uploading PDFs, DOCX, or TXT files. 
The app extracts text from these files and presents a customized preview for users to review.  <br></br>
Using OpenAI's GPT-3.5 model, SimpliMedi-Assist generates comprehensive explanations in two parts: <br>
Report Explanation breaks down the report's terms and findings, while Simplified Explanation offers plain English summaries tailored for non-medical users. <br>
Built on Streamlit, the app ensures a seamless user experience. SimpliMedi-Assist democratizes medical information, empowering users to understand their health reports efficiently and confidentially.

## Features

- Upload PDF, DOCX, or TXT files containing medical reports.
- Extract text from the uploaded documents.
- Preview the extracted text with custom HTML and CSS styling.
- Use OpenAI's GPT-3.5 model to generate explanations for the medical reports:
  - Report Explanation: Breaks down the medical report, explains the significance of terms, findings, and measurements.
  - Simplified Explanation: Provides a layperson-friendly summary of conditions, abnormalities, and their implications for health.

## Usage

1. Install dependencies:
 ```
 pip install streamlit requests PyPDF2 python-docx openai python-dotenv
```

2. Set up environment variables:
   - Create a .env file in the root directory.
   - Add your OpenAI API key to the .env file:
```
OPENAI_API_KEY=<Your_OpenAI_API_Key>
```

3. Run the Streamlit app:
 ```
 streamlit run app.py
 ```

4. Upload medical reports in PDF, DOCX, or TXT format.
5. View the extracted text and generated explanations.

## Dependencies
- Streamlit: For building the web application.
- Requests: For making HTTP requests.
- PyPDF2: For extracting text from PDF files.
- python-docx: For extracting text from DOCX files.
- OpenAI: For using the GPT-3.5 model.
- python-dotenv: For loading environment variables from a .env file.
