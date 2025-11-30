
---

# FoodDeliveryApp – Full-Stack Food Ordering System**

```md
# FoodDeliveryApp – Full-Stack Food Delivery

## 🚀 Overview
FoodDeliveryApp provides search, restaurant listing, menu browsing, cart, payment structure, order tracking, and delivery workflow.  
Built with Kotlin, Compose, and a hybrid Firebase + REST setup.

---

## 🛠 Tech Stack
- Kotlin, Compose  
- Clean Architecture  
- Retrofit  
- Firebase Auth + Firestore  
- Google Maps API  
- Hilt  
- WorkManager  

---

## ⭐ Features
- Restaurant discovery  
- Menu browsing  
- Add-to-cart system  
- Address + payment method  
- Live order tracking  
- Offline menu caching  
- 30% faster cold start with Baseline Profiles  

---

## Architecture Diagram

app/
│
├── feature-restaurant/
├── feature-cart/
├── feature-order/
├── feature-tracking/
│
├── data/
├── domain/
└── core/


---

## Sync Logic
```kotlin
class OrderSyncWorker ... {
  repo.syncOrderStatus()
}

Security

Location data protected with Keystore

Firestore role-based access
