📊 Mini Expense Tracker


Live Demo: https://mexpense-tracker.netlify.app/

GitHub: https://github.com/s-angra28/Expense-Tracker

Expense Tracker | React.js Financial Dashboard

A responsive financial tracking application built with React.js that enables users to manage daily expenses and visualize spending patterns through interactive charts. Focused on clean UI, data persistence, and modular component design.

Key Features
Expense Management (CRUD): Add and delete expenses with real-time UI updates using React hooks.
Data Visualization: Integrated a responsive bar chart using Recharts to display category-wise spending insights.
Persistent Storage: Implemented localStorage to retain user data across sessions and page refreshes.
Responsive UI: Built with Tailwind CSS using a mobile-first approach for seamless experience across devices.
Form Validation: Added input validation to ensure clean and consistent data entry.

🛠️ Tech Stack

React.js (Vite)
Tailwind CSS
Recharts
React Hooks (useState, useEffect)
LocalStorage API
Netlify (Deployment)





📂 Project Architecture
Plaintext

src/
├── components/
│   ├── ExpenseForm.jsx       # Logic for data entry and input validation
│   ├── ExpenseBarChart.jsx   # Recharts integration for data visualization
│   ├── ExpenseSummary.jsx    # Business logic for calculations and list state
│   ├── Hero.jsx              # Branding and entry UI
│   └── Footer.jsx            # Metadata and credits
├── App.jsx                   # Central logic, state management, and persistence layer
└── main.jsx                  # Application entry point





