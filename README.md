# 🔗 Content Aggregation Application
Overview
The Content Aggregation Application is a Python-based tool designed to fetch and summarize news articles on any topic of interest. It provides an overview of the topic using Wikipedia, scores articles based on relevance, and visualizes the scores using interactive charts.

Features
TF-IDF-based Summarization: Extracts concise summaries from full-text articles or summaries.

Wikipedia Integration: Retrieves a brief overview or theory about the queried topic.

Relevance Scoring: Assigns relevance scores to articles based on query keywords using softmax normalization.

Visual Charts: Displays a bar chart of article relevance scores using Altair.

User Authentication: Login functionality for access control.

Technologies Used
Python: The core language for the application.

Streamlit: For building the user interface.

BeautifulSoup: For parsing HTML content.

TF-IDF (Scikit-learn): For text summarization.

Newspaper3k: To extract full-text articles from URLs.

Wikipedia API: For fetching related theories.

Altair: For visualizing relevance scores.

Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/repo-name.git
cd repo-name
2. Install Dependencies
Make sure you have Python 3.8+ installed. Install the required libraries using:

bash

pip install -r requirements.txt

3. Run the Application
Start the Streamlit application:

bash
streamlit run app.py

How to Use
Login: Use the default credentials (username: admin, password: 1234) to access the app.

Search for a Topic: Enter a topic in the input field and hit enter.

View Results:

Topic Overview: A short description fetched from Wikipedia.

Latest Articles: List of summarized articles with relevance scores.

Relevance Score Chart: A visual bar chart representing article relevance.

Screenshots
Login Page
![image](https://github.com/user-attachments/assets/d68ca032-5692-4a01-ab52-c690a0ba6bb9)

Main Application
![image](https://github.com/user-attachments/assets/072059e5-a860-49f6-b134-05a4d3c18609)
![image](https://github.com/user-attachments/assets/749cc34d-0f4e-4e20-976b-a07a01cc286e)

Relevance Score Chart
![image](https://github.com/user-attachments/assets/2d883838-1e1a-4fa0-93fc-a6041e0d5e77)


Project Structure
bash
Copy
Edit
.
├── app.py                  # Main Python application
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
Dependencies
The following libraries are required:

streamlit

feedparser

pandas

numpy

beautifulsoup4

scikit-learn

newspaper3k

wikipedia-api

altair

Future Enhancements
Add more advanced NLP-based summarization techniques (e.g., BERT or GPT-based summarization).

Implement advanced authentication mechanisms.

Extend support for more news sources and RSS feeds.

Add deployment to a cloud platform like Streamlit Cloud or Heroku.

Contributing
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request. Ensure your code is well-documented and adheres to the project structure.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
