# Q&A: Question and Answer System Based on OPENAI LLM and Langchain for Fetching Desired data from database  

End-to-End LLM-Powered Q&A System with LangChain, OpenAI, and MySQL

This project is an end-to-end Question & Answer application built using LangChain and the OpenAI API, with a Streamlit-based user interface.

Users can ask natural language questions about wardrobe inventory, and the system will:

1.  Convert the question into an SQL query using an LLM.

2. Execute the query on a MySQL database.

3. Retrieve the relevant results.

4. Present the answer in a clear, user-friendly interface.

It combines modern LLM capabilities with database integration, enabling intuitive, conversational access to structured data.

<img width="1920" height="947" alt="QA_bot" src="https://github.com/user-attachments/assets/b0563a3d-44ff-4bf4-a2f8-bc5d8aed5237" />


## Project Highlights

## Tools used,
  - Langchain + OpenAI API
  - Streamlit: UI
  - OPENAI Embeddings
  - Chroma: Vector databs

## Project Results

## Database
<img width="689" height="515" alt="MySQL_Database" src="https://github.com/user-attachments/assets/018b0fe6-b2a2-4b01-8e7b-67a4292090ac" />

## Results 
<img width="688" height="477" alt="MySQL_query" src="https://github.com/user-attachments/assets/90661b2d-547e-4f3f-a12e-b39c5db80c93" />


## Installation

1.Clone this repository to your local machine using:

```bash
  git clone [https://github.com/codebasics/langchain.git](https://github.com/shaheer776/qa-bot-using-langchain-openai-mysql.git)
```
2.Navigate to the project directory:

```bash
  cd qa-bot-using-langchain-openai-mysql
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  OPENAI_API_KEY="your_api_key_here"
```
## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```

2.The web app will open in your browser.

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
