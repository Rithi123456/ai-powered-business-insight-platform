AI-Powered Business Insight Platform

Overview
•	Built an interactive AI-powered business analytics platform using Python and Streamlit  
•	Leverages Google Gemini (Generative AI) to analyze images and user queries  
•	Provides trend interpretation, personalized insights, and multilingual support**  
•	Designed for exploratory analysis and AI-assisted decision support  

Key Features
•	Image upload and AI-based visual analysis  
•	Text and voice-based query input (Speech-to-Text)  
•	AI-generated trend and pattern interpretation  
•	Industry-specific personalized insights  
•	Multilingual translation of user queries  
•	Downloadable AI-generated responses  
•	Email delivery of insights  
•	Interactive UI with themes, background styling, and animations  

Technologies & Libraries
•	Python
•	Streamlit– Web application framework  
•	Google Generative AI (Gemini API) – Insight generation  
•	Pillow (PIL) – Image processing  
•	SpeechRecognition – Voice input handling  
•	googletrans – Language translation  
•	smtplib – Email integration  
•	HTML/CSS (via Streamlit markdown) – UI customization  

How It Works
•	User uploads an image (charts, reports, or visual data)
•	User enters a query or uses voice input
•	Image and query are sent to Gemini AI for analysis
•	AI generates contextual insights and trend interpretations
•	Output can be translated, downloaded, or sent via email
•	Insights are customized based on selected industry

Supported Industries
o	Healthcare  
o	Retail  
o	Finance  
o	Technology  

How to Run the Project

Step 1: Install Dependencies
```bash
pip install streamlit google-generativeai pillow speechrecognition googletrans==4.0.0-rc1

Step 2: Configure API Key
•	Replace the API key in the code with your own:
genai.configure(api_key="YOUR_API_KEY")

Step 3: Run the Application
streamlit run app.py

