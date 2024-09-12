# Text Sentiment and Emotion Analysis with Tweet Extraction

This project performs sentiment and emotion analysis on text data using natural language processing (NLP) techniques. It can also extract tweets based on specific keywords, analyze their sentiment and emotions, and visualize the results using bar charts.

## Features
- **Text Preprocessing**: Lowercasing, punctuation removal, and stop words filtering.
- **Emotion Detection**: Detects emotions using a predefined lexicon (`emotions.txt`).
- **Sentiment Analysis**: Analyzes text sentiment (positive, negative, or neutral) using the VADER model.
- **Tweet Extraction**: Fetches tweets based on a search term and timeframe using `GetOldTweets3`.
- **Visualization**: Visualizes emotion counts using bar charts.

## Technology Stack
- **Python**
- **NLTK** (Natural Language Toolkit)
- **GetOldTweets3** (Tweet extraction)
- **Matplotlib** (Visualization)
- **Counter** (From `collections` for counting emotions)


## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Install the required Python libraries:
   * Make sure the following libraries are installed: `nltk`, `matplotlib`, `GetOldTweets3`.
   
3. Download NLTK data (if required):
    ```python
    import nltk
    nltk.download('vader_lexicon')
    nltk.download('stopwords')
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

## Usage
1. Place your text data in the `read.txt` file.
2. Modify the script to change the keyword for tweet extraction (if needed).
3. Run the script:
    ```bash
    python main.py
    ```

4. The output will include:
   - Sentiment analysis results (Positive, Negative, Neutral).
   - Emotion analysis with a bar chart visualization (`graph.png`).

## Example
1. Text Sentiment and Emotion Analysis:
   - Input: `read.txt` file with sample text.
   - Output: Detected emotions and sentiment score, visualized in a bar chart.

2. Tweet Extraction:
   - Input: Tweets based on a keyword (e.g., "CoronaOutbreak").
   - Output: Emotion and sentiment analysis of tweets.

## License
This project is licensed under the MIT License.
