# Smart ATS - Resume Evaluation Tool

Smart ATS is a web application built with Streamlit that leverages AI technology to evaluate resumes based on a provided job description. It assists job seekers in improving their resumes by analyzing how well they match the job requirements and suggesting areas for improvement.

## Features

- **Resume Evaluation**: Users can upload their resume in PDF format and input a job description. The application then analyzes the resume and provides feedback on its match with the job description.
  
- **AI-Powered Analysis**: The application utilizes the Gemini-Pro generative AI model to evaluate resumes and provide detailed insights on their relevance to the job description.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/smart-ats.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables:

    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:

        ```plaintext
        GOOGLE_API_KEY=your-api-key
        ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2. Access the application in your web browser (by default, it runs on `http://localhost:8501`).

3. Paste the job description into the provided text area or upload it as a PDF file.

4. Upload your resume in PDF format.

5. Click the "Submit" button to initiate the evaluation process.

## Contributing

Contributions are welcome! If you'd like to contribute to Smart ATS, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Streamlit: [streamlit.io](https://streamlit.io)
- Google Generative AI: [Google AI](https://ai.googleblog.com/2021/10/advances-in-generative-models-ai-for.html)
