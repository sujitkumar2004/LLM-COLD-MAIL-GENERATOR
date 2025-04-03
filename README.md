# LLM Cold Email Generator

Overview
This project is designed to automate the process of scraping job listings, extracting relevant information from the scraped content, and generating personalized cold emails for outreach using LangChain. The pipeline uses a machine learning model, ChatGroq, and document loaders from LangChain to achieve these objectives.

# Features:
Job Scraping: Scrape job listings from a specified website.
Information Extraction: Extract important details such as job role, experience, skills, and description using natural language models.
Portfolio Matching: Compare extracted job requirements to the user’s portfolio using a vector store for skill matching.
Cold Email Generation: Automatically generate cold emails tailored to the job description, highlighting relevant work in the portfolio.

# Requirements
- Python 3.7+
- OpenAI API key
- Required Python packages:
  openai
  python-dotenv
  ipywidgets

# Installation
Clone this repository:
```bash
  git clone https://github.com/sohamvsonar/LLM-cold-email-generator.git
  ```

Install the required packages:
```bash
  pip install openai python-dotenv ipywidgets
  ```

Create a .env file in the project root and add your OpenAI API key:
```bash
  OPENAI_API_KEY=your_api_key_here
  ```

# Usage
- Open the llm_code_email_generator.ipynb notebook in Jupyter Lab or Jupyter Notebook.
- Run all cells in the notebook.
- Use the provided input fields to enter company and recipient information.
- Click the "Generate Email" button to create a personalized cold email.
- The generated email will be displayed below the input fields.
