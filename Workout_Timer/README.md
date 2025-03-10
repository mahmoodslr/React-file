# Workout Timer

## Overview
Workout Timer is a React application that helps users plan their workout sessions by selecting a workout type, adjusting sets, exercise speed, and break duration. The app dynamically calculates the total workout time and includes a sound toggle feature.

## Features
- Select different workout types with predefined exercises.
- Adjust the number of sets, exercise speed, and break duration.
- Dynamically calculates workout duration.
- Plays a click sound when changes are made (toggleable).
- Updates the document title with the selected workout.

## Components
### `App.js`
- Manages global state for sound settings.
- Displays the current time, updating every second.
- Determines the appropriate workout options based on the time of day.

### `Calculator.js`
- Accepts a list of workouts and calculates the total workout duration.
- Updates the document title based on the selected workout.
- Plays a click sound when settings are adjusted (if sound is enabled).

### `ToggleSounds.js`
- A simple button to enable or disable sound effects.

## Hooks
### `useEffect`
- Used in `App.js` to update time and manage interval cleanup.
- Used in `Calculator.js` to update document title and play sounds.

### `useMemo`
- Used in `App.js` to optimize workout options based on the time of day.

--- 
<img src="https://github.com/user-attachments/assets/50c3e4bf-0735-4aa8-ad3c-e1319701f083" width="400" height="250" style="border: 2px solid #ccc; border-radius: 10px; box-shadow: 3px 3px 10px rgba(0,0,0,0.1);" /> 

