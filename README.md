# BizCardX: Extracting Business Card Data with OCR

## Overview

BizCardX is a Python-based tool designed to simplify the extraction of data from business cards using Optical Character Recognition (OCR). This project streamlines the process of digitizing business card information, making it efficient and user-friendly.

## Features

- **OCR Extraction:** Utilizes Optical Character Recognition to extract text data from business card images.
  
- **Output Organization:** Provides a structured and organized output format for the extracted information.

- **Image Format Support:** Supports various image formats commonly used for business cards.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed before using BizCardX:

- Python 3.x
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) (Ensure it's in your system's PATH)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/BizCardX.git
    cd BizCardX
    ```

2. Install required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Place business card images in the `images/` directory.
2. Run the following command:

    ```bash
    python extract_data.py
    ```

3. Extracted data will be saved in `output.csv` in the project directory.

## Configuration

Customize BizCardX by modifying settings in the `config.py` file. Adjust OCR settings, output format, or other parameters to suit your requirements.

## Contributing

We welcome contributions! If you'd like to contribute to BizCardX, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Thanks to the [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) project for providing the OCR engine.

## Support

For questions or issues, please open an [issue](https://github.com/your-username/BizCardX/issues).
