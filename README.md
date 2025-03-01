# **Viral Trend Analysis & AI Content Generation**

## **Project Overview**
This project analyzes and predicts viral trends on social media platforms, specifically **X (formerly Twitter) and TikTok**. By leveraging **data scraping, sentiment analysis, and machine learning**, it identifies trending topics and generates AI-powered content (text, images, and videos) to maximize engagement.

## **Key Features**

- **Real-Time Data Scraping**: Extracts tweets and TikTok videos to detect emerging trends.
- **Trend Analysis & Prediction**: Uses **ML models (ARIMA, LSTMs, Facebook Prophet)** to forecast viral topics.
- **Sentiment Analysis**: Classifies user engagement (positive, neutral, negative) using **Azure AI & RoBERTa NLP model**.
- **Content Generation**: Utilizes **GPT-based models, RAG (Retrieval-Augmented Generation), and Stable Diffusion** to create captions, images, and videos.
- **Engagement Optimization**: Analyzes best posting times, hashtag trends, and influencer impact.
- **Interactive Dashboard**: Visualizes insights using **Flask & Dash**.

## **Technologies Used**

- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, TensorFlow, PyTorch)
- **Machine Learning**: Scikit-learn, ARIMA, LSTMs, Facebook Prophet
- **Data Processing**: NLTK, Hugging Face Transformers, Tweepy (X API), Playwright (TikTok scraping)
- **AI Models**: GPT-2, RAG (Facebook), Stable Diffusion (video generation), RoBERTa (sentiment analysis)
- **Storage & Deployment**: MongoDB, CSV, JSON, Flask

## **Installation & Setup**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-account/Viral-Trend-Analysis.git
cd Viral-Trend-Analysis
```

### **2. Set Up Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Configure API Keys**
Create a `.env` file and add the necessary API keys:
```
X_API_KEY=your_x_api_key
TIKTOK_API_KEY=your_tiktok_api_key
AZURE_AI_KEY=your_azure_ai_key
WEATHER_API_KEY=your_weather_api_key
```

### **5. Run the Application**
```bash
flask run
```

## **Usage**
1. The system continuously scrapes **trending tweets & TikTok videos**.
2. Sentiment analysis categorizes content into **positive, neutral, and negative**.
3. Trend prediction models forecast **future viral topics**.
4. AI-powered content generation creates **optimized text, images, and videos**.
5. Insights are displayed on an **interactive dashboard**.

## **Future Improvements**
- Expand trend analysis to **additional social media platforms**.
- Enhance **forecasting models** for more accurate trend prediction.
- Improve **content personalization** using advanced AI techniques.
- Deploy to **cloud platforms for scalability**.


