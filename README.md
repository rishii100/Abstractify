# Abstractify
This is a simple Streamlit web application for text summarization using the txtai library. It allows users to either input text directly or upload a PDF document for summarization.

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

---

You may need to adjust the installation instructions or dependencies section based on your actual project structure and requirements. Also, make sure to include the appropriate license file (e.g., LICENSE) in your project directory.
