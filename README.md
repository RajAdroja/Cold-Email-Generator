# Cold Email Generator

The Cold Email Generator is an AI-powered application designed to automate the creation of personalized cold emails. By leveraging advanced language models and natural language processing techniques, this tool streamlines outreach efforts, enhancing efficiency for business development and marketing teams.

## Features

- **Automated Email Generation**: Craft personalized cold emails tailored to specific industries and client needs using AI.
- **Customizable Templates**: Utilize and modify predefined templates to suit various outreach scenarios.
- **User-Friendly Interface**: Interact with the application through a simple and intuitive web interface built with Streamlit.
- **Integration with Language Models**: Employ advanced language models for natural language understanding and generation.
- **Job Description Integration**: Users can provide a link to a job description, and the model will generate a tailored email for that specific job. This significantly simplifies the process of sending cold emails for job applications or networking purposes.

## Technologies Used

- **Python**: The core programming language for the application.
- **Streamlit**: Framework for building the web-based user interface.
- **Advanced Language Models**: Utilized for generating human-like text based on prompts, including the Llama model (llama-3.1-70b-versatile).
- **Natural Language Processing (NLP)**: Techniques applied to understand and generate human language.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/RajAdroja/Cold-Email-Generator.git
   cd Cold-Email-Generator
   ```

2. **Create and Activate a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your API keys and other necessary configurations.

5. **Run the Application**:
   ```bash
   streamlit run app/main.py
   ```
   Access the application at `http://localhost:8501`.

## Usage

1. **Input Information**: Enter the necessary details such as the recipient's name, company, and any specific information to personalize the email.
2. **Generate Email**: Click the "Generate" button to create a personalized cold email based on the input provided.
3. **Provide Job Description**: Optionally, paste a link to a job description to generate an email tailored to that role.
4. **Review and Edit**: Review the generated email and make any necessary edits to ensure it aligns with your outreach goals.
5. **Send Email**: Copy the finalized email content and send it through your preferred email client.

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, please feel free to submit a pull request or open an issue in the repository.
