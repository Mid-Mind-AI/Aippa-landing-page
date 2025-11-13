# AIPPA Landing Page

A modern, responsive landing page for AIPPA - an AI-powered healthcare management platform.

## Features

- 🎨 Modern UI built with Next.js and Tailwind CSS
- 🧩 Component-based architecture using shadcn/ui
- 📱 Fully responsive design
- ⚡ Optimized performance with Next.js 16
- 🎭 Smooth animations with Motion

## Tech Stack

- **Framework**: Next.js 16
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Animations**: Motion (Framer Motion)
- **Icons**: Lucide React

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn or pnpm

### Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

2. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
├── app/
│   ├── page.tsx          # Main page component
│   ├── layout.tsx        # Root layout
│   ├── globals.css       # Global styles
│   └── favicon.ico       # Site favicon
├── components/
│   ├── simple-header.tsx # Header component
│   ├── hero.tsx          # Hero section
│   ├── pain-points.tsx   # Pain points section
│   ├── features.tsx      # Features section
│   ├── about.tsx         # About section
│   ├── faq.tsx           # FAQ section
│   ├── menu-toggle.tsx   # Mobile menu toggle
│   └── ui/               # shadcn/ui components
│       ├── button.tsx
│       ├── card.tsx
│       ├── sheet.tsx
│       └── separator.tsx
├── lib/
│   └── utils.ts          # Utility functions
└── ...config files
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## License

Private project - All rights reserved

