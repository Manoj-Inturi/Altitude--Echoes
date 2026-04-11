# 🏔️ Altitude Echoes

A comprehensive web platform dedicated to high-altitude mountaineering, exploring the world's most challenging peaks and the legends who conquer them.

## 📖 About

**Altitude Echoes** is an educational website that celebrates the art and science of mountaineering. It provides in-depth information about:

- **The 14 Eight-Thousanders** - Peaks above 8,000 meters in the Himalayas and Karakoram
- **The Seven Summits** - The highest peaks on each continent
- **Legendary Mountaineers** - Stories of climbers who've shaped the sport
- **Documentaries** - Curated collection of mountaineering films
- **Altitude Sickness** - Understanding high-altitude physiology

## 🌟 Features

### 📱 Fully Responsive Design
- **Mobile Optimized** (320px - 480px)
- **Tablet Friendly** (481px - 768px)
- **Desktop Enhanced** (769px - 1024px)
- **Large Screen** (1025px+)

The website adapts seamlessly across all devices with:
- Responsive navigation
- Flexible grid layouts
- Touch-friendly interactive elements
- Optimized image scaling

### 🗺️ Comprehensive Peak Documentation
Each of the 21 peak pages includes:
- Peak Overview with statistics (Height, Location, First Ascent, Coordinates)
- Geography and terrain information
- Historical significance
- Climbing challenges and dangers
- Cultural impact
- External resources

### 🎬 Documentary Library
25+ curated mountaineering documentaries with:
- Release information
- Director and cast details
- Watch availability guides
- Comprehensive summaries

### 👥 Mountaineer Profiles
Extensive collection of legends and modern pioneers:
- Indian climbers and Sherpas
- International mountaineers
- Historical figures
- Contemporary athletes

## 🏗️ Project Structure

```
Altitude--Echoes/
├── index.html                    # Main landing page
├── README.md                     # This file
├── assets/
│   ├── css/                     # 27 responsive CSS files
│   │   ├── index.css            # Main page styles
│   │   ├── peaks-shared.css     # Shared peak page styles
│   │   ├── documentaries.css    # Documentary page styles
│   │   ├── mountaneers.css      # Mountaineers page styles
│   │   ├── mmm.css              # Altitude sickness page styles
│   │   ├── sevensummit.css      # Seven summits page styles
│   │   └── [peak-specific].css  # 21 individual peak CSS files
│   ├── images/
│   │   ├── general/             # General website images
│   │   ├── logos/               # Logo files
│   │   ├── peaks/               # Mountain peak images
│   │   └── people/              # Mountaineer profile images
│   ├── js/                      # JavaScript files
│   └── svg/                     # SVG graphics
└── pages/
    ├── peaks/                   # 21 peak detail pages
    │   ├── 8000.html
    │   ├── everest.html
    │   ├── k2.html
    │   ├── annapurna.html
    │   └── ... (17 more peaks)
    └── other/                   # Additional pages
        ├── documentaries.html
        ├── mountaneers.html
        ├── mmm.html             # Altitude sickness guide
        └── sevensummit.html
```

## 🚀 Getting Started

### Local Development

1. **Clone the repository:**
```bash
git clone https://github.com/Manoj-Inturi/Altitude--Echoes.git
cd Altitude--Echoes
```

2. **Open in browser:**
   - Open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx http-server
   ```

3. **Access the site:**
   - Navigate to `http://localhost:8000`

## 📚 Pages Overview

### Main Pages
| Page | URL | Description |
|------|-----|-------------|
| Home | `/index.html` | Landing page with overview |
| 8000ers | `/pages/peaks/8000.html` | Index of 14 eight-thousanders |
| Seven Summits | `/pages/other/sevensummit.html` | Highest peaks per continent |
| Mountaineers | `/pages/other/mountaneers.html` | Profile collection |
| Documentaries | `/pages/other/documentaries.html` | Film recommendations |
| Altitude Sickness | `/pages/other/mmm.html` | Medical information |

### Peak Pages (21 total)
All located in `/pages/peaks/`:
- Mount Everest, K2, Kangchenjunga
- Lhotse, Makalu, Cho Oyu
- Dhaulagiri, Manaslu, Nanga Parbat, Annapurna
- Gasherbrum I & II, Broad Peak, Shishapangma
- Aconcagua, Denali, Kilimanjaro, Elbrus, Vinson

## 🎨 Design & Technology

### Frontend Tech Stack
- **HTML5** - Semantic markup
- **CSS3** - Responsive design with media queries
- **Flexbox & CSS Grid** - Modern layout system
- **JavaScript** - Interactive features
- **SVG** - Scalable graphics

### Responsive Breakpoints
```css
Mobile:    320px - 480px
Tablet:    481px - 768px
Desktop:   769px - 1024px
Large:     1025px+
```

### Key CSS Features
- Mobile-first design approach
- Flexible typography
- Touch-friendly UI (44px minimum tap targets)
- Dark mode compatible
- Print-friendly styles

## 🔗 Navigation

### Top Navigation Bar
- Logo (links to home)
- 8000ers
- Seven Summits
- Mountaineers
- Documentaries
- Altitude Sickness
- Courses (expandable)

### Peak Navigation
- Next/Previous peak buttons
- Quick peak grid with thumbnails
- Back to home links
- Related peaks section

## 📊 Content Highlights

### 14 Eight-Thousanders
All mountains above 8,000m elevation in Asia:
1. Mount Everest (8,848.86m)
2. K2 (8,611m)
3. Kangchenjunga (8,586m)
... and 11 more

### Seven Summits Challenge
Includes mountains from all seven continents:
- Asia: Mount Everest
- South America: Aconcagua
- North America: Denali
- Europe: Mount Elbrus
- Africa: Kilimanjaro
- Oceania: Carstensz Pyramid
- Antarctica: Vinson Massif

### Documentary Categories
- Adventure & Expedition Films
- Historical Documentaries
- Contemporary Climbing
- Safety & Education
- Cultural Impact

## 🐛 Recent Improvements (Latest Commit)

### Code Quality
- ✅ Fixed 5 critical HTML syntax errors
- ✅ Corrected all broken image paths
- ✅ Fixed incorrect hyperlinks (30+ fixes)
- ✅ Validated all CSS file references

### Responsive Design
- ✅ Added media queries to all 27 CSS files
- ✅ Implemented mobile-first design approach
- ✅ Optimized layouts for tablet screens
- ✅ Enhanced desktop experience

### Performance
- ✅ Reorganized assets for better structure
- ✅ Optimized image loading
- ✅ Improved CSS organization
- ✅ Better separation of concerns

### Accessibility
- ✅ Added touch-friendly sizes (44px minimum)
- ✅ Improved color contrast
- ✅ Enhanced keyboard navigation
- ✅ Better alt text for images

## 🛠️ Development Notes

### Adding New Content
1. For new peaks: Create HTML file in `pages/peaks/` and corresponding CSS
2. For images: Organize by type in `assets/images/`
3. Update navigation links in affected pages
4. Test responsive design on all breakpoints

### CSS Organization
- Each peak has its own CSS file for modularity
- Shared styles in `peaks-shared.css`
- Responsive media queries at end of each file
- Consistent variable definitions for colors/sizes

### Performance Tips
- Images are optimized for web
- CSS is minifiable for production
- SVG graphics are scalable
- Lazy loading can be added for images

## 🌐 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Android)

## 📱 Mobile Optimization

The website is fully optimized for mobile devices:
- **Responsive images** - Scale appropriately per device
- **Touch targets** - All buttons 44px minimum
- **Readable text** - Font sizes scale with screen
- **Quick load** - Optimized asset delivery
- **Touch gestures** - Smooth scrolling and interactions

## 🔌 Customization

### Colors
Primary colors are defined in CSS variables:
- Blue accent: `#007bff`
- Background: `#f5f7fa`
- Text: `#222`

Modify in individual CSS files or create a theme system.

### Fonts
- Headers: Montserrat
- Body: Open Sans
- All from Google Fonts CDN

### Layout
Flexbox and CSS Grid make layout changes simple. Main containers:
- `.nav` - Navigation
- `.mountain-container` - Content wrapper
- `.mountain-row` - Peak sections
- `.grid` - Grid layouts

## 📝 License

This project is open source and available for educational use.

## 👨‍💻 Author

**Manoj Inturi**

- Portfolio: Available in Mountaineers section
- Email: Contact via repository
- GitHub: [@Manoj-Inturi](https://github.com/Manoj-Inturi)

## 🤝 Contributing

To contribute:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Commit with descriptive messages
5. Push to your fork
6. Submit a pull request

## 📬 Contact & Support

- Report bugs via GitHub Issues
- Request features via GitHub Discussions
- Share improvements through Pull Requests

## 🙏 Acknowledgments

- Mountain images from various sources
- Documentary information from IMDb, official sources
- Climber profiles from historical records
- Technical guidance from the open-source community

---

**Last Updated:** April 2026

For the latest features and improvements, visit: https://github.com/Manoj-Inturi/Altitude--Echoes
