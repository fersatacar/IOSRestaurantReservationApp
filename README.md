# 🍋 Little Lemon Restaurant – iOS App

A modern iOS application built with **SwiftUI** that showcases restaurant locations, menu items, and reservation management features. This project demonstrates the integration of **Core Data**, state management, and clean UI architecture in a real-world restaurant scenario.

## 🚀 Features

* 📍 Browse multiple restaurant locations with detailed information
* 🍽️ View menu items including dishes and desserts
* 🧾 Manage customer-related data using Core Data
* 📱 Smooth and responsive UI built with SwiftUI
* 🔄 Persistent local storage with Core Data integration
* 🧠 State-driven navigation and UI updates

## 🏗️ Architecture

The project follows a modular and scalable structure:

* **SwiftUI Views** for UI rendering
* **ObservableObject (Model layer)** for state management
* **Core Data** for persistence and data handling
* **PersistenceController** for managing the Core Data stack

This approach ensures separation of concerns and maintainability.

## 🗂️ Project Structure

* `MainView.swift` → Root navigation with TabView
* `Model.swift` → Application state and business logic
* `LocationsView.swift` → Displays restaurant locations
* `RestaurantView.swift` → Individual restaurant UI component
* `CORE DATA/` → Core Data entities and persistence setup

  * `Dish`, `Dessert`, `Customer`, `Location` entities
  * `Persistence.swift` for Core Data configuration

## 💾 Data Persistence

The app uses **Core Data** to store:

* Restaurant locations
* Menu items (dishes & desserts)
* Customer information

The `PersistenceController` handles the Core Data stack and context management.

## 📱 Technologies Used

* Swift
* SwiftUI
* Core Data
* MVVM-inspired architecture

## 🎯 Purpose

This project was developed to strengthen skills in:

* Native iOS development with SwiftUI
* Data persistence using Core Data
* App architecture and state management
* Building scalable and maintainable mobile applications

## 🔧 Future Improvements

* 🌐 Remote API integration
* 🔍 Search & filtering functionality
* ⭐ Favorites system
* 🛒 Order management system
* 🎨 UI/UX enhancements

## 👨‍💻 Author

Developed by a Software Engineering student focused on **iOS development and mobile technologies**.

---
