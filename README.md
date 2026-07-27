# 🤖 IBM SkillsBuild AI Project
# Nutrition Project

A small Flask web app for meal generation, nutrition analysis, and community recipe sharing.

## Project Structure

- `app.py` - main Flask app and routes
- `nutritional_analyzer.py` - nutrition lookup and parsing helpers
- `voice_module.py` - optional voice command module
- `meal_data.json` - saved meal plan data
- `templates/` - HTML pages for the app
  - `index.html`
  - `meal_generator.html`
  - `loading.html`
  - `display_meal.html`
  - `analyze.html`
  - `community_recipe.html`

## How to Run

1. Install Python 3.
2. Install dependencies:

   ```bash
   pip install flask requests speechrecognition pyttsx3 pyaudio
   ```

3. Start the app:

   ```bash
   python app.py
   ```

4. Open the browser at:

   ```
   http://127.0.0.1:5000/
   ```
## screenshort
1.home page

  <img width="443" height="210" alt="image" src="https://github.com/user-attachments/assets/c6cc0f35-af40-4021-8c90-330b5b3a5dfa" />

2.generate your meal plan

<img width="475" height="258" alt="image" src="https://github.com/user-attachments/assets/a04ba2cb-e839-4ec9-b686-ccdda04a14b6" />

3.Community recipe sharing

<img width="401" height="256" alt="image" src="https://github.com/user-attachments/assets/ad71bb76-7805-4a8c-983b-ffe107516469" />


  
 

## Important Notes

- The app uses a Nutritionix API request in `nutritional_analyzer.py`.
- The meal generator sends data to a Relay.app webhook in `app.py`.
- Replace any API keys or webhook URLs with your own before publishing.
- `voice_module.py` is optional and may need microphone/audio support on your system.


