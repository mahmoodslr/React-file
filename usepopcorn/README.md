# Usepopcorn
This project includes a React-based star rating component along with two custom hooks: `useKey` and `useLocalStorageState`. These utilities help in handling keyboard events and managing local storage state in a React application.

## Features
- A customizable star rating component with interactive UI.
- A hook for listening to specific key presses (`useKey`).
- A hook for persisting state using local storage (`useLocalStorageState`).

## Components
### `StarRating`
A fully customizable star rating component.
Props:
- `maxRating` (number): Maximum number of stars (default: 5).
- `defaultRating` (number): Default selected rating (default: 0).
- `color` (string): Color of the stars (default: #fcc419).
- `size` (number): Size of the stars in pixels (default: 48).
- `messages` (array): An array of messages for each rating.
- `className` (string): Custom class for styling.
- `onSetRating` (function): Callback function when the rating is changed.

## Custom Hooks
### `useKey`
A hook for detecting key presses and executing a callback function.
Parameters:
- `key` (string): The key to listen for (e.g., 'Enter').
- `action` (function): The function to execute when the key is pressed.

### useLocalStorageState
A hook for persisting state using local storage.
Parameters:
- `initialState` (any): The default state value.
- `key` (string): The local storage key name.

--- 
<img src="https://github.com/user-attachments/assets/767d5d8a-952d-4d02-a7c3-399b43fd495e" width="400" height="250" style="border: 2px solid #ccc; border-radius: 10px; box-shadow: 3px 3px 10px rgba(0,0,0,0.1);" /> 
