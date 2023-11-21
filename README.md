## Question and Answer System Based on Google Palm LLM and Langchain for E-learning company

This is an end to end LLM project based on Google Palm and Langchain. We are building a Q&A system for an e-learning company. 
They have thousands of learners who uses discord server or email to ask questions. This system will provide a streamlit
based user interface for students where they can ask questions and get answers.

### Project Highlights

1. Use a real CSV file of FAQs where company uses.
2. Their human staff will use this file to assist their course learners.
3. We will build an LLM based question and answer system that can reduce the workload of their human staff.
4. Students should be able to use this system to ask questions directly and get answers within seconds.

### Steps to execute

1. Install all required libraries/packages, which are listed out in requirements.txt
2. Create google Key API from below website: ( https://makersuite.google.com/app/apikey) and load it from .env
3. Read csv file and convert into Embeddings, here we used "Huggingface instructor embeddings: Text embeddings"
4. Save vector embeddings into Vector database (FAISS).
5. Use Streamlit for UI.