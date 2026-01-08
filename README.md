# Description

Group Project MyHerbalWise is a React-based web app that promotes Chinese herbal wellness through an accessible, modern UI. It lets users explore herbs, teas, and remedies with structured information and clear categorization. The project focuses on responsive design, intuitive navigation, and a visually calm experience suitable for both desktop and mobile visitors.

## Registration and Login Functions

The live site does not allow Registration and Login as a member.

Registration and Login functions require running npm run server on your local computer.

- Frontend: React (component-driven architecture, modular UI components)
- Backend: Node.js, Express.js (RESTful APIs)
- Filtering Logic: Client-side  array.filter() + map()  for real-time herb search by category/properties.
- State Synchronization: Frontend memoization with React  useMemo  to optimize re-renders during search/filter operations.

## Core Architecture

- Component-based React frontend: Modular UI with reusable components for search, modals and forms. State management via Context API for seamless user flows.
- Express.js REST API: Lightweight backend serving user data, recommendations, and health records. Structured endpoints for data filtering.

## Key Features & Implementation

# Search & Filtering
Real-time input capture with debounced search.
Client-side dataset filtering using array methods ( filter ,  map ).

# Herb Details Modal
Dynamic popup displaying categorized data (type, properties, functions, usage instructions).

# Post-Login
- TCM Constitution Assessment: Questionnaire‑driven quiz analyzing user responses to classify constitution (e.g., cold, hot, qi deficiency). Results trigger personalized dietary plans by constitution, symptoms, and seasonal factors (24 solar terms).
- Symptom Tracking: Daily symptom logging with historical data.
- Diet Logging: Time-stamped meal records for health.
- Daily Meal Plans: Algorithm generates breakfast/lunch/dinner suggestions based on constitution quiz, symptoms, and seasonal TCM principles.
- Food Recommendations: Matches user constitution results to suitable ingredients with dietary restrictions and wellness tips.
