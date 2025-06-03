# Grabbit E-commerce Store

A modern e-commerce platform for digital prints, posters, and merchandise built with Next.js 14 and TypeScript.

## 🚀 Features

- **Modern Design**: Clean, responsive design with Tailwind CSS
- **Norwegian Language**: Fully localized for Norwegian customers
- **Shopping Cart**: Persistent cart with localStorage
- **Authentication**: Mock authentication system (ready for Supabase integration)
- **Product Catalog**: Featured products and category browsing
- **Mobile Responsive**: Optimized for all device sizes
- **Toast Notifications**: User feedback system

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Heroicons
- **Fonts**: Inter & Poppins (Google Fonts)

## 🎨 Design System

### Colors
- **Primary**: Coral (#FF6B6B) - Main brand color
- **Secondary**: Gray scale for text and backgrounds
- **Accent**: Various shades of coral for hover states

### Typography
- **Primary Font**: Inter (body text)
- **Heading Font**: Poppins (headings and brand)

## 🏃‍♂️ Getting Started

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start development server**:
   ```bash
   npm run dev
   ```

3. **Open your browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
src/
├── app/                    # Next.js app directory
│   ├── layout.tsx         # Root layout with providers
│   ├── page.tsx           # Homepage
│   └── globals.css        # Global styles
├── components/
│   ├── layout/            # Layout components
│   │   ├── Header.tsx     # Navigation header
│   │   └── Footer.tsx     # Site footer
│   ├── providers/         # Context providers
│   │   ├── AuthProvider.tsx
│   │   ├── CartProvider.tsx
│   │   └── ToastProvider.tsx
│   ├── sections/          # Page sections
│   │   ├── HeroSection.tsx
│   │   ├── FeaturedProducts.tsx
│   │   ├── CategoryGrid.tsx
│   │   └── CtaSection.tsx
│   └── ui/                # Reusable UI components
│       └── Button.tsx
└── lib/                   # Utility libraries
    ├── services/          # Mock services
    └── supabase/          # Database types
```

## 🎯 Current Status

This is a **development version** with mock data and services. The application includes:

✅ **Completed**:
- Homepage with hero section
- Featured products display
- Category grid
- Responsive navigation
- Shopping cart functionality
- Toast notifications
- Mock authentication

🚧 **Next Steps for Production**:
- Supabase database integration
- Real authentication system
- Product management
- Payment processing (Stripe + Vipps)
- Order management
- Email notifications
- SEO optimization

## 🌟 Key Components

### Homepage Sections
1. **Hero Section**: Eye-catching banner with call-to-action
2. **Featured Products**: Showcase of popular items
3. **Category Grid**: Browse by product categories
4. **CTA Section**: Final call-to-action for shopping

### Navigation
- Responsive header with mobile menu
- Shopping cart with item count
- User authentication state
- Brand logo and navigation links

### Shopping Cart
- Add/remove items
- Update quantities
- Persistent storage
- Real-time total calculation

## 🎨 Customization

The design system is built with CSS custom properties and Tailwind CSS. Key customizations:

- **Colors**: Defined in `tailwind.config.js`
- **Fonts**: Configured in `layout.tsx`
- **Components**: Modular and reusable
- **Responsive**: Mobile-first approach

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

This project follows the implementation guide in `grabbit_ecommerce_guide.md`. For production deployment, refer to the guide for:

- Database setup with Supabase
- Payment integration
- Email services
- Analytics setup
- Performance optimization

---

**Built with ❤️ for Norwegian e-commerce**
