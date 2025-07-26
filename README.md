# 🎬 IMDb Web Scraping & Sentiment Analysis

##  Project Description

This project aims to **scrape detailed movie information and user reviews from IMDb** using Python's **BeautifulSoup** library, then perform a **sentiment analysis** to determine the overall audience opinion. Finally, the results are **visualized with charts** for better interpretation.

## 🛠️ Features

*  **Data collection** of the following fields:

  * `movie`: Movie title
  * `year`: Release year
  * `rating`: IMDb user rating
  * `genre`: Movie genres
  * `runtime_min`: Runtime in minutes
  * `imdb`: IMDb score
  * `metascore`: Metacritic score
  * `movie_link`: IMDb URL
  * `user reviews`: used for sentiment analysis
* 🧠 **Sentiment analysis** (positive, neutral, negative) on user reviews
* 📊 **Result visualization** using **Matplotlib** and/or **Seaborn**
* 💾 Export collected data in **CSV** format

## 📚 Libraries Used

* `beautifulsoup4`: for web scraping IMDb
* `requests`: to fetch the HTML content
* `pandas`: for data cleaning and processing
* `nltk` or `textblob`: for sentiment analysis
* `matplotlib` & `seaborn`: for result visualization

## ⚙️ Installation & Execution

1. **Clone the project**

   ```bash
   git clone https://github.com/your-username/imdb-webscraping-sentimentanalysis.git
   cd imdb-webscraping-sentimentanalysis
   ```

2. **Open the Jupyter Notebook**

   ```bash
   jupyter notebook Scraping_Sentiment_Analysis.ipynb
   ```

4. **View the outputs**

   * A CSV file containing the scraped movie details and reviews
   * Visualizations showing the distribution of positive/negative reviews
   * A word cloud of the most frequent terms in reviews

## 📊 Sample Output

### **Scraped Movie Data (CSV Example)**

| movie      | year | rating | genre         | runtime\_min | imdb | metascore | movie\_link                                                                  |
| ---------- | ---- | ------ | ------------- | ------------ | ---- | --------- | ---------------------------------------------------------------------------- |
| The Batman | 2022 | PG-13  | Action, Crime | 176          | 7.8  | 72        | [https://www.imdb.com/title/tt1877830](https://www.imdb.com/title/tt1877830) |

### **Reviews Sentiment Analysis**

| User        | Rating | Review                     | Sentiment |
| ----------- | ------ | -------------------------- | --------- |
| John\_Doe   | 8/10   | "Great movie, well acted!" | Positive  |
| MovieFan123 | 4/10   | "Too slow and boring"      | Negative  |

### **Visualization Examples**

* Sentiment distribution chart (Positive, Negative)
* Word cloud showing the most frequent words in the reviews


## 👨‍💻 Author

Project developed by **Nada Ammar** as part of a data science project.
