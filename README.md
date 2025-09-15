Book Recommender (HuggingFace + Streamlit)



Overview
A Book Recommendation System built using Hugging Face embeddings and Streamlit.
It suggests books based on genre, emotions, or free-text input.
The model works even without filters, always providing meaningful suggestions.
Features
- Suggests books by genre, emotion, or text description
- Works with one, two, or all filters applied
- Provides recommendations even if no filter is selected
- Uses semantic embeddings for better recommendations
- Clean and interactive Streamlit UI
Installation
Clone the repository and install dependencies:
git clone https://github.com/your-username/book-recommender-llm.git
cd book-recommender-llm
pip install -r requirements.txt
Usage
Run the app with:
streamlit run gradio-dashboard.py
Project Structure
- books_cleaned.csv, books_with_categories.csv, books_with_emotions.csv : Dataset files
- data-exploration.ipynb : Exploratory analysis
- vector-search.ipynb : Semantic search implementation
- sentiment-analysis.ipynb : Emotion tagging pipeline
- gradio-dashboard.py : Streamlit app
Note
The .env file with API keys (OpenAI, Hugging Face) is ignored for security reasons.
You need to add your own keys in .env to run locally.
Future Improvements
- Deploy on Hugging Face Spaces / Streamlit Cloud
- Add collaborative filtering
- Improve dataset with more book attributes
Author
Baibhab Ghosh
GitHub: https://github.com/MonGeR-B

