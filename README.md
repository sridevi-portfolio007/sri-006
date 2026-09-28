# Cortex — AI Collaboration Workspace for Students

React + Vite + Tailwind CSS frontend (mock data, no backend).

## Run on Windows
1. Install Node.js LTS from https://nodejs.org
2. Unzip this folder, open it in VS Code (File > Open Folder)
3. Open the terminal (Ctrl+`) and run:
   ```
   npm install
   npm run dev
   ```
4. Open the URL shown (usually http://localhost:5173)

## Structure
- `src/data.js` — mock data and placeholder AI functions (`askAI`, `genPlan`). Replace these with real API calls.
- `src/components/ui.jsx` — reusable components (icons, Orb, Ring, Progress, Badge, Avatar, TaskCard, InsightCard)
- `src/pages/Pages.jsx` — Dashboard, AI Hub, Tasks, Study Planner, Team, Insights, Documents, Notifications
- `src/pages/Landing.jsx` — landing page
- `src/App.jsx` — layout: sidebar, header, mobile bottom nav

Build for production: `npm run build`
