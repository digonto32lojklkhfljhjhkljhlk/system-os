# SYSTEM OS — Real Life RPG

React + Vite starter with a robotic 4-digit PIN page, dashboard, daily quests, skill tree and achievements.

## Run
1. Install Node.js.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`

## Change PIN
Open `src/App.jsx` and change `const SYSTEM_PIN="1234";` to your own four digits.

## Build
Run `npm run build`. Production output is in `dist`.

## Storage and security
No database, cloud storage, account system, localStorage or sessionStorage is used. XP and quest progress exist only in memory and reset after refresh. The PIN is visible in client-side source code, so it is a simple entry screen, not strong security.