# OCR-with-Phi-3-Vision
This repository contains code to perform Optical Character Recognition (OCR) on images using the Phi-3 Vision model from Microsoft. The OCR output is provided in markdown format.



## Model

We use the `microsoft/Phi-3-vision-128k-instruct` model from Hugging Face's transformers library.

## Installation

To run the code, you need to install the required dependencies:

```bash
pip install numpy==1.24.4 Pillow==10.3.0 Requests==2.31.0 torch==2.3.0 torchvision==0.18.0 transformers==4.40.2 accelerate
