# NLP Analysis on NYT Bestselling Non-Fiction Books

✨ Project Overview
This project applies Natural Language Processing (NLP) techniques to the descriptions of New York Times Bestselling Non-Fiction Books.
We focus on two major tasks:

Text Summarization to generate concise summaries of the book descriptions.

Emotion Detection to identify the emotional tone conveyed in each description.

The project uses libraries like NLTK, spaCy, text2emotion, sumy, and TextBlob to perform advanced text analysis.

🛠️ Solution Workflow
Data Loading: Load the NYT bestselling books dataset.

Summarization: Use LexRank algorithm (Sumy library) to generate short summaries.

Emotion Detection: Detect emotions (Happy, Angry, Sad, Surprise, Fear) using text2emotion.

Visualization: Create a bar plot to visualize overall emotional distribution across all books.

Saving Results: Store enhanced data (summaries and emotions) into a clean CSV.


📋 Setup Instructions

Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Anushka85252/nlp_project_01.git
cd nlp_project_01
Create a Virtual Environment (Recommended):

bash
Copy
Edit
python -m venv nlp_env
Activate the Virtual Environment:

Windows:

bash
Copy
Edit
nlp_env\Scripts\activate
Mac/Linux:

bash
Copy
Edit
source nlp_env/bin/activate
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebooks:

bash
Copy
Edit
jupyter notebook
➡️ Open the notebooks inside the notebooks/ folder and run all cells.

📦 Libraries and Versions Used

Library	Version
Python	3.11+
pandas	1.5.3
matplotlib	3.7.1
nltk	3.8.1
spacy	3.5.0
sumy	0.10.0
text2emotion	0.0.6
emoji	1.6.3
textblob	0.17.1
numpy	1.24.3


📈 Sample Outputs
Summarized Descriptions for each book

Detected Emotions (Happy, Sad, Angry, Fear, Surprise)

Bar plot showing the average emotion scores across all bestselling books

🎯 Key Takeaways
Compared NLTK vs spaCy tokenization and POS tagging techniques.

Built a working summarizer for book descriptions.

Extracted emotional profiles of bestselling nonfiction books.

Visualized the overall sentiment trends in popular books.

📚 Conclusion
Through this project, we successfully:

Summarized complex book descriptions into short, meaningful texts.

Extracted and visualized the emotional tone across multiple bestselling titles.

Gained valuable insights about reader sentiment trends in nonfiction literature.

