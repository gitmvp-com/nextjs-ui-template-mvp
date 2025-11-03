# Next.js UI Template MVP

A clean, modern UI template built with Next.js 15, TypeScript, and Tailwind CSS. This is a UI-only MVP version featuring beautiful components, dark mode support, and smooth animations - without authentication, payments, or analytics.

## ✨ Features

- 🎨 **Modern UI Components** - Beautiful, reusable components
- 🌓 **Dark Mode** - Media query-based dark mode support
- ✨ **Smooth Animations** - Framer Motion animations throughout
- 📱 **Fully Responsive** - Mobile-first responsive design
- ⚡ **Next.js 15** - Latest Next.js with App Router
- 🎯 **TypeScript** - Full type safety
- 🎨 **Tailwind CSS** - Utility-first styling
- 🔄 **Scroll Animations** - Intersection Observer for scroll effects

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/gitmvp-com/nextjs-ui-template-mvp.git
cd nextjs-ui-template-mvp
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📦 What's Included

### UI Components

- **TypewriterEffect** - Animated typing effect
- **PricingSection** - Interactive pricing cards
- **VideoModal** - YouTube video modal
- **LoadingSpinner** - Loading indicator
- **Animated Cards** - Hover effects and transitions

### Features

- **Sticky Navigation** - Smooth scrolling navigation
- **Hero Section** - Eye-catching landing section
- **Feature Sections** - Multiple content sections
- **CTA Sections** - Call-to-action areas
- **Metrics Display** - Statistics showcase

## 🛠️ Built With

- [Next.js 15](https://nextjs.org/) - React framework
- [TypeScript 5](https://www.typescriptlang.org/) - Type safety
- [Tailwind CSS 3.4](https://tailwindcss.com/) - Styling
- [Framer Motion 12](https://www.framer.com/motion/) - Animations
- [Lucide React](https://lucide.dev/) - Icons
- [React Icons](https://react-icons.github.io/react-icons/) - Additional icons
- [React Scroll](https://www.npmjs.com/package/react-scroll) - Smooth scrolling

## 📖 Project Structure

```
├── app/
│   ├── layout.tsx       # Root layout
│   ├── page.tsx         # Home page
│   └── globals.css      # Global styles
├── components/
│   ├── TypewriterEffect.tsx
│   ├── PricingSection.tsx
│   ├── VideoModal.tsx
│   └── LoadingSpinner.tsx
├── public/              # Static assets
└── tailwind.config.ts   # Tailwind configuration
```

## 🎨 Customization

### Colors

Edit `tailwind.config.ts` to customize the color scheme:

```typescript
colors: {
  primary: {
    DEFAULT: '#A78BFA',
    light: '#C4B5FD',
    dark: '#8B5CF6',
  },
  // ... more colors
}
```

### Components

All components are in the `components/` directory and can be easily customized or extended.

## 🚀 Deployment

The easiest way to deploy is using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/gitmvp-com/nextjs-ui-template-mvp)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

This MVP is based on [ShenSeanChen/launch-mvp-stripe-nextjs-supabase](https://github.com/ShenSeanChen/launch-mvp-stripe-nextjs-supabase) - UI components and styling only, without authentication, payments, or analytics.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

Made with ❤️ using [GitMVP](https://gitmvp.com)
