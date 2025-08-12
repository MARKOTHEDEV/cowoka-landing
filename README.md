# Cowoka Landing Page

A beautiful, modern landing page for the Cowoka coworking space management platform built with Next.js, Shadcn/ui, and Tailwind CSS.

## 🚀 Features

- **Modern Design**: Clean, professional design with gradient backgrounds and smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Components**: Shadcn/ui components with hover effects and transitions
- **Demo Booking**: Integrated demo booking form with multiple fields
- **Feature Showcase**: Comprehensive display of Cowoka's key features
- **Testimonials**: Customer testimonials with star ratings
- **Call-to-Action**: Multiple CTA buttons throughout the page
- **SEO Optimized**: Proper meta tags and semantic HTML

## 🛠️ Tech Stack

- **Framework**: Next.js 15.4.6 with App Router
- **Styling**: Tailwind CSS
- **Components**: Shadcn/ui
- **Icons**: Lucide React
- **Language**: TypeScript
- **Build Tool**: Vite (via Next.js)

## 📋 Key Sections

1. **Navigation Bar**: Sticky navigation with logo and demo booking button
2. **Hero Section**: Compelling headline with feature image and CTA buttons
3. **Features Section**: Six key features with icons and descriptions
4. **Stats Section**: Impressive statistics about the platform
5. **Testimonials**: Customer reviews with ratings
6. **Call-to-Action**: Final CTA section with gradient background
7. **Footer**: Comprehensive footer with links and company info

## 🎨 Design Highlights

- **Color Scheme**: Blue to indigo gradient theme
- **Typography**: Modern font hierarchy with proper spacing
- **Animations**: Smooth hover effects and transitions
- **Cards**: Feature cards with hover effects
- **Buttons**: Gradient buttons with hover states
- **Forms**: Clean, accessible form design

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd cowoka-landing
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
cowoka-landing/
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx          # Main landing page
│   ├── components/
│   │   └── ui/               # Shadcn/ui components
│   └── lib/
│       └── utils.ts          # Utility functions
├── public/
│   └── cowoka-image.png      # Hero section image
├── components.json           # Shadcn configuration
├── tailwind.config.js        # Tailwind configuration
└── package.json
```

## 🎯 Key Features Showcased

### Booking Management

- Smart booking system with real-time availability
- Resource capacity management
- Multiple time models (hourly, daily, monthly)
- Conflict prevention

### Financial System

- Dual wallet system (general & branch modes)
- Balance reservation and transaction history
- Paystack payment integration
- Automatic refunds and payment history

### Member Management

- Attendance tracking with real-time check-in/out
- Duration tracking and overstaying alerts
- Role-based access control
- Staff management with custom permissions

### Analytics & Reports

- Comprehensive booking analytics
- Revenue analytics and trend analysis
- Utilization reports
- Space optimization insights

## 📱 Responsive Design

The landing page is fully responsive and optimized for:

- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🎨 Customization

### Colors

The color scheme can be customized in `tailwind.config.js`:

- Primary: Blue (#2563eb) to Indigo (#4f46e5)
- Secondary: Various shades for feature cards
- Background: Gradient from slate to blue to indigo

### Content

- Update text content in `src/app/page.tsx`
- Replace `public/cowoka-image.png` with your own hero image
- Modify testimonials and statistics as needed

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For support or questions about the landing page, please contact the development team.

---

Built with ❤️ for Cowoka - The Complete Coworking Space Management Platform
