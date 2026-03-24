# Return Risk Predictor and Smart Substitute Recommender

This project aims to reduce product return rates and improve customer satisfaction by predicting the likelihood of returns for each product and recommending lower-risk alternatives at the point of purchase.

Designed for **Walmart Sparkathon 2025**, this solution leverages machine learning and data-driven decision-making to improve user experience and optimize Walmart's retail efficiency.

## Live Demo
[Deployed URL here]

---

## Problem Statement

Product returns represent a major challenge for Walmart, leading to increased logistics costs, inventory inefficiencies, and reduced customer trust.

Many returns are preventable and occur due to:
- Inconsistent sizing
- Misleading product descriptions
- Quality concerns
- Poor customer reviews

This project addresses these challenges by:

- Identifying products with a **high probability of return before purchase**
- Recommending **lower-risk alternatives**
- Providing **explanations for return risks**

---

## Key Features

- Machine learning–based **return risk prediction**
- **Real-time product evaluation** during checkout
- Automated **smart substitute recommendation system**
- **Explainable AI module** highlighting return risk factors
- Simulated **Walmart product catalog with cart functionality**

---

## Architecture Overview

**Frontend**
- React (TypeScript)

**Backend**
- FastAPI (Python)

**Machine Learning**
- scikit-learn
- XGBoost (Return prediction model)

**Data Layer**
- Simulated product datasets
- Review datasets (CSV / Firebase)

**Deployment**
- Vercel / Render (or your platform)

---

## How It Works

1. A user selects a product and adds it to their cart.
2. The backend model calculates the **return probability** using:

- Average product rating
- Review volume
- Product category and price
- NLP-based sentiment from reviews
- Historical return rate patterns

3. If the predicted return probability exceeds a threshold:

- A **warning message** is displayed
- **Lower-risk alternative products** are recommended

4. The user can:
- Select a recommended substitute  
- Continue with the original product

---

## Tech Stack

- React + TypeScript
- FastAPI
- Python
- scikit-learn
- XGBoost
- Firebase / CSV datasets

---

## Future Improvements

- Real Walmart product dataset integration
- Improved NLP model for review sentiment
- Personalized recommendation engine
- Real-time analytics dashboard

---

## Author

**Soham Puranik**

B.Tech Computer Engineering  
AI & Cybersecurity Enthusiast
