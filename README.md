# 🍽️ Gemini Calories & Nutrition App

A simple Streamlit web app that uses Google Gemini to analyse a meal image and estimate its calories. You upload a food photo, add a short text prompt, and the app returns a breakdown of items with approximate calories.

##  Features

- Upload a food image (JPG / PNG).
- Provide an input prompt (e.g. "Describe this meal and estimate the calories").
- Uses Google Gemini (`gemini-flash-latest`) to:
  - List the food items it sees.
  - Estimate calories for each item.
  - Optionally comment on how healthy the meal is.

##  Tech Stack

- Python  
- Streamlit  
- google-generativeai  
- python-dotenv  
- (Optional) sqlite3 example script in `sqlite.py` for a local test database.  

All Python dependencies are listed in `requirements.txt`.

##  Setup 

- Clone the repo
- Create and activate a virtual environment
- Install dependencies(pip install -r requirements.txt)
- Set up environment variables:Create a file called .env in the project root:
     GOOGLE_API_KEY=your_real_gemini_api_key_here
- Run the app: streamlit run app.py
