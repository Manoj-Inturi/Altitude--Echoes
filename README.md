# 🏔️ Altitude Echoes

A comprehensive and immersive web platform dedicated to high-altitude mountaineering — exploring the world's most extreme peaks and the legendary climbers who conquer them.

---

## 📖 About

**Altitude Echoes** is a structured educational platform that blends **geography, history, and human endurance** into a cohesive experience.

It delivers deep insights into:

- **The 14 Eight-Thousanders**  
  Mountains above 8,000 meters in the Himalayas and Karakoram — the planet's most dangerous climbs where survival is a triumph.

- **The Seven Summits**  
  The highest peak from each continent — representing humanity's ultimate global mountaineering challenge.

- **Legendary Mountaineers & Sherpas**  
  Stories of climbers, guides, and pioneers who shaped high-altitude exploration and redefined human limits.

- **Curated Documentaries**  
  A handpicked collection of 25+ mountaineering films with detailed insights and viewership guides.

- **Altitude Physiology & Science**  
  Deep understanding of how the human body adapts—and struggles—at extreme elevations.

---

## 🌟 Key Features

### 📱 Fully Responsive Design

Built with a **mobile-first approach** and optimized across all screen sizes:

- **Mobile Devices**: 320px – 480px
- **Tablets**: 481px – 768px
- **Desktops**: 769px – 1024px
- **Large Displays**: 1025px+

Delivers:
- Adaptive navigation with smart spacing
- Flexible grid and layout systems
- Touch-friendly UI (44px minimum targets)
- Optimized image rendering and lazy loading
- Smooth animations and transitions

### 🗺️ Comprehensive Peak Documentation

All **21 peak pages** feature deep-dive content:

- Peak statistics (elevation, coordinates, first ascent, geography)
- Terrain analysis and route information
- Historical expedition data and records
- Climbing challenges, hazards, and safety considerations
- Cultural significance and local impact
- External resources and further reading

### 🎬 Documentary Library

Curated collection of **25+ elite mountaineering films**:

- Release dates and production details
- Director, cast, and crew information
- Streaming availability guides
- Comprehensive summaries and critical context
- Recommendations by skill level

### 👥 Mountaineer Gallery

Profiles of climbers spanning:

- Indian mountaineers and High-Altitude Sherpas
- International legends and pioneers
- Historical expedition leaders
- Contemporary record-setters


---

## 🏗️ Project Architecture

```
Altitude--Echoes/
│
├── index.html                    # Main landing page
├── README.md                     # Project documentation
│
├── assets/                       # All static resources
│   ├── css/                     # 27 modular, responsive stylesheets
│   │   ├── index.css            # Main page styles
│   │   ├── peaks-shared.css     # Shared peak page components
│   │   ├── documentaries.css    # Documentary page layouts
│   │   ├── mountaneers.css      # Gallery and profiles
│   │   ├── mmm.css              # Altitude physiology guide
│   │   ├── sevensummit.css      # Seven summits showcase
│   │   └── [peak-specific].css  # 21 individual peak stylesheets
│   │
│   ├── images/                  # Organized image library
│   │   ├── general/             # Theme and layout graphics
│   │   ├── logos/               # Brand and navigation assets
│   │   ├── peaks/               # Mountain photography
│   │   └── people/              # Mountaineer profiles
│   │
│   ├── js/                      # Interactive behaviors
│   └── svg/                     # Scalable vector graphics
│
└── pages/                        # Page templates
    ├── peaks/                   # 21 peak detail pages
    │   ├── 8000.html
    │   ├── everest.html
    │   ├── k2.html
    │   ├── annapurna.html
    │   └── ... (17 additional peaks)
    │
    └── other/                   # Thematic pages
        ├── documentaries.html
        ├── mountaneers.html
        ├── mmm.html             # Altitude physiology
        └── sevensummit.html
```

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, etc.) for development
- Git (optional, for cloning)

### Installation & Setup

**1. Clone the repository:**

```bash
git clone https://github.com/Manoj-Inturi/Altitude--Echoes.git
cd Altitude--Echoes
```

**2. Run locally using a web server:**

```bash
# Python 3 (recommended)
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server

# Ruby
ruby -run -ehttpd . -p8000
```

**3. Open in browser:**

```
http://localhost:8000
```

**4. Navigate the site:**
- Landing page displays featured content
- Browse peaks, summits, climbers, and films
- Each page includes internal navigation links

---

## 📚 Complete Pages Guide

### Main Hubs

| Page | URL | Purpose |
|------|-----|---------|
| **Home** | `/index.html` | Landing hub with featured content |
| **8000ers Index** | `/pages/peaks/8000.html` | Gateway to all 14 eight-thousanders |
| **Seven Summits** | `/pages/other/sevensummit.html` | Continental peak showcase |
| **Mountaineer Gallery** | `/pages/other/mountaneers.html` | Profiles and achievements |
| **Documentary Library** | `/pages/other/documentaries.html` | Film recommendations and reviews |
| **Altitude Physiology** | `/pages/other/mmm.html` | Medical and scientific insights |

### Peak Pages (21 Total)

All located in `/pages/peaks/` with dedicated styling:

**Himalayan Peaks:**
- Mount Everest (8,848.86m)
- K2 (8,611m)
- Kangchenjunga (8,586m)
- Lhotse (8,516m)
- Makalu (8,485m)
- Cho Oyu (8,188m)
- Dhaulagiri (8,167m)
- Manaslu (8,163m)
- Nanga Parbat (8,126m)
- Annapurna I (8,091m)

**Karakoram Peaks:**
- Gasherbrum I / Hidden Peak (8,080m)
- Broad Peak (8,051m)
- Gasherbrum II (8,034m)
- Shishapangma (8,027m)

**Seven Summits:**
- Aconcagua (6,961m) — South America
- Denali (6,190m) — North America
- Mount Elbrus (5,642m) — Europe
- Kilimanjaro (5,895m) — Africa
- Vinson Massif (4,892m) — Antarctica
- Carstensz Pyramid (4,884m) — Oceania

---

## 🎨 Design & Technology Stack

### Frontend Technologies

| Technology | Purpose | Implementation |
|-----------|---------|-----------------|
| **HTML5** | Semantic markup | Clean, accessible document structure |
| **CSS3** | Responsive styling | Media queries, flexbox, CSS Grid |
| **JavaScript** | Interactivity | DOM manipulation, navigation |
| **SVG** | Scalable graphics | Data visualization, icons |
| **Google Fonts** | Typography | Montserrat (headers), Open Sans (body) |

### Responsive Breakpoints

Strategic breakpoints ensure perfect rendering:

```css
Mobile Small:    320px - 480px     /* Phones */
Mobile Large:    481px - 768px     /* Tablets */
Desktop:         769px - 1024px    /* Laptops */
Large Desktop:   1025px+           /* Monitors */
```

### CSS Architecture

- **Mobile-first approach** — Base styles for small screens, enhanced for larger
- **Modular files** — Each peak has dedicated stylesheet
- **Shared components** — Common styles in `peaks-shared.css`
- **CSS variables** — Consistent color and sizing system
- **Flexible typography** — Font sizes scale with viewport
- **Touch optimization** — 44px minimum interactive targets

---

## 🔗 Navigation System

### Primary Navigation Bar

Always accessible header featuring:
- Logo (links to home)
- Peak explorer (8000ers)
- Continental challenge (Seven Summits)
- Climber profiles (Mountaineers)
- Film collection (Documentaries)
- Scientific guide (Altitude Sickness)

### In-Page Navigation

**Peak Pages Include:**
- Previous/Next peak buttons for sequential browsing
- Visual peak grid for quick jumping
- "Back to Home" links
- Related peaks section

**Multi-Level Navigation:**
- Home → Category → Peak → Details
- Breadcrumb-style orientation
- Consistent header and footer

---

## 📊 Content Deep Dive

### The 14 Eight-Thousanders

**Overview:**
- Located exclusively in the Himalayas and Karakoram ranges
- Span across 5 countries: Nepal, India, Pakistan, Tibet/China, Indonesia
- Represent the absolute pinnacle of mountaineering difficulty
- Death Zone starts at ~8,000m (oxygen levels critically low)

**Key Statistics:**
- Everest: First summited 1953 (Hillary & Tenzing Norgay)
- K2: Deadliest 8000er (1 death per 4 summits)
- Annapurna: Most dangerous (1 death per 3 summits)
- All require serious expedition planning

### The Seven Summits

**Continental Challenge:**
- Mount Everest (Asia)
- Aconcagua (South America)
- Denali (North America)
- Mount Elbrus (Europe)
- Mount Kilimanjaro (Africa)
- Carstensz Pyramid (Oceania)
- Vinson Massif (Antarctica)

**Significance:**
- Represents full diversity of Earth's mountains
- Tests adaptability across climates and terrains
- Symbol of true mountaineering versatility
- Achievable by dedicated (non-elite) climbers

### Documentary Collection

**Categories:**
- Epic expeditions and summits
- Historical records and archive
- Safety, rescue, and survival
- Cultural impact and ethics
- Solo climbing and innovation

**Featured Films:**
- 14 Peaks: Nothing Is Impossible
- Meru
- Free Solo
- Sherpa
- The Summit
- Touching the Void

---

## 🐛 Recent Enhancements

### Code Quality ✅
- Fixed 5 critical HTML syntax errors
- Corrected 30+ broken image and hyperlinks
- Validated all CSS file references
- Implemented proper semantic markup

### Responsive Design ✅
- Added media queries to all 27 CSS files
- Mobile-first design methodology
- Tablet-optimized layouts
- Enhanced desktop experiences
- Breakpoints: 480px, 768px, 1024px+

### Performance ✅
- Restructured assets for faster serving
- Optimized image compression
- Improved CSS organization and modularity
- Better separation of concerns

### Accessibility ✅
- Touch targets meet 44px minimum
- Improved color contrast ratios
- Enhanced keyboard navigation
- Better alt text for images
- Screen reader friendly

---

## 🛠️ Development Guide

### Adding New Peak Content

**Step 1: Create HTML Page**
```
pages/peaks/[peakname].html
```

**Step 2: Create Stylesheet**
```
assets/css/[peakname].css
```

**Step 3: Update Navigation**
- Add link in `index.html`
- Add to peak grid in `8000.html`
- Add to related peaks sections

**Step 4: Test Responsiveness**
- Test at 480px, 768px, 1024px
- Check on actual mobile devices
- Validate image loading

### CSS Organization Strategy

```
Structure:
1. Root variables (colors, sizes)
2. Base element styles
3. Navigation
4. Main content areas
5. Footer
6. Media queries (mobile → large)
```

### Best Practices

- **Consistency** — Use existing color scheme and typography
- **Performance** — Optimize images before deployment
- **Accessibility** — Always include alt text and descriptive labels
- **Testing** — Verify on multiple browsers and devices
- **Documentation** — Update this README with changes

---

## 🌐 Browser Compatibility

**Fully Supported:**
- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile Safari (iOS 14+)
- Chrome Android

**Graceful Degradation:**
- Older browsers receive functional experience
- CSS Grid falls back to flexbox
- JavaScript enhancements are progressive

---

## 📱 Mobile Experience

### Optimization Details

| Feature | Implementation |
|---------|-----------------|
| **Responsive Images** | Scale to 100% viewport width |
| **Touch Targets** | Minimum 44×44 pixel hitbox |
| **Typography** | Font sizes increase on larger screens |
| **Navigation** | Flexible menu adapts to screen |
| **Performance** | Lightweight, fast-loading assets |

### Device Testing

Tested on:
- iPhone (SE, 11, 12, 13, 14)
- Android (Samsung, Google Pixel)
- Tablets (iPad, Samsung)
- Desktops and laptops

---

## 🔌 Customization Guide

### Theme Colors

Located in individual CSS files:

```css
:root {
  --primary-color: #007bff;      /* Blue accent */
  --background: #f5f7fa;         /* Light gray */
  --text: #222;                  /* Dark text */
  --muted: #6b7280;              /* Muted gray */
}
```

**To change theme:**
1. Update color values in CSS files
2. Maintain contrast ratios (WCAG AA minimum)
3. Test on light and dark backgrounds

### Typography System

**Headers:** Montserrat (Google Fonts)
- Weights: 500, 600, 700
- Sizes: Scale responsively

**Body Text:** Open Sans (Google Fonts)
- Weights: 400, 500
- Sizes: 13px to 18px based on screen

**To customize:**
1. Import different fonts in `<head>`
2. Update CSS font-family rules
3. Adjust font-size in breakpoints

### Layout Modifications

**Main Containers:**
- `.nav` — Navigation header
- `.mountain-container` — Primary content wrapper
- `.grid` — Multi-column layouts
- `.section-card` — Content blocks

**To modify:**
1. Edit CSS grid or flexbox properties
2. Adjust padding/margin values
3. Test responsive behavior

---

## 📝 License & Usage

**License:** MIT — Open source for educational and personal use

**Attribution:** While not required, linking back to this repository is appreciated.

---

## 👨‍💻 Author & Creator

**Manoj Inturi**

- GitHub: [@Manoj-Inturi](https://github.com/Manoj-Inturi)
- Project: [Altitude Echoes](https://github.com/Manoj-Inturi/Altitude--Echoes)
- Created: 2025-2026

---

## 🤝 Contributing Guidelines

We welcome contributions! Here's how to participate:

**1. Fork the repository**
```bash
git fork https://github.com/Manoj-Inturi/Altitude--Echoes.git
```

**2. Create a feature branch**
```bash
git checkout -b feature/your-feature-name
```

**3. Make your changes**
- Edit files
- Test thoroughly
- Keep commits clean

**4. Commit with clear messages**
```bash
git commit -m "feat: Add new feature description"
```

**5. Push and create Pull Request**
```bash
git push origin feature/your-feature-name
```

**6. Submit PR with description**
- Describe changes clearly
- Reference any related issues
- Include screenshots if applicable

---

## 📬 Support & Contact

**Report Issues:**
- GitHub Issues tab
- Detailed error descriptions
- Screenshots or reproductions

**Feature Requests:**
- GitHub Discussions
- Enhancement suggestions
- Use case descriptions

**General Questions:**
- Star this repository
- Share feedback
- Suggest improvements

---

## 🙏 Acknowledgments & Credits

**Resources:**
- Wikipedia for mountain and climber data
- IMDb for documentary information
- Google Fonts for typography
- Open-source community for tools and inspiration

**Technical Foundation:**
- HTML5 specification compliance
- CSS3 best practices
- Responsive design principles
- Accessibility standards (WCAG 2.1)

**Special Thanks:**
- All mountaineers and Sherpas featured
- Documentary filmmakers
- Educational contributors
- Community feedback

---

## 📈 Project Statistics

**Current State:**
- 1 main landing page
- 21 peak detail pages
- 4 thematic pages
- 27 responsive CSS files
- 100+ mountain images
- 25+ documentary references
- 60+ climber profiles
- 100% responsive design

**Code Metrics:**
- HTML: Semantic, validated
- CSS: 27 modular files, fully responsive
- JavaScript: Clean, organized
- Performance: Optimized for web

---

## 🔄 Latest Updates (April 2026)

**Version 2.0 — Major Restructuring:**
- ✅ Reorganized into modular directory structure
- ✅ Fixed all broken links (30+ corrections)
- ✅ Added comprehensive responsive design
- ✅ Enhanced mobile experience
- ✅ Improved code organization
- ✅ Added this detailed documentation

**Next Planned Features:**
- Dark mode toggle
- Image gallery lightbox
- Search functionality
- Climber achievement tracking
- Interactive peak comparison

---

## 🎯 Vision & Future

**Altitude Echoes** aims to be the definitive educational resource for mountaineering enthusiasts, from casual learners to aspiring climbers.

**Long-term goals:**
- Expand to 50+ peaks globally
- Add interactive elevation profiles
- Include real-time expedition tracking
- Create mobile app version
- Build community forums
- Add user-generated content

---

## 📞 Get in Touch

- **GitHub:** https://github.com/Manoj-Inturi/Altitude--Echoes
- **Issues:** Report bugs and request features
- **Discussions:** Join the community conversation
- **Stars:** Show your support ⭐

---

**Made with ❤️ for mountaineering enthusiasts worldwide.**

**Last Updated:** April 11, 2026

For the latest updates and features, visit: **[Altitude Echoes on GitHub](https://github.com/Manoj-Inturi/Altitude--Echoes)**
