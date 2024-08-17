# Golds Gym - Fitness App

Welcome to **Golds Gym**, the ultimate fitness app designed to help you discover and perform a wide range of exercises! This app leverages the power of RapidAPI's ExerciseDB and YouTube Search APIs to bring you an extensive database of exercises with practical examples and related video content.

## Features

- **Exercise Categories & Muscle Groups**: Easily browse exercises by categories and target specific muscle groups.
- **Pagination**: Navigate through exercises efficiently with a user-friendly pagination system.
- **Exercise Details**: Get in-depth details about each exercise, including instructions and benefits.
- **Related YouTube Videos**: Pull and display related workout videos directly from YouTube.
- **Similar Exercises**: Discover similar exercises to diversify your workout routine.
- **Beautiful User Interface**: A sleek and intuitive UI designed using Material UI (version 5).

## Technologies Used

- **React.js**: Frontend framework for building a responsive and dynamic user interface.
- **Material UI (v5)**: Provides the app with a modern and visually appealing design.
- **Styled Components & Emotion**: For advanced CSS styling in JavaScript.
- **React Horizontal Scrolling Menu**: For smooth horizontal scrolling features.
- **React Loader Spinner**: For displaying loading indicators.
- **Vite**: A fast development server and build tool for modern web projects.
- **ESLint**: For ensuring code quality and consistency.

## Getting Started

To get started with the Golds Gym app, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/mjaffal21/Gym-Exercise.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd golds-gym
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up environment variables:**

   Create a .env file in the root directory and add your RapidAPI keys:

   ```bash
   VITE_RAPID_API_KEY = YOUR_RAPID_API_KEY
   VITE_RAPID_API_HOST = YOUR_RAPID_API_HOST
   VITE_RAPID_API_HOST_YOUTUBE = YOUR_RAPID_API_HOST_YOUTUBE
   ```

5. Run the application:

   ```bash
   npm run dev
   ```
