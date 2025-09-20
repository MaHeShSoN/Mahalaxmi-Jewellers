# 💎 Mahalaxmi Jewellers - Android App

A comprehensive Android application for **Mahalaxmi Jewellers**, a premium jewelry showroom located in Pipar City, Jodhpur, Rajasthan. The app showcases an extensive collection of traditional and modern jewelry with seamless ordering capabilities.

## 📱 About the App

Mahalaxmi Jewellers has been a recognized name in the gems and jewelry business since 2009. This mobile app brings their stunning jewelry collections directly to customers' fingertips, featuring handpicked and exclusive designs in gold and diamond jewelry.

## ✨ Key Features

### 🛍️ Product Catalog
- **Comprehensive Categories**: Rings, Chains, Earrings, Sets, Mangal Sutra, Payal, Chudiyan, and more
- **Traditional & Modern Designs**: From classic styles to bespoke pieces
- **High-Quality Images**: Detailed product photography with zoom functionality
- **Bilingual Support**: Available in both Hindi and English

### 💬 Direct Ordering
- **WhatsApp Integration**: Direct contact with Hari Kishan Soni (9828441285)
- **Instant Messaging**: Send product inquiries and place orders via WhatsApp
- **Contact Information**: Easy access to store contact details

### 📊 Gold Price Tracking
- **Real-time Updates**: Current gold and silver prices
- **Price Calculator**: Built-in tools for price estimation
- **Market Trends**: Stay updated with jewelry market rates

### 🏪 Store Information
- **Location Details**: Complete address and directions
- **Business Hours**: Store timings and availability
- **About Us**: Company history and expertise
- **Services**: Bridal trousseau, jewelry upgrade, and redesigning services

### 🔐 User Features
- **User Authentication**: Secure login and verification system
- **Privacy Policy**: Transparent data handling policies
- **App Sharing**: Easy sharing with friends and family
- **Offline Support**: Basic functionality without internet

## 🛠️ Technical Stack

- **Language**: Kotlin
- **Architecture**: MVVM with Android Navigation
- **Backend**: Firebase (Firestore, Authentication, Storage, Analytics)
- **UI**: Material Design 3
- **Image Loading**: Coil
- **Networking**: Firebase SDK
- **Ads**: Google AdMob
- **Updates**: Google Play Core

## 📋 Requirements

- **Android Version**: 8.0 (API 26) or higher
- **Target SDK**: 34
- **Minimum SDK**: 26
- **Internet Connection**: Required for full functionality

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/MLJ12.git
   cd MLJ12
   ```

2. **Open in Android Studio**
   - Open Android Studio
   - Select "Open an existing project"
   - Navigate to the cloned repository folder

3. **Configure Firebase**
   - Add your `google-services.json` file to the `app/` directory
   - Update Firebase configuration in the Firebase console

4. **Build and Run**
   - Sync project with Gradle files
   - Build the project
   - Run on device or emulator

## 📁 Project Structure

```
app/
├── src/main/
│   ├── java/com/mljca/MahalaxmiJewellers/
│   │   ├── Activity/           # App activities
│   │   │   ├── MainActivity.kt
│   │   │   ├── LoginActivity.kt
│   │   │   ├── AboutUs.kt
│   │   │   └── ...
│   │   └── Fragment/           # App fragments
│   ├── res/                    # Resources
│   │   ├── layout/            # XML layouts
│   │   ├── values/            # Strings, colors, styles
│   │   └── drawable/          # Images and icons
│   └── AndroidManifest.xml
├── build.gradle               # App-level dependencies
└── google-services.json       # Firebase configuration
```

## 🎯 Main Activities

- **SplashActivity**: App launch screen
- **MainActivity**: Main navigation and product display
- **LoginActivity**: User authentication
- **AboutUs**: Company information and history
- **ContactUs**: Store contact details
- **MessageUs**: Customer support and inquiries
- **Gold_Change**: Gold price tracking and updates

## 🔧 Dependencies

### Core Libraries
- `androidx.appcompat:appcompat:1.7.0`
- `androidx.constraintlayout:constraintlayout:2.1.4`
- `com.google.android.material:material:1.12.0`

### Firebase
- `com.google.firebase:firebase-firestore-ktx`
- `com.google.firebase:firebase-auth-ktx`
- `com.google.firebase:firebase-storage-ktx`
- `com.google.firebase:firebase-analytics-ktx`

### UI & Navigation
- `androidx.navigation:navigation-fragment-ktx:2.7.7`
- `androidx.navigation:navigation-ui-ktx:2.7.7`
- `de.hdodenhof:circleimageview:3.1.0`

### Image Loading
- `io.coil-kt:coil:2.6.0`

## 📞 Contact Information

**Store Details:**
- **Owner**: Hari Kishan Soni
- **Phone**: +91 9828441285, +91 9166770604
- **Address**: Ganash Mandir ka Pass, Iilaji Bazar, Pipar City, Jodhpur, Rajasthan, 342601, India

**Developer Contact:**
- **Developer**: Mahesh Soni
- **Email**: sonim1234567@gmail.com

## 📄 License

This project is developed for Mahalaxmi Jewellers. All rights reserved.

## 🤝 Contributing

This is a proprietary application for Mahalaxmi Jewellers. For any suggestions or improvements, please contact the developer.

## 📱 Screenshots

<div align="center">
  <img width="200" height="355" alt="App Screenshot 1" src="https://github.com/user-attachments/assets/eefecf75-5131-474a-9f7e-363909a668f2" />
  <img width="200" height="355" alt="App Screenshot 2" src="https://github.com/user-attachments/assets/f530d386-902b-4a71-8708-333aa7f5fa5c" />
  <img width="200" height="355" alt="App Screenshot 3" src="https://github.com/user-attachments/assets/ac464a1e-7c24-4c1e-84cc-abd5c48c1a4b" />
  <img width="200" height="355" alt="App Screenshot 4" src="https://github.com/user-attachments/assets/4793e764-0c3c-4fff-847b-d255a05b7da6" />
</div>

## 🔄 Version History

- **v11** - Current version with enhanced UI and Firebase integration
- **v10** - Added WhatsApp integration and improved navigation
- **v9** - Implemented user authentication and privacy policy

## 🌟 Features in Development

- [ ] Online payment integration
- [ ] Wishlist functionality
- [ ] Push notifications for new arrivals
- [ ] AR try-on feature
- [ ] Multi-language support expansion

---

**Developed with ❤️ for Mahalaxmi Jewellers**

*Bringing traditional jewelry craftsmanship to the digital age*
