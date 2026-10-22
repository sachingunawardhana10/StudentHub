# StudentHub – Mobile Application Development Practical 03

A mini student hub built with **React Native** and **Expo Router** for the University of Kelaniya's Mobile Application Development practical tutorial.

The project demonstrates bottom-tab navigation, nested stack navigation, a student dashboard, a digital ID card details screen, and a live-updating clock using `useEffect` and `setInterval`.

## Learning Objectives

- Set up bottom tabs with a stack navigator nested inside.
- Use `ScrollView` and `Pressable` to improve the user interface and user experience.
- Display a local image in a React Native screen.
- Simulate a periodic background task with a live-updating clock.

## Technologies

- React Native
- Expo
- Expo Router
- TypeScript / TSX
- `@expo/vector-icons`

## Project Structure

```text
StudentHub/
├── app/
│   ├── _layout.tsx
│   ├── clock.tsx
│   └── (home)/
│       ├── _layout.tsx
│       ├── index.tsx
│       └── details.tsx
├── assets/
│   └── images/
│       └── user.png
├── Output_Screens/
└── README.md
```

## Getting Started

### Prerequisites

- Node.js and npm installed.
- Expo-compatible development environment.
- Expo Go or an appropriate simulator/device.

### Install and Run

If you have not created the project yet:

```bash
npx create-expo-app StudentHub
cd StudentHub
npm run reset-project
npx expo install @expo/vector-icons
```

If the project already exists, open a terminal in the project directory and install dependencies as needed:

```bash
npm install
npx expo install @expo/vector-icons
```

Start the development server:

```bash
npx expo start
```

## Author

- Name: Sachin Gunawardhana
- Student ID: PS/2022/200
- Course: Mobile Application Development
- Practical: Tutorial 03 – Navigation, Components & Background Tasks
