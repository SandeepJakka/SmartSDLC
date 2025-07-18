SmartSDLC – AI-Powered Software Development Lifecycle Automation

**SmartSDLC** is a Google Colab-based AI application that automates various stages of the Software Development Lifecycle (SDLC) using the IBM Granite model from Hugging Face. Built with `FastAPI` and `Gradio`, it classifies requirements, generates code, fixes bugs, and summarizes code — all from natural language input.

## Features

## 1. Requirement Classifier
- Upload a PDF containing raw requirements
- Classifies content into SDLC stages:
  - Planning
  - Design
  - Implementation
  - Testing
  - Maintenance

## 2. AI Code Generator
- Converts natural-language implementation requirements into Python code

## 3. Bug Fixer
- Accepts buggy code and suggests fixes with explanations

## 4. Code Summarizer
- Provides human-readable summaries of pasted code

## 5. Stage-wise Summary Generator *(Upcoming)*
- Auto-generates summaries for each SDLC stage to help with documentation


## Built and Tested On

-  **Platform**: Google Colab (Notebook-based interface)
-  **Frontend**: Gradio (Runs inside Colab)
-  **Backend**: FastAPI (Used within Colab for structured endpoints)
-  **Model**: `ibm-granite/granite-3.3-2b-instruct` from Hugging Face
-  **Libraries**: `transformers`, `gradio`, `fastapi`, `uvicorn`, `PyMuPDF`, etc.


##  Files in This Project

|          File            |                      Description                       |
|--------------------------|----------------------------------------------------------------------------|
| `smart_sdlc_colab.ipynb` | Main notebook with all code (API, UI, and model logic)                     |
| `.env`                   | Hugging Face API token stored securely                                     |
| `sample_requirement.pdf` | Sample test PDF for SDLC classification                                    |
| `README.md`              | This readme file                                                           |


## How to Use

1. Open the notebook in Google Colab  
2. Install dependencies (auto-installed in the first cell)  
3. Add your Hugging Face token in a `.env` file or in a Colab cell  
4. Run the app and open the Gradio interface  
5. Upload PDF or use input boxes for bug fixing/code generation


## Sample Requirement PDF

You can test the classifier with a detailed sample requirements document that includes all 5 SDLC stages in paragraph format. [Generate Sample Here](#) or create your own.


## AI Model

- **Name**: `ibm-granite/granite-3.3-2b-instruct`
- **Task**: Instruction-based generation and classification
- **Hosted On**: Hugging Face Hub
- **Used For**:
  - SDLC stage classification
  - Code generation
  - Code summarization
  - Bug fixing


## Developed By

- **Sandeep Jakka**  
  Role: Prompt Engineer, AI Integrator, Colab Developer

## License

This project is licensed under the MIT License. You are free to reuse and modify for educational and research purposes.

## Future Improvements

- Add real-time chat interface for guided SDLC planning  
- Enable saving of generated code and summaries to Google Drive  
- Add support for multilingual code generation (JavaScript, Java, etc.)

`#GoogleColab` `#AI4SDLC` `#IBMGranite` `#SmartSDLC` `#FastAPI` `#Gradio` `#Python`
