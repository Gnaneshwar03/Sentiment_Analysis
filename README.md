## Sentiment Analysis on Tweets

This project is a Python script that performs sentiment analysis on a collection of tweets. It uses the TextBlob library to analyze the sentiment of the tweets and generates a report and visual representation of the sentiment distribution.

### Installation

To run this project, you need to have Python installed on your system. You also need to install the required libraries by running the following command:

```
pip install textblob matplotlib pandas nltk
```

### Usage

1. Clone the repository to your local machine or download the script file.
2. Make sure you have the CSV file named 'tweets.csv' containing the tweets you want to analyze. Place this file in the same directory as the script.
3. Open the script file and modify the following variables as per your requirements:
   - `NoOfTerms`: Number of tweets to analyze.
   - `searchTerm`: Term to search for in the tweets.
4. Run the script using the following command:
   ```
   python Sentiment_Analysis_Engine.py
   ```
5. The script will process the tweets, perform sentiment analysis, generate a report, and display a pie chart representing the sentiment distribution.

### Dependencies

This project relies on the following libraries:

- textblob: For sentiment analysis.
- matplotlib: For data visualization.
- pandas: For data manipulation and analysis.
- nltk: For natural language processing tasks.

### License

This project is licensed under the MIT License. You can find the details in the [LICENSE](LICENSE) file.

### Acknowledgments

This project uses the TextBlob library, which is built on the NLTK library. The NLTK library provides various corpuses and resources for natural language processing tasks.

### Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### Contact

For any inquiries or questions, please contact [email protected]

### Disclaimer

This project is for educational and demonstration purposes only. It may not provide accurate sentiment analysis results and should not be used for critical decision-making processes.
