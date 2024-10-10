# MCQ Generator using Gen AI 🤖

Welcome to the MCQ Generator project! This web application allows users to generate multiple-choice questions (MCQs) based on a given topic description. It utilizes Generative AI to create questions tailored to the specified complexity level and subject.

## Features ✨

- **File Upload**: Users can upload a `.txt` or `.pdf` file containing the topic description.
- **Dynamic Question Generation**: Specify the number of questions to generate.
- **Customization Options**: Input fields for subject title and complexity level.
- **User-Friendly Interface**: Built with Streamlit for an interactive experience.
- **Error Handling**: Robust error handling to ensure smooth operation.
- **Review Section**: Automatically generated review for the created MCQs.

## Requirements 📦

- Python 3.7+
- Streamlit
- Pandas
- dotenv
- Other dependencies defined in `requirements.txt`

## Setup Instructions 🛠️

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RaST-EDITH/GenAI_MCQ_Generator.git
   cd GenAI_MCQ_Generator
   ```

2. **Create a Virtual Environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Required Packages**:

   Make sure you have a `requirements.txt` file in your project directory. If it’s missing, you can create it with the required libraries.

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**:

   Create a `.env` file in the root directory and add your environment variables there.

5. **Run the Application**:

   Start the Streamlit application by running:

   ```bash
   streamlit run app.py
   ```

   This will launch the web app in your default browser.

## Directory Structure 📁

```
mcq-generator/
│
├── src/
│   ├── mcqgenerator/
│   │   ├── utils.py
│   │   ├── logger.py
│   │   └── MCQGen.py
│
├── Response.json
├── app.py
├── requirements.txt
└── .env
```

## Example Usage 📝

1. Upload a file containing the topic description.
2. Specify the number of questions, subject, and complexity level.
3. Click "Generate MCQs" to see the generated questions and review.

## 📎 Contact

If you have any questions or need assistance with the project, please don't hesitate to contact me at 

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raghvendra-singh-053977226)

We are here to help you stay organized and monitor your daily task progress effectively.