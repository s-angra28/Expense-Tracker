📊 Mini Expense Tracker


**Live Demo:**  https://mexpense-tracker.netlify.app/ 

A high-performance financial dashboard engineered for real-time data tracking and visualization. This project focuses on state persistence, modular component architecture, and accessible UI/UX.


🚀 Key Engineering Features

    Real-time State Sync: Implemented instant UI synchronization for expense lifecycle management (Create/Delete) using optimized React hooks.

    Dynamic Data Visualization: Architected a responsive horizontal bar chart using Recharts, providing categorical spending breakdowns and data-driven insights.

    Resilient Data Persistence: Engineered a local storage integration layer to ensure data integrity across browser sessions and page refreshes.

    Responsive & Accessible Design: Built with a mobile-first strategy using Tailwind CSS, ensuring WCAG-compliant accessibility and seamless layouts across all breakpoints.

    Smart Validation Logic: Integrated robust form validation to maintain data hygiene and prevent malformed entries.

🛠️ Tech Stack

    Core: React.js (Vite)

    Architecture: Component-Based Design

    Styling: Tailwind CSS

    Data Visualization: Recharts / Custom SVG Components

    State Management: React Hooks (useState, useEffect)

    Deployment: Netlify

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

⚙️ Installation & Development

To get the environment running locally:

    Clone the repository
    Bash

    git clone https://github.com/s-angra28/Expense-Tracker.git

    Navigate to the workspace
    Bash

    cd Expense-Tracker

    Install dependencies
    Bash

    npm install

    Launch development server
    Bash

    npm run dev

    The application will be served at http://localhost:5173.
