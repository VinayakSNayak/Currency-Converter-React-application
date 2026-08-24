Currency Converter 💱

A responsive currency converter built using React.js and Tailwind CSS. It fetches exchange rates from a currency API and allows users to convert between different currencies.

Features
💱 Convert between multiple currencies
🔄 Swap From and To currencies
🌐 Fetch exchange rates using a REST API
⚛️ React Hooks (useState, useEffect, useId)
🪝 Custom Hook for fetching currency information
🧩 Reusable InputBox component
📱 Responsive UI using Tailwind CSS
Tech Stack
React.js
JavaScript
Tailwind CSS
REST API
Fetch API
Vite
How It Works
Select the From currency.
Enter the amount.
Select the To currency.
Click Convert.
The application uses the latest exchange rate from the API to calculate the converted amount.
Installation
git clone <your-repository-url>
cd currency-converter
npm install
npm run dev

Then open the local development URL shown by Vite.

Project Structure
src/
├── components/
│   ├── InputBox.jsx
│   └── index.js
├── hooks/
│   └── useCurrencyInfo.js
├── App.jsx
├── main.jsx
└── index.css
Learning

This project was built to practice React Hooks, custom hooks, API integration, reusable components, props, state management, and Tailwind CSS.
