# YouTube Analysis in Python

## Overview
This project provides a comprehensive analysis of YouTube comments using Python. The analysis includes sentiment analysis, word cloud generation, emoji analysis, and visualization of trends in user feedback.

## Features
- **Sentiment Analysis**: Classifies comments as positive, negative, or neutral.
- **Word Cloud Visualization**: Displays frequently used words in comments.
- **Emoji Analysis**: Analyzes emoji usage in YouTube comments to understand user sentiment better.
- **Comment Length Distribution**: Examines the distribution of comment lengths.
- **Most Frequent Words**: Identifies commonly used words in both positive and negative comments.
- **User Engagement Analysis**: Analyzes the frequency and types of interactions users have in comments.

## Requirements
To run this project, you need to install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn wordcloud textblob emoji
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/tanishkasharma29/YouTube_Analysis_Python.git
   ```
2. Navigate to the project directory:
   ```bash
   cd YouTube_Analysis_Python
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Youtube_analysis.ipynb
   ```
4. Run the cells step by step to analyze YouTube comments.

## Results
- **Positive Sentiment Words**: Users frequently use words like *best, awesome, perfect, amazing, happy*.
- **Negative Sentiment Words**: Common negative words include *terrible, worst, horrible, boring, disgusting*.
- **Emoji Analysis**: Determines which emojis are associated with positive or negative sentiments.
- **Word Cloud Representation**: Shows the most frequently occurring words in positive and negative comments.
- **Comment Length Distribution**: Provides insights into whether short or long comments are more prevalent.
- **Engagement Insights**: Identifies common patterns in user interactions based on the nature of comments.

## Screenshots
To enhance the documentation, you can add relevant screenshots in the following sections:
- **Sentiment Analysis Results**: Add an image showing a summary of positive, negative, and neutral comment distributions.
- **Word Cloud**: Include a generated word cloud image to visualize frequently used words.
- **Emoji Analysis**: Insert a graphical representation of emoji usage in positive and negative comments.
- **Comment Length Distribution**: Display a histogram or graph showing comment length trends.

You can place the screenshots in a `screenshots/` directory and reference them in the README like this:
```markdown
![Sentiment Analysis](screenshots/sentiment_analysis.png)
![Word Cloud](screenshots/wordcloud.png)
![Emoji Analysis](screenshots/emoji_analysis.png)
![Comment Length Distribution](screenshots/comment_length.png)
```

## Contributing
Feel free to submit issues or pull requests for improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).

