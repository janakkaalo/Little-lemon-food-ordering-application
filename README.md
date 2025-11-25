# Little Lemon Food Ordering Application 🍋

![Little Lemon Logo](assets/Logo.png)

A delightful food ordering mobile application for Little Lemon restaurant, built with React Native and Expo. This app allows users to browse the menu, customize orders, and manage their profiles seamlessly across Android, iOS, and Web platforms.

## ✨ Features

- **🍽️ Menu Browsing**: Explore a curated selection of dishes with beautiful images and descriptions
- **🔍 Smart Filtering**: Filter menu items by categories, dietary preferences, and price ranges
- **👤 User Authentication**: Secure login and profile management
- **🛒 Order Management**: Add items to cart, customize orders, and track order history
- **📱 Cross-Platform**: Runs natively on Android, iOS, and Web
- **💾 Offline Support**: Local SQLite database for offline functionality
- **🎨 Modern UI**: Clean, intuitive interface with Material Design components

## 🚀 Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (version 16 or higher) - [Download here](https://nodejs.org/)
- **Expo CLI** - Install globally via npm:
  ```bash
  npm install -g @expo/cli
  ```
- **Git** - For cloning the repository

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Little-lemon-food-ordering-application
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Run on your preferred platform**
   - **Android**: `npm run android`
   - **iOS**: `npm run ios` (macOS only)
   - **Web**: `npm run web`

## 📱 Usage

1. **Onboarding**: New users will go through a quick onboarding process
2. **Browse Menu**: Explore dishes on the Home screen with filtering options
3. **Customize Orders**: Select items, choose preferences, and add to cart
4. **Profile Management**: Update personal information and view order history

## 🛠️ Tech Stack

- **Framework**: React Native with Expo
- **Navigation**: React Navigation v6
- **UI Components**: React Native Paper
- **Database**: Expo SQLite for local storage
- **State Management**: React Context API
- **Icons**: React Native Vector Icons
- **Image Handling**: Expo Image Picker

## 📂 Project Structure

```
Little-lemon-food-ordering-application/
├── assets/              # Static assets (images, fonts)
├── components/          # Reusable UI components
│   ├── Filters.js       # Menu filtering component
│   ├── Header.js        # App header
│   ├── PrimaryButton.js # Custom button component
│   └── Title.js         # Title component
├── contexts/            # React contexts for state management
│   └── AuthContext.js   # Authentication context
├── screens/             # App screens
│   ├── Home.js          # Main menu screen
│   ├── Onboarding.js    # User onboarding
│   ├── Profile.js       # User profile
│   └── Splash.js        # App splash screen
├── utils/               # Utility functions
├── App.js               # Main app component
├── database.js          # Database configuration
└── package.json         # Project dependencies
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact our support team.

---

*Made with ❤️ for Little Lemon restaurant*</content>