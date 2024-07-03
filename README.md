
# AskMe.AI- Data extraction from Database using AI 

End to End LLM project based on Google Palm and Langchain.
AskMe.AI is an AI-powered tool designed to facilitate data extraction from databases using natural language queries. Leveraging state-of-the-art language models and innovative technologies, it enables users to effortlessly retrieve desired data from databases without the need for expertise in SQL queries.

![](atliq_tees.png)

## Project Highlights

- AtliQ Tees is a t shirt store that sells Adidas, Nike, Van Heusen and Levi's t shirts 
- Their inventory, sales and discounts data is stored in a MySQL database
- AskMe.AI will use the following:
  - Google Palm LLM
  - Hugging face embeddings
  - Streamlit for UI
  - Langchain framework
  - Chromadb as a vector store
  - Few shot learning
- In the UI, store manager will ask questions in a natural language and it will produce the answers


## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/codebasics/langchain.git
```
2.Navigate to the project directory:

```bash
  cd 4_sqldb_tshirts
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  GOOGLE_API_KEY="your_api_key_here"
```
5. For database setup, run database/db_creation_atliq_t_shirts.sql in your MySQL workbench

## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```

2.The web app will open in your browser where you can ask questions

  
