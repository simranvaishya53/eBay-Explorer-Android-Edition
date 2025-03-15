# 🛍️ eBay Explorer: Android Edition

## 📌 Overview
**eBay Explorer: Android Edition** is a mobile application that enables users to **search for products on eBay**, view product details, manage a wishlist, and share products on Facebook. The app follows **Google's Material Design** principles and integrates a **Node.js backend** for handling API requests efficiently.

## 🚀 Features
- 🔍 **Product Search:** Search for eBay products with category, condition, and shipping filters.
- 📋 **Search Results:** Display results in a **scrollable RecyclerView** with product details.
- 🛒 **Product Details:** View specifications, shipping info, seller details, and similar products.
- ❤️ **Wishlist:** Save favorite items and persist them using **MongoDB on AWS/GCP/Azure**.
- 🖼️ **Google Images:** Fetch product-related images via **Google Custom Search API**.
- 📲 **Facebook Sharing:** Share product details directly to Facebook.
- 📍 **User Location:** Retrieve current location using **Google Play Services or IP-based APIs**.
- 🎨 **Dynamic UI & Sorting:** Implement sorting techniques for search results and wishlist items.

## 🛠 Tech Stack
- **📝 Languages:** Kotlin, Java, XML
- **📦 Frameworks & Libraries:**
  - ⚙️ **Android SDK**
  - 🌐 **Volley** (HTTP Requests)
  - 🖼️ **Picasso/Glide** (Image Loading)
  - 📜 **RecyclerView** (UI Display)
  - 📑 **ViewPager** (Tabbed Navigation)
  - 🗺️ **Google Maps API** (Location Services)
  - 🗄️ **MongoDB** (Cloud-based Wishlist Storage)
  - 🛠 **Node.js & Express.js** (Backend Services)

## 🔗 Backend Integration
The **Node.js backend** is responsible for:
- Fetching product details from the **eBay API**.
- Retrieving **Google Custom Search images**.
- Managing the **wishlist** stored in **MongoDB**.
- Handling **user authentication and API requests**.

## 📲 Screenshots
![🔍 Search Page](https://via.placeholder.com/400x300)
![📋 Search Results](https://via.placeholder.com/400x300)
![🛒 Product Details](https://via.placeholder.com/400x300)

## 🔧 Setup & Installation
1. 📥 Clone this repository:
   ```bash
   git clone https://github.com/yourusername/eBay-Explorer-Android-Edition.git
   cd eBay-Explorer-Android-Edition
   ```
2. 🏗️ Open the project in **Android Studio**.
3. 🔄 Install dependencies and sync the Gradle project.
4. 🔑 Set up **Google API Keys** for Maps and Custom Search.
5. 🖥️ Configure the **Node.js backend** (hosted on AWS/GCP/Azure).
6. 📱 Run the app on an emulator or a physical device.

## 📡 API Integration
- 🛍️ **eBay API:** Fetch product details, prices, and seller info.
- 🔎 **Google Custom Search API:** Retrieve related product images.
- 📲 **Facebook API:** Enable product sharing.

## 🐞 Error Handling
- ⚠️ Displays **Toast messages** for validation errors.
- 🌐 Handles network failures gracefully with appropriate error messages.
- 🔄 Ensures data consistency across app states.

## 💡 Future Enhancements
- 🌙 Implement **dark mode**.
- 🔔 Add **push notifications** for wishlist updates.
- ⚡ Optimize search queries for faster results.

---
