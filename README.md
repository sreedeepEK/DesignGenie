### DesignGenie

A lightweight application for generating UI design images based on text prompts using machine learning models. The application utilizes pre-trained models for feature extraction and image generation, allowing users to create visual designs quickly and efficiently.

![alt text](https://github.com/sreedeepEK/DesignGenie/blob/9baffef0ed7008e7bab512207f63f500de5b4ac9/workflows/workflow_image.png)


#### Installation

##### Prerequisites

Make sure you have Python 3.7 or later installed. You can check your Python version by running:

```bash
python --version
```
Clone the Repository
```
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```
Install Required Packages

You can install the required Python packages using pip: 
```
pip install -r requirements.txt
```

Set Up Environment Variables

You may need to create a .env file to store your Hugging Face API token: 

```
HUGGINFACE_API_KEY=your_api_key_here
```
Usage

Run the application by executing the running the `file.ipynb`. 

Example Prompts,

- "A futuristic mobile app design"
- "Minimalistic website layout"

Models Used

- Feature Extractor: CLIP - A model for extracting features from images and text, enabling the understanding of user prompts.
- Generative Model: Stable Diffusion - A powerful generative model for creating images from text prompts.

#### License

This project is licensed under the MIT License, which is a permissive free software license. This means that you are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided that you include the original license and copyright notice in any copies of the software that you distribute.
