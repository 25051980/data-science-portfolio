 🧠 Mod_31 Machine Learning App

This project is part of the EBAC Data Science course and demonstrates how to build and deploy a machine learning application using Python. The app loads a trained model, makes predictions, and is configured for deployment using Heroku.

## 🚀 Project Overview

- Loads a trained ML model for classification or regression tasks.
- Exposes an interface for making predictions (CLI or Web, depending on integration).
- Uses dependency files and configuration for deployment to cloud platforms.

## 📁 Project Structure

```
Mod_31-main/
├── Mod_31.py            # Main Python script with model loading and logic
├── requirements.txt     # Python dependencies
├── setup.sh             # Setup script for deployment
├── Procfile             # Heroku-specific startup file
├── runtime.txt          # Python runtime version for Heroku
└── README.md            # Project documentation
```

## 📦 Requirements

Install dependencies locally with:

```bash
pip install -r requirements.txt
```

## ▶️ Running the App

To run the application: Git Hub (https://github.com/25051980/Mod_31)

## ☁️ Deployment

This project includes everything needed to deploy to Heroku:

- `Procfile`: Tells Heroku how to run the app
- `setup.sh`: Shell script for setting environment
- `runtime.txt`: Defines Python version for Heroku

To deploy:

```bash
heroku create your-app-name
git push heroku main
```

## 🙋 Author

**Samuel Walford**  
📊 Postgraduate in Data Science – PUC-Rio  
🔐 MSc Cyber Security Student – St Mary’s University  
🌍 Passionate about tech, AI, and real-world applications

---

📝 *This project was developed during the EBAC Data Science program as a practical implementation of model deployment techniques.*
