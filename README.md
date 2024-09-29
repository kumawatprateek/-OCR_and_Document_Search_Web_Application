# OCR and Document Search Web Application

This project is a **Streamlit** web application that allows users to upload images containing text in both Hindi and English, extract the text using **EasyOCR**, and perform keyword searches on the extracted text using a **TensorFlow** and **Huggingface Transformers** model.

## Features

- **OCR Functionality**: Extracts text from images using EasyOCR, supporting both Hindi and English.
- **Keyword Search**: Allows users to search for specific keywords within the extracted text, utilizing Huggingface Transformers' `distilbert-base-cased-distilled-squad` model for question-answering.
- **Simple Interface**: Streamlit-powered interface for easy interaction.


## Screenshots

### Home Page
![Home Page](./DemoImages/Home.jpg)

### Output Example
![Output Example](./DemoImages/output.jpg)

## Live Demo

You can access the live version of this app [here](https://ocranddocumentsearchwebapplication-tot3a5evkcegsscgdtpb2d.streamlit.app/).

## Linkedin Post Link [here](https://www.linkedin.com/posts/kumawatprateek_ai-ocr-nlp-activity-7246145305958641664-Z54e?utm_source=share&utm_medium=member_desktop).

## Installation

To run this project locally, follow the steps below.

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ocr-search-app.git
cd ocr-search-app
```

### 2. Set Up a Virtual Environment (Optional but Recommended)
```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install the required dependencies from the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

The dependencies include:
- `streamlit`: For the web interface.
- `easyocr`: To perform OCR on the uploaded images.
- `tensorflow`: TensorFlow backend for Huggingface models.
- `transformers`: For text processing and NLP functionalities.
- `pillow`: For image handling.
- `torch`: Required for Huggingface Transformers models.

### 4. Run the App
Run the Streamlit application:
```bash
streamlit run ocr_search_app.py
```

The app will start, and you can access it locally at `http://localhost:8501`.

## How to Use

1. **Upload an Image**: Upload an image containing text in Hindi and English (JPEG/PNG).
2. **Extract Text**: The app will automatically extract the text from the uploaded image.
3. **Keyword Search**: Enter a keyword to search for within the extracted text. The app will highlight the matching sections of the text using TensorFlow-backed question-answering models.

## Folder Structure

```
ocr-search-app/
│
├── ocr_search_app.py       # Main Streamlit app code
├── requirements.txt        # Dependencies file
└── README.md               # Project documentation (this file)
```

## Deployment

You can deploy this app for free on [Streamlit Community Cloud](https://share.streamlit.io/). Here’s how:

1. Push your project to a public GitHub repository.
2. Log in to Streamlit Community Cloud using your GitHub account.
3. Create a new app and link your GitHub repository.
4. Deploy the app and get a live URL to share.

## Dependencies

The application uses the following Python libraries:

- **streamlit**: For building the web app.
- **easyocr**: For Optical Character Recognition (OCR).
- **tensorflow**: For deep learning backend used by Huggingface Transformers.
- **transformers**: For NLP tasks like keyword search.
- **pillow**: For handling images.
- **torch**: PyTorch framework required by Huggingface Transformers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out:

- Email: kumawatprateek008@gmial.com
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/kumawatprateek/)
