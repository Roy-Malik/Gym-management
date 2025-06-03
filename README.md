# 🏋️ AuraFit - Gym Management System (Admin Dashboard)

AuraFit is a modern, responsive, and beautifully animated **Gym Management System Dashboard** built using:

- ⚛️ React (via Vite)
- 💨 Tailwind CSS
- 🌀 Framer Motion
- 🧠 TypeScript
- 📊 Recharts
- 🧩 Modular Component Design

---

## 📦 Tech Stack

| Tech             | Purpose                          |
|------------------|----------------------------------|
| React            | UI Framework                     |
| TypeScript       | Type Safety                      |
| Vite             | Lightning-fast dev server        |
| Tailwind CSS     | Styling                          |
| Framer Motion    | Animations & transitions         |
| React Router DOM | Routing                          |
| Recharts         | Charts & Data Visuals            |

---

## 🚀 Getting Started

### 1. **Clone or Download the Project**
```bash
git clone https://github.com/your-username/aura-fit.git
cd aura-fit
2. Install Dependencies
bash
Copy
Edit
npm install
3. Run Development Server
bash
Copy
Edit
npm run dev
Navigate to http://localhost:5173 in your browser.

🗂️ Project Structure
bash
Copy
Edit
.
├── components/          # Reusable UI components
│   ├── Layout.tsx
│   ├── Sidebar.tsx
│   ├── Navbar.tsx
│   └── ui/              # Button, Card, Tooltip etc.
├── pages/               # Page-level components (TrainerDashboard, MemberDashboard, etc.)
├── App.tsx              # Main routing & layout
├── index.tsx            # Entry point
├── vite.config.ts       # Vite configuration
└── tailwind.config.js   # Tailwind theme config
🎨 Custom Theme
Custom Tailwind theme includes:

brand-background: #121828 (deep navy)

brand-primary: #D4AF37 (muted gold)

brand-surface, brand-border, and more

Typography uses:

"Playfair Display" for elegant headings

Inter for clean body text

📈 Features
Role-based UI (Admin, Trainer, Member)

Responsive design (mobile-first)

Animated transitions with Framer Motion

Dark Mode enabled

Modular and scalable architecture
