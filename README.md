# Decoding-Tourist-voice-A-Data-driven-analysis
Capstone project on Text analysis &amp; Web scraping 
This project presents an end-to-end Text Analytics & Natural Language Processing (NLP) system designed to analyze real-world tourist experiences across major destinations in India.
The system collects textual reviews through web scraping, cleans the text, applies multiple NLP techniques, and visualizes insights through an interactive Streamlit dashboard.

The project aims to help tourism stakeholders understand:

What tourists feel

What they talk about

What issues they frequently face

How sentiment varies across destinations

What themes dominate tourist discussions

🎯 Objectives

Collect real-world textual data from tourist experiences.

Preprocess and clean unstructured text.

Apply multiple NLP techniques to extract insights:

Sentiment Analysis

Keyword Extraction

Emotion Detection

Topic Modeling

Issue Identification

Build an interactive dashboard for users to explore insights.

Provide a scalable, reusable framework for tourism analytics.

🧰 Tools & Technologies
Programming & Frameworks

Python 3.x

Streamlit (Dashboard UI)

Jupyter / VS Code

Libraries

NLP: NLTK, NRCLex, RAKE, Scikit-learn

Visualization: Matplotlib, Seaborn, Plotly

Data Handling: Pandas, NumPy

Web Scraping: Requests, BeautifulSoup

Geolocation: Geopy

📂 Project Structure
├── data_raw/
│   ├── tourist_experience_india.csv
│   ├── tourist_experience_cleaned.csv
│   ├── usecase1_sentiment_analysis.csv
│   ├── usecase2_keyword_extraction.csv
│   ├── usecase3_emotion_detection.csv
│   ├── usecase4_topic_keywords.csv
│   ├── usecase4_topic_named.csv
│   ├── usecase5_issue_summary.csv
│
├── tourist_experience_scraper.py
├── data_cleaning.py
├── usecase1_sentiment_analysis.py
├── usecase2_keyword_extraction.py
├── usecase3_emotion_detection.py
├── usecase4_topic_detection.py
├── usecase5_issue_identification.py
├── dashboard.py
├── README.md

📊 NLP Use Cases Implemented
1️⃣ Sentiment Analysis (VADER)

Classifies each review as Positive, Negative, or Neutral.

Produces destination-wise sentiment scores.

Helps identify satisfaction levels across India.

2️⃣ Keyword Extraction (RAKE)

Extracts important keywords & phrases from reviews.

Provides an overview of the most discussed aspects of each destination.

3️⃣ Emotion Detection (NRCLex)

Detects emotions like Joy, Trust, Fear, Anger, Surprise, Sadness.

Helps understand the psychological dimension of travel experiences.

4️⃣ Topic Modeling (TF-IDF + NMF)

Identifies hidden themes discussed across reviews.

Example topics:

Logistics & Essentials

Food & Culture

Solo Travel & Safety

Hotels & Seasonal Travel

5️⃣ Issue Identification

Automatically detects common issues:

Safety

Crowding

Cleanliness

Traffic

Pricing

Weather

Service

Helps policymakers take corrective action.

🌐 Interactive Dashboard

The Streamlit dashboard provides:

Sentiment graphs

Emotion distribution

Topic distribution charts

Keyword lists

Issue summaries

Geographical sentiment maps

Run the dashboard:
streamlit run dashboard.py

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/tourist-experience-nlp.git
cd tourist-experience-nlp

2. Install the required libraries
pip install -r requirements.txt

3. Run the scripts

Clean data:

python data_cleaning.py


Run NLP analyses:

python usecase1_sentiment_analysis.py
python usecase2_keyword_extraction.py
python usecase3_emotion_detection.py
python usecase4_topic_detection.py
python usecase5_issue_identification.py


Launch dashboard:

streamlit run dashboard.py

📈 Results Summary

Tourists showed high positive sentiment for destinations like Goa, Kerala, Ladakh.

Urban regions displayed higher negative sentiments such as traffic, crowding, cleanliness issues, and safety concerns.

Emotions like Joy and Trust were dominant across most scenic locations.

Topic modeling revealed six meaningful tourist themes.

Issue identification highlighted safety and crowding as major concerns.

📜 License

Open-source under MIT License.

👤 Author

Tony Stark
Python Developer | Data Analyst | NLP Practitioner

🤝 Contributions

Contributions, suggestions, and improvements are welcome!
Feel free to open an issue or submit a pull request.
