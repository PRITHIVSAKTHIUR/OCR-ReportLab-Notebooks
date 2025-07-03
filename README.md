# **OCR-ReportLab**

> [!note]
**OCR-ReportLab** is a collection of Colab notebooks designed to perform Optical Character Recognition (OCR) on images and generate DOCX or PDF documents containing both the original image and the extracted text. It supports multiple state-of-the-art vision-language models for experimentation and practical use.

## Notebooks

You can launch and run the following notebooks directly in Google Colab:

- **Nanonets OCR:** [Open in Colab](https://colab.research.google.com/drive/1VvA-amvSVxGdWgIsh4_by6KWOtEs_Iqp)
- **Monkey OCR:** [Open in Colab](https://colab.research.google.com/drive/1vPCojbmlXjDFUt06FJ1tjgnj_zWK4mUo)
- **OCRFlux 3B:** [Open in Colab](https://colab.research.google.com/drive/1TDoCXzWdF2hxVLbISqW6DjXAzOyI7pzf)
- **Typhoon OCR:** [Open in Colab](https://colab.research.google.com/drive/1_59zvLNnn1kvbiSFxzA1WiqhpbW8RKbz)
  
## Features

- Extracts text from input images using various OCR models
- Embeds the image and extracted text into DOCX or PDF formats
- Designed for quick deployment via Google Colab

## Supported Models

The repository currently supports the following OCR implementations:

- **Nanonets OCR**
- **Monkey OCR**
- **OCRFlux 3B**
- **Typhoon OCR 3B**

## Installation

No installation is required. Simply click on the links above to run the notebooks in Google Colab. Make sure to upload your image file(s) when prompted and follow the instructions in the notebook.

## Dependencies

The notebooks are built using:

- Python
- PyTorch
- Hugging Face Transformers
- ReportLab
- Gradio (for UI)
- (Qwen2.5-VL based)

All dependencies are automatically installed in the Colab environment.

## Author

Created and maintained by [PRITHIVSAKTHIUR](https://github.com/PRITHIVSAKTHIUR)
