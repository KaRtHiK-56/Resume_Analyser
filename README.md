# Smart Resume Matcher: Leveraging Generative AI for Job Seekers

## Table of Contents
1. Introduction
2. Problem Statement
3. Problem Outline
4. Business Solution
5. Technical Solution
   - Architecture
   - Technologies Used
   - Workflow
6. Features
   - Percentage of Match
   - Profile Summary
   - Missing Keywords
   - Areas of Improvement
7. Use Cases
8. Future Work
9. Conclusion
10. References

## 1. Introduction
The Generative AI Resume Analyzer is an advanced tool designed to assist job seekers in tailoring their resumes to match specific job descriptions. By leveraging state-of-the-art generative AI models and a user-friendly interface, this application provides detailed insights and actionable recommendations to enhance the quality and relevance of a resume.

## 2. Problem Statement
Job seekers often struggle to align their resumes with the requirements and keywords specified in job descriptions. This misalignment can lead to missed opportunities, as resumes may not pass through automated Applicant Tracking Systems (ATS) or fail to capture the attention of hiring managers.

## 3. Problem Outline
- Difficulty in identifying relevant keywords from job descriptions.
- Lack of clarity on how well a resume matches a given job description.
- Uncertainty about specific areas of improvement in the resume.
- Time-consuming manual adjustments and revisions.

## 4. Business Solution
The Generative AI Resume Analyzer provides a comprehensive solution to the outlined problems by automating the process of resume analysis and comparison. The application:
- Analyzes the content of a resume against a job description.
- Highlights missing keywords and areas that need improvement.
- Provides a percentage match score to indicate how well the resume fits the job description.
- Offers a profile summary that aligns with the job requirements.

## 5. Technical Solution

### Architecture
The system architecture consists of the following components:
1. **Frontend**: Developed using Streamlit for a seamless and interactive user experience.
2. **Backend**: Python backend integrating various models and libraries.
3. **Generative AI Model**: Utilizes the Llama 3 model through LangChain for advanced natural language processing and generation.

### Technologies Used
- **Streamlit**: For developing the user interface.
- **Python**: Core programming language for backend development.
- **LangChain**: For managing the generative AI model and embedding techniques.
- **Llama 3**: The generative AI model used for text analysis and generation.

### Workflow
1. User uploads a resume and provides a job description.
2. The application preprocesses the text data from both documents.
3. The generative AI model analyzes the resume in the context of the job description.
4. Results are generated, including a match percentage, profile summary, missing keywords, and areas of improvement.
5. The user interface displays the results in an intuitive and detailed manner.

## 6. Features

### Percentage of Match
- Calculate the similarity score between the resume and job description.
- Display the percentage match to indicate how well the resume aligns with the job requirements.

### Profile Summary
- Generate a concise profile summary based on the job description.
- Highlight key skills and experiences that match the job requirements.

### Missing Keywords
- Identify and list keywords present in the job description but missing from the resume.
- Provide suggestions for incorporating these keywords into the resume.

### Areas of Improvement
- Highlight sections of the resume that need enhancement.
- Offer actionable recommendations to improve the quality and relevance of the resume.

## 7. Use Cases
- **Job Seekers**: Improve the quality of their resumes to match specific job descriptions.
- **Recruiters**: Quickly assess the suitability of resumes against job requirements.
- **Career Coaches**: Provide detailed feedback to clients on how to improve their resumes.

## 8. Future Work
- **Integration with Job Portals**: Allow users to directly upload job descriptions from popular job portals.
- **Advanced Analytics**: Implement deeper analytics for more nuanced insights.
- **Real-time Feedback**: Provide real-time suggestions and feedback as users edit their resumes.

## 9. Conclusion
The Generative AI Resume Analyzer is a powerful tool designed to bridge the gap between job seekers and job requirements. By leveraging advanced AI models and providing detailed feedback, the application enhances the chances of resumes passing through ATS and catching the attention of hiring managers.

## 10. References
- LangChain Documentation
- Streamlit Documentation
- Hugging Face Embedding Models
- Llama 3 Model Specifications and Documentation

## Acknowledgements

 - [Langchain](https://www.langchain.com/)
 - [Ollama](https://ollama.com/)
 - [Llama-3](https://ollama.com/library/llama3)


## Authors

- [@Github](https://www.github.com/KaRtHiK-56)
- [@LinkedIn](https://www.linkedin.com/in/l-karthik/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)


## Demo

https://github.com/KaRtHiK-56/Python_code_Explainer

https://www.linkedin.com/posts/l-karthik_generativeai-resumeanalyzer-jobsearch-activity-7217851332643209216-WOfa?utm_source=share&utm_medium=member_desktop


## Documentation

 - [Langchain](https://www.langchain.com/)
 - [Ollama](https://ollama.com/)
 - [Llama-3](https://ollama.com/library/llama3)

## Technology used

### Backend
- **LangChain:** For chaining together various AI models and processing workflows.
- **Llama 3 Model:** A state-of-the-art language model used for generating human-like text.
- **Python:** The primary programming language for implementing the application logic.

### Frontend
- **Streamlit:** An open-source app framework used for creating the web interface.

## Installation


### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/KaRtHiK-56/Resume_Analyser
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage Guide

1. **Launching the Application:**
   - Open a terminal and navigate to the project directory.
   - Run `streamlit run app.py`.
   - Open the provided URL in a web browser.
