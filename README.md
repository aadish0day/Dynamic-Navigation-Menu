# 🚀 Dynamic Navigation Menu & Modern Landing Page

[![React](https://img.shields.io/badge/React-18.3-blue?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite)](https://vitejs.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A professional, high-performance landing page template featuring a dynamic navigation system, smooth scrolling, and a fully responsive modern UI. Built with the latest web technologies for speed and developer experience.

![Project Preview](https://via.placeholder.com/1200x600?text=Dynamic+Navigation+Menu+Preview)

## ✨ Features

- **🎯 Dynamic Navigation:** Smart navbar that transitions styling on scroll and supports active section tracking.
- **📱 Fully Responsive:** Optimized for all devices, from mobile phones to high-resolution desktops.
- **🌊 Smooth Scrolling:** Native-feeling smooth scroll navigation to internal page sections.
- **🎨 Modern UI/UX:** Clean, professional design using Tailwind CSS with glassmorphism effects and smooth animations.
- **⚡ Performance First:** Built with Vite for lightning-fast HMR and optimized production builds.
- **🛠️ Production Ready:** Includes Docker configuration, ESLint, and TypeScript type-checking.

## 🛠️ Tech Stack

- **Frontend:** React 18, TypeScript
- **Styling:** Tailwind CSS, Lucide React (Icons)
- **Build Tool:** Vite
- **Containerization:** Docker, Docker Compose
- **Backend Ready:** Pre-configured for Supabase integration

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Docker](https://www.docker.com/) (Optional, for containerized deployment)

### Local Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Dynamic-Navigation-Menu.git
   cd Dynamic-Navigation-Menu
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser.

### 🐳 Running with Docker

You can spin up the entire environment using Docker Compose:

```bash
docker-compose up -d --build
```
The application will be accessible at [http://localhost:3000](http://localhost:3000).

## 📁 Project Structure

```text
Dynamic-Navigation-Menu/
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── Navigation.tsx # Dynamic Navbar logic
│   │   ├── Hero.tsx       # Hero section with animations
│   │   ├── Features.tsx   # Feature grid
│   │   ├── About.tsx      # About section
│   │   ├── Contact.tsx    # Contact form with validation
│   │   └── Footer.tsx     # Footer component
│   ├── App.tsx           # Main application shell
│   ├── main.tsx          # Entry point
│   └── index.css         # Global styles & Tailwind imports
├── public/               # Static assets
├── Dockerfile            # Production Docker image config
├── docker-compose.yml    # Docker orchestration
└── tailwind.config.js    # Tailwind CSS configuration
```

## 🛠️ Scripts

- `npm run dev`: Start development server.
- `npm run build`: Build for production.
- `npm run lint`: Run ESLint for code quality.
- `npm run typecheck`: Run TypeScript compiler checks.
- `npm run preview`: Preview the production build locally.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with ❤️ by [Your Name/Organization]
