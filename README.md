# MoodPalette-2-Daily-Mood-Tracker

## Description
A simple and visually appealing web app that allows users to log their daily moods and view them as a colorful calendar heatmap.

## Tech Stack
- React

## Requirements
- Mood selection interface (using emoji or color buttons for mood selection)
- Calendar heatmap display (mapping moods to colors on a monthly grid)
- Local storage persistence (saving moods locally so data stays after refresh)

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/your-username/MoodPalette-2-Daily-Mood-Tracker.git
   
2. Navigate to the project directory:
   bash
   cd MoodPalette-2-Daily-Mood-Tracker
   
3. Install dependencies:
   bash
   npm install
   # or
   yarn install
   
4. Start the development server:
   bash
   npm start
   # or
   yarn start
   
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
1. Select your mood for the current day using the emoji or color buttons.
2. View your mood entries rendered on the calendar heatmap.
3. Refresh or revisit the page to see your previously logged moods (data persists in local storage).

## Implementation Steps
1. Scaffold the React application using Create React App.
2. Create a `MoodSelector` component that displays emoji/color buttons and handles mood selection.
3. Create a `CalendarHeatmap` component to render a monthly grid and map saved moods to colored cells.
4. Implement a `useLocalStorage` hook or service to persist and retrieve mood entries from `localStorage`.
5. Manage application state (selected moods and entries) in the main `App` component.
6. Wire up event handlers to update local storage and re-render the heatmap on mood changes.
7. Apply styling for a clean, visually appealing interface.
8. Test the application in development mode and verify data persistence across refreshes.