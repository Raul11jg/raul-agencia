# AgenceX Landing Page

A modern, responsive landing page for a digital agency specializing in web development services. Built with Astro, TypeScript, and Tailwind CSS.

## 🌟 Features

- **Modern Design**: Clean, professional layout with dark/light mode support
- **Responsive**: Fully responsive design that works on all devices
- **Performance Optimized**: Built with Astro for lightning-fast loading
- **TypeScript**: Full TypeScript support for better development experience
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Component-based**: Modular component architecture for maintainability

## 🚀 Demo

### Live Preview
- **Light Mode**: ![Light Mode Demo](./screens/demoLight.webp)
- **Dark Mode**: ![Dark Mode Demo](./screens/demoDark.webp)

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/) - Static Site Generator
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS
- **Language**: TypeScript - Type-safe JavaScript
- **Build Tool**: Vite - Fast build tool and dev server

## 📦 Installation

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn package manager

### Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd agencex-astro
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the application

## 🚀 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## 📁 Project Structure

```
/
├── public/                 # Static assets
│   ├── images/            # Image assets
│   ├── logos/             # Logo files
│   └── favicon.svg        # Site favicon
├── screens/               # Demo screenshots
│   ├── demoLight.webp     # Light mode preview
│   └── demoDark.webp      # Dark mode preview
├── src/
│   ├── components/        # Reusable components
│   │   ├── blocks/        # Block components
│   │   ├── cards/         # Card components
│   │   ├── elements/      # Basic UI elements
│   │   ├── sections/      # Page sections
│   │   │   ├── Hero.astro     # Hero section
│   │   │   ├── Services.astro # Services section
│   │   │   ├── AboutUs.astro  # About section
│   │   │   ├── Projects.astro # Projects showcase
│   │   │   ├── Brands.astro   # Brand partners
│   │   │   └── CTA.astro      # Call-to-action
│   │   └── shared/        # Shared components
│   ├── layouts/           # Layout components
│   │   └── Layout.astro   # Main layout
│   ├── pages/             # Page components
│   │   └── index.astro    # Home page
│   └── utils/             # Utility functions
├── astro.config.mjs       # Astro configuration
├── tailwind.config.cjs    # Tailwind configuration
├── tsconfig.json          # TypeScript configuration
└── package.json           # Dependencies and scripts
```

## 🎨 Sections Overview

The landing page includes the following sections:

1. **Hero Section** - Main banner with call-to-action
2. **Brands Section** - Partner brands showcase
3. **Services Section** - Services offered
4. **About Us Section** - Information about the agency
5. **Projects Section** - Portfolio showcase
6. **CTA Section** - Call-to-action (currently commented out)

## 🔧 Customization

### Styling
- Modify `tailwind.config.cjs` to customize the design system
- Update component styles in individual `.astro` files
- Add custom CSS in component style blocks

### Content
- Update section content in `src/components/sections/`
- Modify layout in `src/layouts/Layout.astro`
- Replace images in `public/images/`

### Configuration
- Update site metadata in `src/layouts/Layout.astro`
- Modify Astro configuration in `astro.config.mjs`

## 📱 Responsive Design

The layout is fully responsive and optimized for:
- Mobile devices (320px and up)
- Tablets (768px and up)
- Desktop (1024px and up)
- Large screens (1280px and up)

## 🌐 Deployment

### Build for Production
```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service.

### Deployment Options
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)
- [Cloudflare Pages](https://pages.cloudflare.com/)

## 📄 License

This project is licensed under the MIT License - see the [LICENCE.md](LICENCE.md) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Contact

For questions or support, please contact: raul11jg@gmail.com

---

**Built with ❤️ using Astro and Tailwind CSS**
