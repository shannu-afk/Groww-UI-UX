# TradePro - Advanced Trading Platform

A modern, responsive trading platform built with Next.js, featuring real-time market data, interactive charts, and a sleek dark theme UI. TradePro provides traders with comprehensive tools for stock analysis, portfolio management, and market insights.

---

## 🌟 Features

### Core Functionality
- Real-time Market Data for NIFTY50, SENSEX, BANKNIFTY
- Candlestick charts with timeframes: 5M, 10M, 15M, 30M, 1H
- Detailed stock analysis pages with technical indicators
- Real-time options chain data (Call/Put)
- Portfolio tracking with market insights
- Live index movements with percent changes

### User Experience
- Responsive design for desktop, tablet, and mobile
- Modern dark UI with blue accents
- Smooth animations with Framer Motion
- Mobile-friendly hamburger menu
- Fast global stock search

### Trading Tools
- Price alerts
- Watchlist
- Technical charting tools
- Educational resources

---

## 🛠️ Tech Stack

### Frontend
- Next.js 14
- React 18
- TypeScript

### UI / Styling
- Tailwind CSS
- Framer Motion
- Lucide React
- shadcn/ui

### Visualization
- React Google Charts

### Development Tools
- ESLint
- PostCSS
- Tailwind CSS Animate

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn or pnpm

### Installation

Clone the repository:
    git clone https://github.com/shannu-afk/Groww-UI/UX.git

Install dependencies:
    npm install
    # or
    yarn install
    # or
    pnpm install

Run development server:
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev

Open your browser:
    http://localhost:3000

### Build for Production

Build the project:
    npm run build

Start production server:
    npm start

---

## 📁 Project Structure

    ui-ux-Trade-pro-main/
    ├── src/
    │   ├── app/
    │   │   ├── dashboard/
    │   │   │   ├── [id]/page.jsx        # Stock detail pages
    │   │   │   └── page.tsx             # Dashboard
    │   │   ├── layout.tsx               # Root layout
    │   │   ├── page.tsx                 # Landing page
    │   │   └── globals.css              # Global styles
    │   ├── components/
    │   │   └── ui/button.tsx            # Reusable button
    │   └── lib/utils.ts                 # Utility functions
    ├── public/
    ├── next.config.mjs
    ├── package.json
    ├── tailwind.config.ts
    ├── tsconfig.json
    └── README.md

---

## 🎯 Key Components

### Pages
- Landing page
- Dashboard
- Stock details

### Layout
- Header + Footer global layout
- Mobile navigation

### Features
- Live indices overview
- Stock cards
- Candlestick charts
- Options chain table
- Open interest indicators

---

## 🔧 Available Scripts

    npm run dev       # Start dev server
    npm run build     # Build project
    npm start         # Run production build
    npm run lint      # Lint code

---

## 🌐 Deployment

### Deploy on Vercel
- Connect GitHub repository
- Auto build on push

### Other hosting options
- Netlify
- AWS Amplify
- DigitalOcean
- Docker

---

## 🤝 Contributing

    git checkout -b feature/my-feature
    git commit -m "Add my feature"
    git push origin feature/my-feature

### Guidelines
- Use TypeScript best practices
- Tailwind for styling
- Ensure responsive UI
- Proper error handling
- Clean coding standards

---
