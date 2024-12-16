# Sentiment Analysis of Tweets about US Airlines

This project is a **Streamlit dashboard application** for analyzing the sentiment of tweets related to US Airlines. It provides various interactive visualizations and tools to explore the data, including sentiment distribution, tweet locations, airline-specific breakdowns, and word clouds.

---

## Features

1. **Sentiment Analysis Overview**
   - Displays the overall sentiment of tweets categorized into *positive*, *neutral*, and *negative*.

2. **Random Tweet Display**
   - Shows a random tweet for a selected sentiment.

3. **Visualization of Sentiment Distribution**
   - Choose between a histogram or a pie chart to visualize the number of tweets by sentiment.

4. **Tweet Timing and Location**
   - Explore tweets posted during specific hours of the day and visualize their geographic locations on a map.

5. **Airline-Specific Sentiment Breakdown**
   - Analyze sentiment distribution for tweets associated with selected airlines.

6. **Word Clouds**
   - Generate and display word clouds for specific sentiments (*positive*, *neutral*, or *negative*).

---

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Python 3.7+
- pip (Python package manager)

### Steps
1. Clone this repository or download the source code.
2. Install the required dependencies using the following command:
   ```bash
   pip install streamlit pandas numpy plotly wordcloud matplotlib
   ```
3. Ensure the dataset file `Tweets.csv` is located at the specified path (`C:/Users/singh/OneDrive/Desktop/python/Tweets.csv`) or update the `DATA_URL` variable in the code to point to the correct location.

---

## How to Run the Application

1. Navigate to the directory containing the script.
2. Run the Streamlit application:
   ```bash
   streamlit run <script_name>.py
   ```
3. The application will open in your default web browser. Alternatively, access it via the URL provided in the terminal (typically `http://localhost:8501`).

---

## Data
The application uses a CSV file named `Tweets.csv` as the data source. This dataset contains the following relevant columns:
- `text`: The tweet text.
- `airline_sentiment`: The sentiment associated with the tweet (*positive*, *neutral*, *negative*).
- `airline`: The airline mentioned in the tweet.
- `tweet_created`: The timestamp of the tweet creation.

---

## Application Walkthrough

### Sidebar Features

- **Random Tweet Display**: Shows a randomly selected tweet based on the chosen sentiment.
- **Sentiment Visualization**: Toggle between histogram and pie chart to view sentiment distributions.
- **Tweet Timing and Location**:
  - Filter tweets by the hour of the day.
  - View the geographic distribution of tweets on a map.
  - Optionally display raw data.
- **Airline-Specific Breakdown**: Analyze the sentiment of tweets for one or more selected airlines.
- **Word Cloud Generation**: Visualize the most frequent words for tweets with a specific sentiment.

### Main Page

- **Dashboard Title and Description**: Provides an overview of the application’s purpose.
- **Visualizations**: Displays interactive charts and maps based on user selections from the sidebar.

---

## Key Libraries Used

- **Streamlit**: For building the interactive dashboard.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Plotly**: For creating interactive visualizations.
- **WordCloud**: For generating word clouds.
- **Matplotlib**: For displaying word clouds.

---

## Customization

- Update the `DATA_URL` variable to use a different dataset.
- Modify visualization settings, such as chart colors, dimensions, or additional data fields, to fit your specific requirements.

---

## Future Enhancements

- Add sentiment prediction using a machine learning model.
- Include additional filters for more granular data exploration.
- Improve UI/UX with advanced Streamlit components.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Author
Developed by [Vedant Singh Pundir].

