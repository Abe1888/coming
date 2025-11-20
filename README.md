# Translink Fuel Level Sensor Pro - 3D Interactive Experience

An immersive 3D web experience showcasing the Translink Fuel Level Sensor Pro with real-time animations, interactive scroll-based storytelling, and detailed technical specifications.

![Translink Solutions PLC](https://img.shields.io/badge/Translink-Solutions%20PLC-red)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Three.js](https://img.shields.io/badge/Three.js-0.160.0-green)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3.3-blue)

## 🚛 Features

### Interactive 3D Scene
- **Real-time 3D rendering** with Three.js
- **Physics-based animations** (truck vibration, suspension, engine rumble)
- **Scroll-triggered camera movements** through 4 distinct phases
- **Dynamic lighting** with red neon aesthetic
- **Particle effects** and atmospheric fog

### Product Showcase
- **Fuel Level Sensor Pro** detailed component breakdown
- **Technical specifications** displayed in 3D space
- **Interactive info cards** that follow truck physics
- **Sensor head, probe, and protection cage** visualization

### Audio System
- **Realistic diesel engine sounds** with rumble and vibration
- **Horn blast effects** triggered by scroll events
- **Ambient road noise** and wind effects
- **Scanner sounds** during component inspection
- **Click-to-activate** audio (browser autoplay compliance)

### Extended Animation
- **Intro phase** (3.5 seconds) - truck enters from behind
- **Dual sequence** - animation replays after 50% scroll
- **Smooth transitions** between all phases
- **No scene cuts** - continuous flow

## 🎯 Scroll Phases

1. **Phase 0 (0-35% scroll)**: Real-Time Fuel Monitoring
   - Hero angle showcasing the truck
   - Key features and benefits

2. **Phase 1 (35-55% scroll)**: Sensor Head Module
   - Focus on sensor head
   - Technical specifications
   - Interface details (CAN, RS232, Modbus)

3. **Phase 2 (55-75% scroll)**: Exploded Component View
   - Detailed breakdown of all components
   - SVG connection lines to info cards
   - Sensor head, fuel probe, protection cage

4. **Phase 3 (75-100% scroll)**: Deployment
   - Top-down view
   - Call-to-action button
   - Fleet integration ready

## 🛠️ Tech Stack

- **React 18.2** - UI framework
- **TypeScript 5.3** - Type safety
- **Three.js 0.160** - 3D rendering
- **Vite 5.0** - Build tool
- **Tailwind CSS** - Styling
- **Lucide React** - Icons
- **Web Audio API** - Sound system

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/translink-fuel-sensor.git

# Navigate to project directory
cd translink-fuel-sensor

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🚀 Deployment

### Netlify (Recommended)

1. **Connect to GitHub**
   - Push your code to GitHub
   - Connect your repository to Netlify

2. **Build Settings** (Auto-configured via netlify.toml)
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Node version: 18

3. **Deploy**
   ```bash
   # Or deploy manually
   npm run build
   netlify deploy --prod
   ```

### Manual Build

```bash
# Build for production
npm run build

# Preview production build locally
npm run preview
```

## 📁 Project Structure

```
translink-fuel-sensor/
├── src/
│   ├── App.tsx              # Main application component
│   └── index.tsx            # Entry point
├── public/                  # Static assets
├── dist/                    # Production build (generated)
├── netlify.toml            # Netlify configuration
├── package.json            # Dependencies and scripts
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite configuration
└── README.md               # This file
```

## 🎨 Branding

### Colors
- **Primary**: Red (#dc2626, #ff3300)
- **Accent**: Orange (#ff9900)
- **Background**: Black (#000000, #050101)
- **Text**: White, Gray shades

### Company
- **Name**: Translink Solutions PLC
- **Product**: Fuel Level Sensor Pro
- **Category**: Advanced Fleet Telematics

## 📊 Technical Specifications

### Fuel Level Sensor Pro
- **Static Accuracy**: ±1%
- **Dynamic Accuracy**: ±5%
- **Resolution**: <0.5mm
- **Voltage Range**: 9-36V DC
- **Temperature Range**: -10°C to +50°C
- **Certification**: IP67
- **Interfaces**: CAN, RS232, Modbus

### Features
- Remote calibration
- Self-diagnostics
- Theft detection
- Anti-slosh technology
- Inclinometer (tilt compensation)
- Multi-tank support
- Real-time data feed
- Low power consumption

## 🌐 Browser Support

- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅

**Note**: WebGL and Web Audio API required

## ⚡ Performance

- **60 FPS** smooth animations
- **Optimized rendering** with Three.js
- **Lazy loading** for assets
- **Efficient state management**
- **Minimal bundle size** with Vite

## 🔊 Audio Features

- **Engine sounds**: Diesel rumble with dual-frequency oscillation
- **Horn blast**: Dual-tone truck horn (F#3 + A#3)
- **Ambient sounds**: Road noise, wind, scanner effects
- **Temperature compensation**: -10°C to +50°C
- **Click activation**: Browser autoplay compliance

## 📱 Responsive Design

- **Desktop**: Full 3D experience
- **Tablet**: Optimized layout
- **Mobile**: Touch-friendly controls

## 🐛 Known Issues

- None currently reported

## 🤝 Contributing

This is a proprietary project for Translink Solutions PLC.

## 📄 License

Copyright © 2024 Translink Solutions PLC. All rights reserved.

## 📞 Contact

**Translink Solutions PLC**
- Website: [Your Website]
- Email: [Your Email]
- Product: Fuel Level Sensor Pro

## 🙏 Acknowledgments

- Three.js community
- React team
- Vite team
- Lucide icons

---

**Built with ❤️ for Translink Solutions PLC**
