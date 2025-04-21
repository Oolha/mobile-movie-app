# Movie Finder

A mobile app for discovering and exploring movies with real-time data and personalized recommendations.

## 📱 Overview

**Movie Finder** is a React Native application built with Expo, TypeScript, and Tailwind CSS. The app fetches movie data in real-time and implements a popularity algorithm using Appwrite to rank movies based on user engagement. Designed with modern UI/UX principles, it provides a responsive and visually appealing interface while ensuring scalability and performance.

## 📱 Live Demo

Try out the Movie Finder app on your mobile device using Expo Go:

![Expo QR Code](./assets/images/qrCode.png)

[![Expo](https://img.shields.io/badge/Expo-Run%20in%20Expo-blue.svg?style=flat-square&logo=expo&logoColor=white)]

Simply scan the QR code with your device's camera (iOS) or through the Expo Go app (Android).

## ⚙️ Tech Stack

- **Expo** - React Native framework for cross-platform development
- **React Native** - Mobile application framework
- **Appwrite** - Backend as a Service (BaaS) for data storage and authentication
- **TypeScript** - Strongly typed programming language
- **Tailwind CSS (NativeWind)** - Utility-first CSS framework for styling

## 🔋 Features

- **Real-time data**: Fetches and displays up-to-date movie information
- **Home Page**: Featured and discover sections for movie exploration
- **Search Functionality**: Find your favorite movies quickly and easily
- **Popularity Algorithm**: Tracks user searches to highlight trending movies
- **Movie Details**: Comprehensive information about selected movies
- **Responsive Design**: Optimized for various screen sizes
- **Type Safety**: Strong typing with TypeScript for improved development experience
- **Modular Architecture**: Reusable components and services for maintainability
- **Smooth Navigation**: Seamless transition between screens

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed:

- Git
- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Oolha/mobile-movie-app.git
   cd mobile-movie-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a new file named `.env` in the root of your project and add the following content:

   ```
   EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_appwrite_database_id
   EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

   Replace the placeholder values with your actual credentials from TMDB and Appwrite.

4. Start the development server:

   ```bash
   npx expo start
   ```

5. Open the app:
   - Use Expo Go on your mobile device to scan the QR code, or
   - Press `i` to open in iOS simulator or `a` for Android emulator

## 🙏 Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for providing the movie data API
- [Appwrite](https://appwrite.io/) for the backend services
- [Expo](https://expo.dev/) for the development framework
- [NativeWind](https://www.nativewind.dev/) for styling
