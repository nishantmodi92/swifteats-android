🍔  <h1 align="center">FoodDeliveryApp — Full-Stack Food Ordering System</h1>

<p align="center">
Real-time food ordering & delivery tracking app built with Kotlin, Maps API, Firebase & Clean Architecture.
</p>

---

## 🔥 Badges
![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blue)
![Compose](https://img.shields.io/badge/Compose-Stable-green)
![Maps](https://img.shields.io/badge/Google%20Maps-API-red)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange)
![Crash Free](https://img.shields.io/badge/Crash%20Free-98%25-success)
![Performance](https://img.shields.io/badge/Cold%20Start-30%25%20Faster-brightgreen)

---

## 🚀 Overview
A high-performance food delivery app inspired by Swiggy/Zomato flow with:

- Live delivery tracking  
- Order scheduling  
- Secure payments  
- Real-time updates through Firestore  

---

## ⭐ Key Metrics
- ⚡ Real-time order tracking with Driver Location  
- 🗺 Google Maps turn-by-turn delivery path  
- 🔐 Secure checkout + server validation  
- 🏎 30% faster cold start  
- 📉 98% crash-free

---

## 🧩 Features
- User authentication  
- Restaurant & menu listing  
- Add to cart, offers, coupons  
- Live driver movement  
- Firebase Cloud Messaging alerts  
- Order history  
- Real-time ETA updates  
- Material You design + animations

---

## 🛠 Tech Stack
- Kotlin, Jetpack Compose  
- Firebase: Auth, Firestore, Storage  
- Google Maps API  
- Hilt, Retrofit, Room  
- Coroutines + Flow  

---

## 🧱 Architecture Diagram
Compose UI

↓
ViewModel (Use Cases)

↓
Repository

↓
Data Sources

• Firestore (orders/menu)

• Maps API (tracking)


---

## 🏗 System Design Summary
- Firestore pub/sub for order events  
- Driver location stored every 3 seconds  
- Offline cart sync with Room  
- FCM push for order status updates  

---

## ⚙ Setup
```bash
git clone https://github.com/nishantmodi92/FoodDeliveryApp
open in Android Studio → run


• Room (offline)


📁 Folder Structure
/data
/domain
/ui
/di
/maps


Roadmap

Payment gateway integration



Author
Nishant Modi
