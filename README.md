# LangMultiPDF
Be able to have Conversations about any user-uploaded PDF, by breaking down the PDF into data, so that a Language model can learn,analyze, and provide discourse over the PDF.You can upload multiple PDFs at once as well.

## Installation
Download all dependencies with "pip install -r requirements.txt"

## Setup
1. Create a .env file in the root directory

Make sure you change the .env with your own API keys

## How to use

1. Run the app with "streamlit run app.py"
2. Upload a PDF file
3. Wait for the model to process the PDF
4. Ask questions about the PDF
5. Wait for the model to answer the question
6. Repeat steps 4 and 5
7. Upload another PDF file

## How it works
1. The PDF is converted to text using the pdfminer library
2. The text is cleaned and split into sentences
3. The sentences are passed to the model, which generates a response
4. The response is returned to the user
5. The user can ask another question, and the process is repeated
6. The user can upload another PDF, or multiple at once, and the process is repeated



## Reference
All thanks to the original author of this project: **alejandro-ao**
The code is taken from his project: https://github.com/alejandro-ao/ask-multiple-pdfs

## License
[MIT](https://choosealicense.com/licenses/mit/)

