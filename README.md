# culture_circle


# Full Stack Developer Technical Assessment

## Overview
This repository contains the solutions for the Full Stack Developer Technical Assessment, including:
- **E-commerce Product Description Page** (Web & Mobile)
- **StockX Web Scraping Application**

## Table of Contents
- [Technologies Used](#technologies-used)
- [Installation & Setup](#installation--setup)
- [Features](#features)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)
- [Thought Process Documentation](#thought-process-documentation)
- [Future Improvements](#future-improvements)

---
---

## Technologies Used

### **E-commerce Product Description Page**
- **Web:** Next.js, Tailwind CSS, Zustand (state management), shadcn/ui
- **Mobile:** Flutter, Riverpod (state management), HTTP client

### **StockX Web Scraper**
- **Backend:** Node.js, Express, Playwright (web scraping), PostgreSQL
- **Frontend:** Next.js, Tailwind CSS, GraphQL API
- **Database:** PostgreSQL + Prisma ORM

---

## Installation & Setup

### **Clone the Repository**
```sh
git clone https://github.com/yourusername/fullstack-dev-assessment.git
cd fullstack-dev-assessment
```

### **Setup E-commerce PDP (Next.js Web)**
```sh
cd ecommerce-pdp-web
npm install
npm run dev
```

### **Setup E-commerce PDP (Flutter Mobile)**
```sh
cd ecommerce-pdp-mobile
flutter pub get
flutter run
```

---

## Features

### **E-commerce Product Description Page**
✅ Pixel-perfect UI matching Figma design  
✅ Size selection and Add to Cart functionality  
✅ Fully responsive design (desktop & mobile)  
✅ Smooth animations with Framer Motion  
✅ Clean architecture with reusable components  

### **StockX Web Scraper**
✅ Scrapes StockX product details (name, price, sizes, description, images)  
✅ Real-time scraping status updates  
✅ Stores data in PostgreSQL with Prisma ORM  
✅ Export scraped data as CSV/JSON  
✅ Error handling and retry mechanisms  

---

## API Documentation

### **StockX Scraper API**
#### **1. Scrape Product Data**
**Endpoint:** `POST /api/scrape`
```json
{
  "url": "https://stockx.com/product-url"
}
```
**Response:**
```json
{
  "name": "Air Jordan 1 Low SE",
  "price": "$150",
  "sizes": ["7", "8", "9", "10"],
  "description": "Limited edition sneaker.",
  "brand": "Nike",
  "images": ["url1", "url2"]
}
```

#### **2. Get Scraped Data**
**Endpoint:** `GET /api/products`
Returns all previously scraped products stored in the database.

---

## Deployment

### **Deploy Next.js Web App on Vercel**
```sh
vercel
```

### **Deploy Flutter App on Firebase**
```sh
flutter build web
firebase deploy
```
---

## Thought Process Documentation
Detailed documentation on planning, design choices, implementation, and testing is available in the `/docs` folder.

---

## Future Improvements
- Implement authentication for user accounts
- Enhance UI with dark mode support
- Add pagination for scraped product data
- Improve error handling for web scraping edge cases

---

## Author
👤 **Sarthak Raina**  
📧 [rainasarthak03@gmail.com](mailto:rainasarthak03@gmail.com)  
🔗 [LinkedIn Profile](https://linkedin.com/in/sarthak-raina-099856236/)
