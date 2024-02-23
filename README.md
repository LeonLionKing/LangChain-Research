# LangChain Research Project

The LangChain Research project aims to explore the integration of LangChain with the SAP Generative AI Hub. LangChain is a tool for language generation and processing, while SAP Generative AI Hub provides a platform for leveraging generative AI models developed by SAP.

## Project Overview

The primary objective of the LangChain Research project is to pave the way for future projects where generative AI can be applied to enhance user experience. By integrating LangChain with the SAP Generative AI Hub, we aim to investigate how generative AI models can be utilized to provide users with more enriching and personalized experiences in various applications.

## Project Structure
The project directory structure is organized as follows:

- **CustomModel/**: This directory contains custom models developed as part of the LangChain Research project.
  - `CustomLLM.py`: A Python file within the `CustomModel` directory that serves as a custom encapsulation of the LangChain LLM module. This module facilitates interaction with the SAP Generative AI Hub's APIs.

- **prompt-template-demo/**: This directory contains a demo application built using LangChain's Model I/O module. Users can input simple descriptions of risks on a web page and receive suggestions for treatments.
  - `app.py`: Python file to run the Flask web application.
  - Other files and directories related to the demo application.

- **LangChain.ipynb**: This is a Jupyter Notebook file included in the project. It serves as a sandbox environment for exploring the basic functionalities and methods available in LangChain. This notebook allows researchers and developers to experiment with various language generation and processing tasks within the LangChain framework.

## Getting Started

To get started with the LangChain Research project, follow these steps:

1. Clone the project repository from GitHub.

2. Ensure that all the required Python libraries are installed by using the `requirements.txt` file provided in the root directory of the project. You can install the dependencies using the following command:

```
pip install -r requirements.txt
```

3. Navigate to the `prompt-template-demo` directory.

4. Run the `app.py` file using the following command:

```
python app.py
```

5. Once the application is running, you can access it by navigating to `http://127.0.0.1:5000/` in your web browser. This will open a demo page where users can input a simple description of a risk and receive suggestions for treatments.

## Conclusion

The LangChain Research project serves as a foundational exploration for future projects where generative AI can enhance user experiences. By integrating LangChain with the SAP Generative AI Hub, we aim to unlock the potential of generative AI models to provide users with more enriching and personalized experiences across various applications.

