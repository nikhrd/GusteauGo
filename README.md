# GusteauGo - Multi Modal Recipe Recommendation System

An intelligent full-stack web app that generates complete recipes using ingredients you already have at home. Supports both **text-based ingredient input** and **image-based ingredient detection** to reduce food waste and save time.

### Problem Description
Many people struggle to decide what to cook with available ingredients. This is especially common for students, working professionals, and daily home cooks with limited time and resources.

**Key issues with existing platforms:**
1. **Search by dish name only**: Inefficient when you only know ingredients you have
2. **Missing ingredients**: Recipes often require items you don’t possess → frustration + food waste  
3. **No smart integration**: Lack of systems combining ingredient-based search + image-based food recognition

This affects daily convenience, time management, and resource utilization. A solution that simplifies recipe discovery can reduce food wastage and improve cooking experience.

**Additional gap**: No intelligent system that integrates:
- Text-based ingredient entry
- Image-based ingredient extraction from food photos

Users expect fast, personalized, smart solutions. This project builds an AI-powered system that analyzes ingredients or food images and generates relevant recipes efficiently.

### Project Objectives
1. **Smart recipe generation**: Generate complete, structured recipes using only user-provided ingredients via text or image
2. **Reduce food waste**: Promote utilization of existing ingredients instead of buying new ones
3. **Fast + user-friendly**: Minimize time/effort for meal planning and decision-making
4. **Flexible input**: Support both manual text entry and image upload for ingredient extraction
5. **Secure + personalized**: Implement authentication, let users save/view/manage recipes
6. **Scalable full-stack**: Ensure smooth performance, reliable data management, cross-device access

### Tech Stack
- **Frontend**: React.js - responsive UI for mobile + desktop
- **Backend**: Flask - API + business logic
- **Database**: MongoDB - user data, saved recipes
- **AI/ML**: Image recognition model for ingredient detection + NLP model for recipe generation
- **Authentication**: Secure user login + personalization

### Key Features
- **Ingredient-based search**: Enter what you have, get recipes instantly
- **Image upload**: Upload photo of ingredients/fridge → auto-detect items
- **Zero waste**: Recipes designed around your available ingredients only
- **User accounts**: Save favorite recipes
- **Fast suggestions**: AI generates structured recipes in seconds

### How It Works
1. **Input**: User enters ingredients manually OR uploads image of ingredients
2. **Detection**: AI extracts ingredient list from text/image
3. **Generation**: System matches ingredients with recipe database + AI model
4. **Output**: Returns complete recipe: steps, quantities, nutrition, allergens
5. **Save**: Users can save, rate, and revisit recipes

### Usage
```bash
# 1. Clone and install
git clone <repo-url>
cd GusteauGo
pip install -r requirements.txt
npm install

# 2. Run backend
python app.py

# 3. Run frontend  
cd client
npm start
