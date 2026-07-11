# -Gen-_AI-_Sentiment-_Reviews_Analyzer_projects

# 🤖 Gen AI Sentiment Analyzer

A **Generative AI-powered Sentiment Analysis** web application built using **Python**, **Gradio**, **Pandas**, **Matplotlib**, and **TextBlob**. This application analyzes customer reviews from an Excel file, classifies them into **Positive** or **Negative** sentiments, visualizes the results with a pie chart, and generates a downloadable report.

---

## 📌 Project Overview

Understanding customer feedback is essential for improving products and services. This project automates the sentiment analysis process by allowing users to upload an Excel file containing customer reviews.

The application automatically:

* Reads customer reviews from an Excel file
* Detects sentiment for each review
* Classifies reviews as **Positive** or **Negative**
* Displays the results in a table
* Generates a pie chart showing sentiment distribution
* Creates a downloadable Excel report

---

## 🚀 Features

* 📂 Upload Excel (.xlsx) files
* 🤖 Automatic sentiment prediction
* 😊 Positive & 😞 Negative classification
* 📊 Pie chart visualization
* 📥 Download processed Excel report
* 🎨 Clean and interactive Gradio interface
* ⚡ Fast and easy to use

---

## 🛠️ Technologies Used

* Python
* Gradio
* Pandas
* Matplotlib
* TextBlob
* OpenPyXL

---

## 📂 Project Structure

```
GenAI-Sentiment-Analyzer/
│
├── app.py                  # Main application
├── requirements.txt        # Required Python libraries
├── sample_reviews.xlsx     # Sample input file
├── sentiment_results.xlsx  # Generated output
├── README.md
└── screenshots/
    ├── home.png
    ├── result.png
```

---

## 📥 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/GenAI-Sentiment-Analyzer.git
```

```bash
cd GenAI-Sentiment-Analyzer
```

---

### Install Dependencies

```bash
pip install gradio pandas matplotlib openpyxl textblob
```

---

## ▶️ Run the Project

```bash
python app.py
```

After running, Gradio will generate a local URL similar to:

```
http://127.0.0.1:7860
```

Open it in your browser to use the application.

---

## 📊 How It Works

1. Upload an Excel file containing customer reviews.
2. The application automatically selects the first column.
3. TextBlob calculates the sentiment polarity of each review.
4. Reviews are classified into:

   * Positive
   * Negative
5. A pie chart is generated showing sentiment distribution.
6. The processed Excel report becomes available for download.

---

## 📁 Input Format

| Reviews               |
| --------------------- |
| Amazing product       |
| Very bad experience   |
| Excellent quality     |
| Poor customer support |

---

## 📤 Output Format

| Reviews               | Sentiment |
| --------------------- | --------- |
| Amazing product       | POSITIVE  |
| Very bad experience   | NEGATIVE  |
| Excellent quality     | POSITIVE  |
| Poor customer support | NEGATIVE  |

---

## 📈 Output

The application provides:

* Sentiment prediction table
* Pie chart visualization
* Downloadable Excel report

---

## 💡 Future Improvements

* Support for Neutral sentiment
* Hugging Face Transformer models (BERT, RoBERTa)
* Multi-language sentiment analysis
* Confidence score for predictions
* Bar chart and histogram visualizations
* PDF report generation
* Dashboard with analytics
* Batch processing for multiple files

---

## 🎯 Applications

* Customer feedback analysis
* Product review monitoring
* Business intelligence
* E-commerce review analysis
* Social media sentiment analysis
* Market research
* Brand reputation monitoring

---

## 📷 Screenshots

Add screenshots of your application inside the `screenshots` folder and update this section.

Example:

```
screenshots/
│
├── home.png
├── upload.png
└── results.png
```

---

## 📜 Requirements

```
gradio
pandas
matplotlib
openpyxl
textblob
```

---

## 👨‍💻 Author

**Kamaleshkumar S**

* B.Tech – Artificial Intelligence & Data Science
* Passionate about Artificial Intelligence, Machine Learning, and Generative AI


---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub and feel free to fork it, improve it, and share your ideas.

---

## 📄 License

This project is open-source and available under the **MIT License**.
