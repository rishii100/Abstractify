# Abstractify

This is a Streamlit-based web application focused on text summarization, providing users with a streamlined platform to generate concise summaries from either input text or uploaded PDF documents. Through a user-friendly interface accessible via web browsers, individuals can choose between two main options: "Summarize Text" or "Summarize Document." For the former, users input text directly into a provided text area, while for the latter, they upload PDF files for text extraction and summarization. Leveraging libraries such as txtai for text summarization tasks and PyPDF2 for PDF text extraction, the application processes the provided content to produce comprehensive summaries. 
## Architecture Design

![Architecture Design](https://github.com/rishii100/Abstractify/assets/98979613/4c612553-7254-4775-803a-c7d1f1f91cc3)

## Features

- **Summarize Text**: Users can input text directly into a text area and obtain a summary of the input text.
- **Summarize Document**: Users can upload a PDF document, and the app will extract text from it and provide a summary.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/Abstractify.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run Abstractify.py
    ```

2. Access the Streamlit app in your web browser at [http://localhost:8501](http://localhost:8501).

3. Choose between "Summarize Text" or "Summarize Document" from the sidebar, and follow the instructions provided on the app.

## Dependencies

- [Streamlit](https://streamlit.io/)
- [txtai](https://github.com/neuml/txtai)
- [PyPDF2](https://github.com/mstamy2/PyPDF2)

## Contributing

Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

