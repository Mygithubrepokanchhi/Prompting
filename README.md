# Image and Text Prompt Generator


## Overview

Welcome to the Image and Text Prompt Generator! This project leverages Google APIs to generate descriptive prompt text based on input provided as both text and images. Implemented in a Google Colab notebook, this tool allows users to easily integrate and utilize the functionality for generating insightful prompts.

## Features

- **Text-to-Prompt Generation**: Creates prompts from provided text inputs.
- **Image-to-Prompt Generation**: Converts images into descriptive text prompts.
- **Combined Input Handling**: Processes both text and images to generate comprehensive prompts.
- **Google API Integration**: Utilizes `GOOGLE-API-KEY`, `gemini-pro`, and `gemini-pro-vision` for robust functionality.

## Getting Started

### Prerequisites

- A Google account to access Google Colab.
- Basic knowledge of Python.
- Google API Key for accessing the required services.

### Installation

1. **Install google-generativeai**:
    ```bash
    !pip install -U -q google-generativeai # Install the Python SDK
    ```
2. **Open the Colab Notebook**:
    - Open the notebook in Google Colab (https://colab.research.google.com/drive/1VCbbXL2oEZRFMsHK1TWLI5IN8dIhLPzB?usp=sharing).

### Setup

1. **Add Your API Keys**:
    - Insert your `GOOGLE-API-KEY` key into the designated cells in the Colab notebook.
  
### Usage

1. **Provide Input Text**:
    - Input the text for which you want to generate a prompt in the specified cell.

      ![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/603415c1-b058-4a52-b550-8d4889047647)


2. **Upload Images**:
    - Use the file upload feature in the Colab notebook to upload images.

      ![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/575d7f19-4b84-4c16-a6d2-fc84c96883c7)
      ![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/18288e7a-dea9-48d7-89be-55244258c565)


3. **Generate Prompts**:
    - Run the cells to generate text prompts from the provided text and/or images.

      ![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/0b8c1d91-1912-4c38-9ccc-2177cda19529)


## Project Structure

- `notebooks/`: Contains the main Google Colab notebook.
- `images/`: Example images for testing (if applicable).
- `src/`: Source code for the project.
- `README.md`: Project documentation.


## Examples

### Example 1: Generating a Prompt from Text

**Input Text**:
```
response = chat.send_message("In one sentence, explain how a data scientist role is different as compare to data analyst.")
print(response.text)
```
![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/40b75fe3-30bf-4cb0-bfa4-b21cb69cc4cc)

 
**Generated Prompt**:
```
Data scientists use advanced techniques and algorithms to build models and solve complex problems, while data analysts focus on interpreting and visualizing data to provide insights.
```
![image](https://github.com/Mygithubrepokanchhi/Prompting/assets/170111682/1bfb6699-023d-4f2a-ad30-47cb218c8140)


## Project Structure

- `notebooks/`: Contains the main Google Colab notebook.
- `images/`: Example images for testing (if applicable).
- `src/`: Source code for the project.
- `README.md`: Project documentation.


## Contact

For any questions or feedback, please open an issue or contact [Singh Kanchhipriya](mailto:kanchhisingh810@gmail.com).

---

