# ModernNest – AI Rent Prediction System

ModernNest is an AI-powered web application designed to predict monthly rental prices for residential properties. It uses a Machine Learning model deployed on a cloud backend to deliver fast and accurate rent predictions based on key property features such as BHK, furnishing status, and area size.

This project demonstrates real-world integration of Machine Learning, REST APIs, and a modern responsive web interface.

---

## About

The ModernNest AI Rent Prediction System helps users estimate fair rental values instantly. By combining user input with a trained ML model, the platform provides reliable predictions while maintaining a clean, intuitive user experience.

---

## Features

- AI-based rent prediction
- Clean, modern, and responsive UI
- Real-time API-based predictions
- Instant results with INR currency formatting
- Mobile-friendly single-page application
- Backend hosted on Render

---

## How It Works

1. The user enters property details such as:
   - BHK configuration
   - Furnishing status
   - Area size (in square feet)
2. The frontend sends this data to the backend API.
3. A trained Machine Learning model processes the input.
4. The predicted rent value is returned and displayed instantly.

---

## Tech Stack

### Frontend
- HTML5
- CSS3 (Glassmorphism-inspired modern UI)
- JavaScript (Fetch API)
- Google Fonts (Poppins)
- Font Awesome Icons

### Backend
- Python
- Flask
- Machine Learning Model
- REST API

### Deployment
- Backend: Render  
- Frontend: Static Hosting ( Vercel)

---
# Backend

### Request Body
```json
{
  "BHK": 2,
  "Furnishing": 1,
  "Size_sqft": 1200
}

#Use Cases

-Helps tenants estimate fair rental prices

-Assists property owners in pricing decisions

-Demonstrates ML and web application integration

-Suitable for academic projects and portfolios

#Future Enhancements

-Location-based rent prediction

-User authentication and profiles

-Prediction history and analytics

-Advanced ML model with more features

-Admin dashboard

#License

-This project is licensed under the MIT License.


### Endpoint
