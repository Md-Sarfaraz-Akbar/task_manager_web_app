# Task Manager App

I built this task manager to keep track of my daily tasks and stay organized. It's a clean, responsive web app for managing todos efficiently.

## Features

- Add tasks with descriptions, priorities, and due dates
- Mark tasks as complete/incomplete
- Edit and delete tasks
- Filter tasks (all, pending, completed)
- Real-time stats dashboard
- Mobile-responsive design
- Data persists in browser storage

## Tech Stack Used

**Frontend:**
- React.js with hooks (useState, useEffect)
- Tailwind CSS for styling
- Lucide React for icons
- Browser localStorage for data persistence

No external backend needed - everything runs client-side.

## Setup Steps

### Prerequisites
- Node.js (version 14+)
- npm or yarn

### Installation

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Install required packages**
   ```bash
   npm install react react-dom lucide-react
   npm install -D tailwindcss postcss autoprefixer
   ```

3. **Initialize Tailwind**
   ```bash
   npx tailwindcss init -p
   ```

4. **Configure tailwind.config.js**
   ```javascript
   module.exports = {
     content: ["./src/**/*.{js,jsx,ts,tsx}"],
     theme: { extend: {} },
     plugins: [],
   }
   ```

5. **Add Tailwind to src/index.css**
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

6. **Start development server**
   ```bash
   npm run dev
   ```

Visit http://localhost:5173/ to view the app.

### Build for Production
```bash
npm run build
```

---
