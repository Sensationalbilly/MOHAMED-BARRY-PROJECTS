# SLFA Website - Image Setup Guide

## How to Add Your Images

### 1. Create the Images Folder Structure

Create these folders in your project:

```
images/
├── hero-bg.jpg          (Hero section background)
├── trending-placeholder.jpg
├── team1-logo.png
├── team2-logo.png
├── news1.jpg
├── news2.jpg
├── news3.jpg
├── highlight1.jpg
├── highlight2.jpg
├── highlight3.jpg
├── our-story.jpg
├── general-info.jpg
├── our-mission.jpg
├── store.jpg
├── agency.jpg
├── office-location.jpg
├── players/
│   ├── midfielder1.jpg to midfielder6.jpg
│   ├── forward1.jpg to forward6.jpg
└── matches/
    ├── loan1.jpg to loan6.jpg
    ├── gk1.jpg to gk7.jpg
    └── defender1.jpg to defender5.jpg
```

### 2. Where to Add Images

#### Index.html (Home Page)
- **Hero Background**: Add `images/hero-bg.jpg` - This will be the background image
- **Trending**: `images/trending-placeholder.jpg`
- **Team Logos**: `images/team1-logo.png` and `images/team2-logo.png`
- **News**: `images/news1.jpg`, `images/news2.jpg`, `images/news3.jpg`
- **Highlights**: `images/highlight1.jpg`, `images/highlight2.jpg`, `images/highlight3.jpg`

#### About.html
- `images/our-story.jpg`
- `images/general-info.jpg`
- `images/our-mission.jpg`
- `images/store.jpg`
- `images/agency.jpg`

#### Contact.html
- `images/office-location.jpg` (can be a map or photo of your office)

#### Players.html
- Midfielders: `images/players/midfielder1.jpg` through `midfielder6.jpg`
- Forwards: `images/players/forward1.jpg` through `forward6.jpg`

#### Matches.html
- On Loan: `images/matches/loan1.jpg` through `loan6.jpg`
- Goalkeepers: `images/matches/gk1.jpg` through `gk7.jpg`
- Defenders: `images/matches/defender1.jpg` through `defender5.jpg`

### 3. Customizing the Hero Background

The hero section on index.html uses a background image. To change it:

1. Add your image to `images/hero-bg.jpg`
2. If you want a different overlay effect, edit `styles.css` around line 75

### 4. Image Recommendations

- **Hero Background**: 1920x600px or larger
- **Player/Match Photos**: 400x300px minimum
- **News/Highlights**: 600x400px minimum
- **Team Logos**: 200x200px (PNG with transparent background recommended)
- **Format**: JPG for photos, PNG for logos

### 5. Quick Start

1. Create the `images` folder in your project root
2. Add your images with the exact names shown above
3. Open `index.html` in your browser to see your site

### 6. Need Different Image Names?

If you want to use different filenames, just update the `src` attributes in the HTML files. For example:

```html
<!-- Change from: -->
<img src="images/news1.jpg" alt="News 1">

<!-- To your filename: -->
<img src="images/my-custom-name.jpg" alt="News 1">
```

## File Structure

```
project/
├── index.html
├── about.html
├── contact.html
├── players.html
├── matches.html
├── styles.css
├── README.md
└── images/
    └── (your images here)
```

## Notes

- All image paths are relative to the HTML files
- Images will have a gray placeholder background until you add your actual images
- The site is fully responsive and will work on mobile devices
