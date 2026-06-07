# Empowering Blind Individuals – Image & PDF to Audio Converter

## Overview

Empowering Blind Individuals is an AI-powered accessibility project designed to help visually impaired users access information from images and PDF documents through audio. The system extracts textual and visual information, enhances the content using Generative AI, and converts it into speech, making educational and digital resources more accessible.

## Features

* Extracts text from images using Tesseract OCR.
* Extracts text and images from PDF documents.
* Generates captions for non-textual images using BLIP.
* Enhances extracted content with GPT-based text generation.
* Converts processed text into natural-sounding speech using Google Text-to-Speech (gTTS).
* Supports educational materials, textbooks, research papers, and image-based documents.
* Provides an end-to-end accessibility solution for visually impaired users.

## Project Workflow

1. **Input**

   * Image file
   * PDF document
   * URL or local file path

2. **Content Extraction**

   * Text extraction using Tesseract OCR.
   * PDF processing using PyMuPDF.
   * Image caption generation using BLIP.

3. **Content Enhancement**

   * GPT-based text generation improves clarity and provides additional context.

4. **Audio Generation**

   * Enhanced text is converted into speech using gTTS.

5. **Output**

   * Accessible audio content for users.

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* Tesseract OCR
* PyMuPDF (fitz)
* Hugging Face Transformers
* BLIP (Bootstrapping Language-Image Pretraining)
* GPT-2
* gTTS (Google Text-to-Speech)
* Pillow (PIL)
* Requests
* PyTesseract

## Installation

```bash
pip install pymupdf
pip install pytesseract
pip install transformers
pip install gtts
pip install pillow
pip install requests
```

Install Tesseract OCR:

```bash
sudo apt install tesseract-ocr
```

## Usage

1. Upload an image or PDF file.
2. Run the notebook.
3. The system extracts text and image descriptions.
4. GPT enhances the extracted content.
5. gTTS converts the content into audio.
6. Listen to the generated speech output.

## Applications

* Audio Books
* Educational Content Accessibility
* Digital Document Reading
* Research Paper Accessibility
* Real-Time Image-to-Audio Translation
* Assistive Technology for Visually Impaired Individuals

## Advantages

* Improves accessibility for visually impaired users.
* Handles both textual and visual content.
* Provides context-aware explanations using AI.
* Supports PDF and image inputs.
* Generates human-like audio output.

## Future Enhancements

* Real-time camera-based image-to-audio conversion.
* Multi-language support.
* Mobile application deployment.
* Integration with advanced Large Language Models.
* Cloud-based accessibility platform.

## Authors

* Godavarthi Naga Manoj Balaji
## Co-Authors
* Ayush Chetri
* Thrisha Reddy P
* Chandana G S
* Hruthika S N
* Munnangi Suma Reddy

## License

This project is developed for educational and research purposes. Feel free to use and extend it with proper attribution.

---

**Making digital content accessible through AI-powered audio generation for visually impaired individuals.**
