# YouTube Comments Data Analysis 🎥📊

This project focuses on analyzing YouTube comments using Python to understand
public sentiment, frequently used words, and emoji usage patterns.
The goal is to extract meaningful insights from large-scale user-generated text data.

---

## 📂 Dataset
- **Source**: US YouTube Comments Dataset  
- **Size**: ~690,000 comments  
- **Key Columns**:
  - `video_id`
  - `comment_text`
  - `likes`
  - `replies`

Missing values in comments were identified and removed during preprocessing.

---

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas & NumPy** – data handling
- **Matplotlib & Seaborn** – visualization
- **NLTK (VADER)** – sentiment analysis
- **WordCloud** – text visualization
- **Emoji** – emoji extraction and analysis
- **Plotly** – interactive charts

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Cleaning
- Imported CSV data using pandas
- Handled bad lines and mixed data types
- Dropped missing comment text values

---

### 2️⃣ Sentiment Analysis
- Used **VADER Sentiment Analyzer**
- Generated polarity scores for each comment
- Classified comments into:
  - **Positive**
  - **Negative**
  - **Neutral**

This helped understand overall audience reaction across videos.

---

### 3️⃣ WordCloud Analysis
- Created word clouds for:
  - Highly positive comments
  - Highly negative comments
- Removed common stopwords for clarity
- Helped visualize dominant words used by viewers

---

### 4️⃣ Emoji Analysis 😀🔥
- Extracted emojis from all comments
- Counted frequency of emoji usage
- Identified top emojis expressing emotions
- Visualized results using interactive bar charts

Top emojis revealed strong emotional patterns like joy, love, excitement, and sarcasm.

---

## 📊 Key Insights
- Majority of comments are **neutral to positive**
- Emojis like 😂, ❤️, 😍 are heavily used
- Negative comments are fewer but emotionally intense
- Emoji usage strongly correlates with sentiment strength

---

