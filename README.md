# Chat_with_pdf
![chat with gemini](https://github.com/abdulrauf1290/Chat_with_pdf/assets/126774164/f5ad4370-6e7d-4312-85a9-8c9be818de15)

# Chat with PDF

## Overview

The "Chat with PDF" project is a web application built with Flask that enables users to upload PDF files and query them to retrieve relevant information. Leveraging the Google Generative AI for language understanding and retrieval, this tool extracts text from uploaded PDFs, processes it to generate embeddings, and then searches for the most relevant documents based on user queries. Finally, it provides answers to the user's questions based on the extracted information from the PDF.

## Requirements

- Python 3.10
- Flask
- PyPDF2
- langchain
- Google Generative AI
- FAISS
- dotenv

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/chat-with-pdf.git
    ```

2. Navigate to the project directory:

    ```bash
    cd chat-with-pdf
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up your environment variables by creating a `.env` file in the project directory and adding your Google API key:

    ```bash
    GOOGLE_API_KEY=your_google_api_key_here
    ```

## Usage

1. Run the Flask application with the following command:

    ```bash
    python app.py
    ```

2. Access the application through your web browser at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

3. Upload a PDF file and enter your query related to the content of the PDF.

4. Click the submit button to retrieve the answer to your query.

## Notes

- Ensure that your PDF documents are properly formatted and contain searchable text. Scanned documents or images without OCR (Optical Character Recognition) may not yield accurate results.

- The tool utilizes Google Generative AI for language understanding and retrieval. Ensure that you have proper permissions and access to use the Google API.

- Feel free to customize and extend the tool according to your requirements. You can modify the user interface, improve the search functionality, or integrate additional features.

## Credits

This project utilizes Flask for web development, PyPDF2 for PDF processing, langchain for text splitting and embedding, Google Generative AI for language understanding, FAISS for vector storage and retrieval, and dotenv for environment variable management.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
