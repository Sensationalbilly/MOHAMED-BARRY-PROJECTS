# Sierra Leone Football Agency Website

A professional, interactive website for the Sierra Leone Football Agency featuring the Premier League teams and players.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Beautiful Green Gradient Theme**: Inspired by Sierra Leone's colors
- **Interactive Elements**: Hover effects, animations, and smooth transitions
- **5 Main Pages**:
  - Home: Hero section with latest news
  - Players: Filterable player profiles with stats
  - Matches: Upcoming fixtures and recent results
  - About: History, mission, and values
  - Contact: Contact form and information

## Setup Instructions

1. **Add Your Images**: Place your images in the `images` folder with these names:
   
   **Logo (Required):**
   - `logo.png` - Your agency logo (appears in navigation on all pages)
   
   **Hero/Header Images (One for each page):**
   - `hero-home.jpg` - Home page hero background (main landing page)
   - `hero-players.jpg` - Players page header background
   - `hero-matches.jpg` - Matches page header background
   - `hero-about.jpg` - About page header background
   - `hero-contact.jpg` - Contact page header background
   
   **News Images:**
   - `news1.jpg`, `news2.jpg`, `news3.jpg` - News article images
   
   **Player Photos:**
   - `player1.jpg` through `player6.jpg` - Player photos
   
   **Team Logos:**
   - `team1.jpg` through `team6.jpg` - Team logos/badges
   
   **About Page:**
   - `history.jpg` - History section image
   - `mission.jpg` - Mission section image

2. **Open the Website**: Simply open `index.html` in your web browser

3. **Customize Content**: Edit the HTML files to add your actual:
   - Player names and stats
   - Team names
   - Match schedules
   - Contact information
   - News articles

## Important Notes

- **Loading Screen**: Only appears on the home page (index.html) when first entering the site
- **Hero Images**: Your images will display beautifully with just a subtle dark overlay for text readability
- **Image Format**: Use JPG or PNG format. Recommended size: 1920x1080px for hero images

## File Structure

```
├── index.html          # Home page
├── players.html        # Players page
├── matches.html        # Matches page
├── about.html          # About page
├── contact.html        # Contact page
├── style.css           # All styles
├── script.js           # Interactive features
├── images/             # Your images folder
└── README.md           # This file
```

## Icons

The website uses Font Awesome 6.4.0 for realistic, professional icons (no fiber icons).

## Interactive Features

- Mobile-responsive hamburger menu
- Player position filter (All, Forwards, Midfielders, Defenders, Goalkeepers)
- Match tabs (Upcoming/Results)
- Animated statistics counter
- Smooth scroll animations
- Hover effects on cards
- Contact form validation

## Color Scheme

- Primary: #1a1a2e (Dark Navy)
- Secondary: #16213e (Navy Blue)
- Accent: #f39c12 (Gold)
- Accent Light: #f1c40f (Light Gold)
- Professional dark theme with gold accents

**Want to change colors?** Edit the CSS variables in `style.css` (lines 8-16) to customize the color scheme to your preference.

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Customization Tips

1. **Change Colors**: Edit the CSS variables in `style.css` (lines 8-16)
2. **Add More Players**: Copy a player card in `players.html` and update the info
3. **Update Matches**: Edit the match cards in `matches.html`
4. **Modify Contact Info**: Update the contact details in `contact.html`

Enjoy your Sierra Leone Football Agency website!
