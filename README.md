# 🕒 Digital Clock in React

A simple **digital clock** built using **React.js** that displays the current time in **12-hour format with AM/PM**. It updates every second using React Hooks.

## 🚀 Features

- Real-time clock display
- 12-hour format with AM/PM
- Zero-padded hours, minutes, and seconds
- Built using React functional components and hooks (`useState`, `useEffect`)

## 🧠 How It Works

- Initializes current time using `useState`.
- Uses `setInterval` in a `useEffect` to update the time every second.
- Converts 24-hour time to 12-hour format and pads digits with zero where needed.
- Cleans up interval on component unmount to prevent memory leaks.

## 📦 Usage

1. Copy the `DigitalClock.js` file into your React project.
2. Import and use the component in your `App.js`:

```jsx
import React from 'react';
import DigitalClock from './DigitalClock';

function App() {
  return (
    <div>
      <DigitalClock />
    </div>
  );
}

export default App;
