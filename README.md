FAQ Chatbot

1. What is this project?
This is a simple FAQ chatbot that answers users' questions based on a collection of predefined questions and answers.

2. Why did I build this project?
I built this project to understand how chatbots work and how machine learning techniques can be used to find relevant answers.

3. What can this chatbot do?
Users can type their questions, and the chatbot searches for the most relevant answer from its FAQ dataset.

4. Which technologies did I use?
- Python
- Streamlit
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

5. How does it work?
First, the chatbot loads questions and answers from a CSV file. It converts the questions into numerical representations using TF-IDF. When a user asks something, cosine similarity helps find the closest matching question and returns its answer.

6. How can I run this project?

Install the required libraries:

`pip install -r requirements.txt`

Run the application:

`python -m streamlit run app1.py`

7. What did I learn from this project?
I learned how to work with text data, use TF-IDF, calculate cosine similarity, and build a simple chatbot interface.

8. Who developed this project?
**Developer:** Burri Srinu

**Internship:** CodeAlpha AI Internship
