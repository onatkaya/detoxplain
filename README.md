# Detoxplain: Toxic Text Identification and Modification ✏️

![Detoxplain](images/detoxplain_logo.PNG "Our Logo")

## Description 🤖
This project provides a text assistant tool that aims to detect toxicity in text, give explanation as to why it is toxic, and detoxify it to suggest an alternative to the user.

This objective is mainly achieved by conducting a sophisticated NLP-pipeline: By integrating various BERT models (DistilBERT, RoBERTa) with a LLM (gpt-4o-mini) and a explainable AI model (LIME). See the visuals below for better understanding.

## Visuals 👁

### System Components and Pipeline:

![Pipeline](images/pipeline_components.PNG "System Components and Pipeline")

### User Interface:

![Pipeline](images/user_interface.PNG "User Interface")

## Installation 🔧

```bash
git clone https://github.com/onatkaya/detoxplain.git

# create project file
mkdir detoxplain
cd detoxplain

# create virtual environment
conda create -n detox-venv python=3.10.0
conda activate detox-venv

# install dependencies
pip install -r requirements.txt
```

## Usage 🤳
You may use this assisting tool to assess the toxicity of your text, analyze why it can be deemed as toxic, and have helpful suggestions to an alternative detoxified version of your text.

## API Keys 🔑
During this project, an API key from OpenAI was used. Due to privacy concerns, the key cannot be shared, so please obtain your own key. You could use your own key(s) where it is being mentioned in the notebook as instructed.

## Credits and Acknowledgment 👾
This project is co-authored with Cemre Biltekin and Hasan Selim Yagci.
