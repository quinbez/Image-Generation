# Image-Generation
This project demonstrates how to generate a visual representation from a text description using OpenAI's GPT-4 for text-to-prompt generation and the PixArtSigmaPipeline for image synthesis.

## Table of Contents 📑
    - Installation
    - Usage
      - Setting Up the Environment
      - Generating Text Prompts
      - Creating Images
      - Saving Outputs

## Installation and Setup ⚙️
1. install the required Python packages using the following command:
``` !pip install openai diffusers```
2. Import Required Libraries
3. Initialize the Model

## Generating Text Prompts 🔍✏️🤖

**User's Input:**

Provide a descriptive text (user input) that you want to visualize.

**Text-to-Prompt Conversion:**

The script utilizes GPT-4 to extract key elements from the text and convert them into a concise visual prompt suitable for image generation.

## Creating Images 🖼️🛠️✨

**Generate the Image:**

The prompt generated by GPT-4 is passed to the PixArtSigmaPipeline, which creates an image based on the description.

## Saving Outputs 💾

**Save the Generated Prompt:**

The script saves the generated prompt to a text file in the ./prompts directory.

**Save the Generated Image:**

The generated image is saved in the ./generated_images directory.

### 📂 Project Link: 
https://github.com/quinbez/Image-Generation/blob/main/Text_to_Image_Generation_Project.ipynb
