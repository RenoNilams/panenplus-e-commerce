# PanenPlus 🌾

An end-to-end agriculture e-commerce mobile application built with Flutter and Dart, fully integrated with Firebase. PanenPlus aims to cut the middleman supply chain by enabling direct transactions between local farmers and consumers.

<div align="center">
  <img src="lib/assets/panenplus.png" alt="PanenPlus App Showcase" width="100%">
</div>

## 🚀 Key Features

*   **Role-Based Access Control:** Secure authentication for buyers and sellers using Firebase Auth.
*   **Real-time Marketplace:** Browse, search, and add agricultural products to the cart in real-time.
*   **Seller Dashboard:** Comprehensive store management including product upload, stock tracking, and order status updates (Processed, Shipped, Completed).
*   **Order & Payment Processing:** Full checkout flow calculating subtotals and shipping costs.
*   **Interactive Chat & Notifications:** In-app push notifications and a direct buyer-seller communication system.

## 🛠️ Tech Stack

*   **Frontend:** Flutter, Dart, Google Fonts
*   **Backend as a Service:** Firebase (Firestore, Authentication, Storage)
*   **UI/UX Design:** Figma

## 📂 Project Structure Highlights
*   `lib/screens/`: Contains all UI views including Authentication, Cart, Payment, and Seller Dashboard.
*   `lib/services/`: Core logic for `FirestoreService` handling CRUD operations for products, orders, and chats.