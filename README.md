
---

# Image Text Extractor: A Flask-based OCR Application

## Overview

Image Text Extractor is a web application built using Flask that allows users to upload images and extract text from them using Optical Character Recognition (OCR) technology. This application leverages the power of Tesseract OCR to provide accurate text extraction from various image formats.

## Features

- **Image Upload**: Easily upload images from your local machine.
- **Text Extraction**: Extract text from uploaded images using Tesseract OCR.
- **Display Results**: View extracted text directly on the web interface.
- **Download Results**: Download the extracted text as a .txt file for future reference.

## Installation

### Prerequisites

- Python 3.6+
- `pip` (Python package installer)
- Tesseract OCR (Install [here](https://github.com/tesseract-ocr/tesseract))

### Clone the Repository

```bash
git clone https://github.com/your-username/image-text-extractor.git
cd image-text-extractor
```

### Install Dependencies

Install the required Python packages using `pip`:

```bash
pip install Flask Pillow pytesseract
```

### Set Up Tesseract

Make sure Tesseract is installed and accessible from your system's PATH. You can verify the installation by running:

```bash
tesseract --version
```

## Usage

### Run the Application

```bash
python app.py
```

### Access the Application

Open your web browser and go to `http://127.0.0.1:5000/`.

### Extract Text from Images

1. Upload an image from your local machine.
2. Click the "Extract Text" button.
3. View the extracted text on the results page.
4. Optionally, download the extracted text as a .txt file.

## Project Structure

```
.
├── app.py                 # Main Flask application
├── scrape_ebay.py         # eBay scraping script
├── templates
│   ├── index.html         # Home page template
│   └── results.html       # Results page template
└── README.md              # This README file
```

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with detailed descriptions of changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This application uses the [Flask](https://flask.palletsprojects.com/) web framework.
- The [Pillow](https://python-pillow.org/) library is used for image processing.
- [Tesseract OCR]((https://github.com/tesseract-ocr/tesseract))
