# LinkedIn Post Generator 🚀

## Overview

The **LinkedIn Post Generator** is an AI-powered tool that creates engaging LinkedIn posts based on user-selected **topics, length, and language**. It leverages **LLMs (Groq - Llama 3.1-8B)** and **few-shot learning** to generate posts with a natural and contextually relevant style.

## Features ✨

- 🏷️ **User Input Selection**: Choose **Topic**, **Length**, and **Language**.
- 🤖 **Few-Shot Learning**: Uses past examples for better writing style.
- 🔄 **Preprocessing Pipeline**: Automatically processes and categorizes posts.
- 🎨 **Streamlit Interface**: Simple UI for seamless interaction.
- 🧠 **LLM Integration**: Powered by **LangChain** & **Groq API (Llama 3.1-8B)**.

## Tech Stack 🛠️

- **Python**
- **Streamlit**
- **LangChain**
- **Groq API (Llama 3.1-8B)**
- **Pandas**
- **JSON Processing**

## Installation 💻

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Devanshu070/Linkedin-Post-Generator.git
   cd linkedin-post-generator
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
     ```
4. **Set up environment variables:**
   Create a .env file and add your Groq API Key:
    ```sh
   GROQ_API_KEY=your_api_key_here
   ```
## Usage

1. **Run the Streamlit app:**
   streamlit run main.py
2. **Select a Topic, Length, and Language.**

3. **Click "Generate" to get a LinkedIn post.**

## Example Output
<img src="https://github.com/user-attachments/assets/1e7044f5-7094-4e3c-ae76-3475a711aa8d" alt="Screenshot" width="600"/>

