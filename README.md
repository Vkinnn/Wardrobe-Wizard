# Wardrobe_Wizard

Project Structure:

wardrobe_wizard/

├── streamlit_app.py         # Main app file, handles navigation & auth setup

├── pages/

│   ├── 1_👋_Introduction.py   # Landing page, auth, initial upload

│   ├── 2_👗_My_Closet_&_Chat.py # Inventory display & chatbot

│   └── 3_⭐_Saved_Outfits.py   # Display saved outfits

├── backend.py               # Contains adapted backend logic (functions from Colab script)

├── auth.py                  # Google OAuth handling functions

├── requirements.txt         # Python dependencies

└── .streamlit/
    └── secrets.toml         # Store API keys and OAuth credentials
