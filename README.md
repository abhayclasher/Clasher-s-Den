# 🎮 Clasher's Den

A simple, multipurpose Discord bot with a modern, animated landing page. Built with vanilla JavaScript, featuring particle effects, smooth animations, and real-time statistics from the Statcord API.

## ✨ Features

- **Multi-Purpose Bot** - Customization, games, moderation, and leveling system
- **Real-time Stats** - Live server count and user count via Statcord API
- **Particle Effects** - Interactive particle.js background animations
- **Smooth Animations** - AOS (Animate On Scroll) library integration
- **Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- **Auto-typing Effect** - Dynamic text rotation using Typed.js
- **Staff Carousel** - Owl Carousel showcasing team members
- **Loading Animation** - Custom loader with animated fazers
- **Sticky Navigation** - Fixed navbar with smooth transitions

## 🚀 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (jQuery)
- **Animations:** AOS.js, Typed.js, Owl Carousel
- **Effects:** Particles.js
- **API:** Statcord API for live bot statistics
- **Icons:** Font Awesome
- **Fonts:** Google Fonts (Poppins, Ubuntu)

## 📁 Project Structure

```
Clasher-s-Den/
├── aos/
│   ├── aos.css              # Animate on scroll styles
│   └── aos.js               # Animate on scroll library
├── particles/
│   ├── app.js               # Particle configuration
│   └── particles.js         # Particle.js library
├── index.html               # Main landing page
├── style.css                # Custom styles and theme
├── script.js                # Main JavaScript functionality
├── stats.js                 # Statcord API integration
└── README.md                # This file
```

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Clasher-s-Den.git
cd Clasher-s-Den
```

### 2. Update Bot Statistics (Optional)

If you want to display your own Discord bot statistics, update the Statcord API endpoint in `stats.js`:

```javascript
fetch('YOUR_STATCORD_API_ENDPOINT')
```

### 3. Customize Bot Invite Link

Update the invite link in `index.html`:

```html
<a href="YOUR_BOT_INVITE_URL">Invite Me</a>
```

### 4. Run the Website

Simply open `index.html` in your browser, or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

Visit [http://localhost:8000](http://localhost:8000)

## 🚢 Deployment

### Deploy on GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/Clasher-s-Den`

### Deploy on Netlify

1. Connect your GitHub repository
2. No build configuration needed
3. Deploy instantly!

### Deploy on Vercel

1. Import your GitHub repository
2. No build settings required
3. Click Deploy!

## 🎨 Color Scheme

- **Primary:** `#22b4b7` (Cyan/Teal)
- **Background:** `#121212` (Dark)
- **Card Background:** `#222` (Dark Gray)
- **Text:** `#fff` (White)

## 📱 Sections

1. **Home** - Hero section with auto-typing animation
2. **Features** - Bot capabilities showcase (6 feature cards)
3. **Stats** - Real-time bot statistics from Statcord
4. **Staff** - Team members carousel with role badges
5. **Footer** - Credits and copyright

## 🎭 Bot Features

### 🔧 Customization
- Welcome and leave messages
- Level up system
- Custom commands
- NQN mode and more

### 🎮 Games
- Multiple interactive games
- Claim rewards and compete

### 🎵 Music (Coming Soon™)
- High-quality music playback
- YouTube and Twitch live streams support
- Voice chat integration

### 🔒 Moderation
- Powerful moderation commands
- Server protection tools
- Fast moderation workflow

### 💻 Web Dashboard (Coming Soon™)
- Configure all settings from web interface
- Visual server management

### 📈 Level Up System
- Reward active users with points and roles
- Increase server engagement

## 🌟 Staff Badges

- **Owner** - `#22b4b7` (Cyan)
- **Developer** - `orange`
- **Helper** - `#7289DA` (Blurple)
- **Supporter** - `#ff1476` (Pink)
- **Designer** - `#315dd4` (Blue)

## 🔌 API Integration

The bot uses Statcord API to display real-time statistics:

```javascript
fetch('https://api.statcord.com/v3/statcord.com-1G6OSbHsUkirYg1cFHkU')
```

Statistics displayed:
- Total servers
- Total users  
- Commands used

## 📦 Dependencies

```html
<!-- jQuery -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

<!-- Waypoints -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>

<!-- Owl Carousel -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" />

<!-- Typed.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>

<!-- Font Awesome -->
<script src="https://kit.fontawesome.com/a076d05399.js"></script>

<!-- Particles.js -->
<script src="./particles/particles.js"></script>
<script src="./particles/app.js"></script>

<!-- AOS (Animate On Scroll) -->
<link rel="stylesheet" type="text/css" href="./aos/aos.css" />
<script src="./aos/aos.js"></script>
```

## 🎯 Key Features Explained

### Particle Background
- Interactive particle system using Particles.js
- Creates an engaging, dynamic background
- Fully customizable in `particles/app.js`

### Auto-typing Animation
- Rotating adjectives describing the bot
- Smooth typing and backspace effects
- Configured in `script.js`:

```javascript
strings: [
    "simple",
    "powerful", 
    "easy to use",
    "great",
    "your Waifu",
    "made with love",
    "kind",
    "well developed",
    "nice"
]
```

### Sticky Navigation
- Fixed navbar that appears on scroll
- Smooth color transitions
- Mobile-responsive hamburger menu

### Loading Animation
- Custom loader with animated horizontal bars
- Fades out when page fully loads
- Improves perceived performance

## 📄 License

MIT License - Feel free to use this project for any purpose.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 💡 Future Enhancements

- [ ] Web dashboard for bot configuration
- [ ] Music system integration
- [ ] Enhanced moderation tools
- [ ] More interactive games
- [ ] Command list page
- [ ] Server leaderboards
- [ ] Premium features page

## 🔗 Links

- **Invite Bot:** [Discord Invite](https://discord.com/api/oauth2/authorize?client_id=1002858272094691409&permissions=8&scope=bot)
- **Support Server:** [Join Discord](https://discord.gg/hB6Pp73zV8)

## 👨‍💻 Author

**Abhay Kumar**
- 📧 Email: abhaypro.cloud@gmail.com
- 📸 Instagram: [@abhay_clasher](https://www.instagram.com/abhay_clasher/)
- 📍 Location: Kolkata, India

---

**Made with 💖 by Abhay Clasher**  
Copyright © Clasher's Den 2022
