# TEXT-SUMMARIZATION-TOOL
*Company*:CODTECH IT SOLUTIONS
*Name*:Visha Jain
*Intern ID*:C0DF230
*Domain*:AI/ML
*Duration*:4 weeks
*Mentor*:Neela Santosh

# PEGASUS Text Summarizer

A sleek, AI-powered text summarization tool built with the PEGASUS model from Hugging Face and a modern Gradio interface. This application allows users to summarize articles or long texts with customizable settings, delivering concise and accurate summaries in an elegant, user-friendly UI.

*Features:*
Advanced Summarization: Leverages the google/pegasus-large model for high-quality text summarization.
Aesthetic UI: Modern, responsive interface with card-based design, gradients, and smooth animations, inspired by professional productivity apps
Customizable Parameters: Adjust max_input_length and max_output_length via sliders for tailored summaries.

*User-Friendly Features:*
Real-time word count display.
Sample article loader for quick testing.
Clear button to reset inputs and outputs.
Copy button for easy text copying.
Progress Feedback: Displays a progress bar and status messages during summarization.
Error Handling: Graceful handling of invalid inputs or processing errors.

*Requirements:*
Python 3.8+

*Required packages:*
transformers torch gradio

*Usage:*
Paste or Type: Enter your article in the input textbox or click "Load Sample Article" to test with a preloaded text.
Adjust Settings: Use sliders to set max_input_length (100–2048 tokens) and max_output_length (50–500 tokens).
Summarize: Click the "Summarize" button to generate a concise summary, displayed in the output textbox.
Clear: Click "Clear" to reset all fields.
Monitor: Word count updates in real-time, and status messages appear for errors or processing updates.




PEGASUS Text Summarizer
 
A sleek, AI-powered text summarization tool built with the PEGASUS model from Hugging Face and a modern Gradio interface. Developed as part of an internship project at CODTECH IT SOLUTIONS, this application enables users to generate concise, accurate summaries of articles or long texts through an elegant, user-friendly UI inspired by professional productivity tools.
Project Overview
This tool leverages the google/pegasus-large model to provide high-quality text summarization with customizable settings. The interface is designed with a card-based layout, smooth animations, and a responsive design, making it intuitive and visually appealing.
Developed by: Visha JainInternship Details:  

Company: CODTECH IT SOLUTIONS  
Intern ID: C0DF230  
Domain: AI/ML  
Duration: 4 weeks  
Mentor: Neela Santosh

Features

Advanced Summarization: Utilizes the google/pegasus-large model for precise and concise summaries.
Aesthetic UI: Modern, responsive interface with gradients, rounded components, and hover animations, inspired by apps like Notion and Medium.
Customizable Parameters: Adjust max_input_length (100–2048 tokens) and max_output_length (50–500 tokens) via sliders.
User-Friendly Features:
Real-time word count display.
Sample article loader for quick testing.
Clear button to reset inputs and outputs.
Copy button for easy text copying.


Progress Feedback: Displays a progress bar and status messages during summarization.
Error Handling: Gracefully manages invalid inputs or processing errors.

Screenshots
Modern interface with input, settings, and summary sections.
Requirements

Python 3.8 or higher
Required packages:transformers==4.38.2
torch==2.3.0
gradDonald==4.44.0



Installation

Clone the repository:
git clone https://github.com/your-username/text-summarization-tool.git
cd text-summarization-tool


Install dependencies:
pip install -r requirements.txt

Or install directly:
pip install transformers torch gradio


Run the application:
python pegasus_summarizer_ui.py


Access the UI at http://127.0.0.1:7860 in your browser.


Usage

Paste or Type: Enter your article in the input textbox or click "Load Sample Article" to test with preloaded text.
Adjust Settings: Use sliders to set max_input_length (100–2048 tokens) and max_output_length (50–500 tokens).
Summarize: Click the "Summarize" button to generate a summary, displayed in the output textbox.
Clear: Click "Clear" to reset all fields.
Monitor: Word count updates in real-time, and status messages appear for errors or processing updates.

Notes

Performance: The google/pegasus-large model is resource-intensive. A GPU is recommended for faster processing. For lighter usage, consider switching to google/pegasus-xsum by updating the model_name in pegasus_summarizer_ui.py.
Browser Support: Tested on Chrome, Firefox, and Safari.
Customization: Modify the CSS in pegasus_summarizer_ui.py for different styles or colors.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/your-feature-name).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature-name).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Hugging Face Transformers for the PEGASUS model.
Gradio for the intuitive UI framework.
CODTECH IT SOLUTIONS for providing the internship opportunity.
Mentor Neela Santosh for guidance and support.


