# Craft Today!

A Streamlit web application that helps users discover and explore craft projects from Instructables. Browse projects by category, popularity, and get AI-powered step-by-step instructions.

## Requirements

- Python 3.8+
- OpenAI API key
- Internet connection for web scraping and AI analysis

## Installation

0. **Python Version**

   - Use Python 3.8+

2. **Install dependencies**
   ```
   pip install -r requirements.txt
   ```

3. **Install Playwright browser**
   ```
   python -m playwright install chromium
   ```

4. **Set up OpenAI API key**
   - Create an account at https://platform.openai.com/
   - Create an API Key (this will require inputting credit card information, but each request only costs fractions of a cent) at https://platform.openai.com/settings/organization/api-keys
   - Create a `keys.py` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY = "your-api-key-here"`

## Running the App

```
streamlit run main.py
```

The app will open in your browser at `http://localhost:8501`

## How to Use

1. **Select your preferences** - Choose category, number of projects, and sort method
2. **Click "Show Projects"** - View filtered results table
3. **Select a project** - Choose from the dropdown list based on the index number of the chart
4. **Click "Get Instructions"** - Get AI-analyzed materials and step-by-step instructions


### **Example input -**

![Craft Today Example](https://github.com/user-attachments/assets/02364478-4e1f-4182-b1d8-f6fcdbaa474b)



### **Example result -**

<img width="847" height="611" alt="image" src="https://github.com/user-attachments/assets/34f64465-85ac-4b43-afdb-3b17926cc258" />
