# Chev & Jada Wedding Website

A beautiful, responsive wedding website built with Bootstrap 5, featuring a maroon and gold color scheme.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Three Pages**: Home, Our Story, and Wedding Information
- **Elegant Styling**: Maroon and gold color scheme with beautiful typography
- **Easy to Customize**: Simple HTML structure that's easy to update
- **Static Content**: No server-side code required - can be hosted anywhere

## Pages

### 1. Home Page (`index.html`)
- Hero section with wedding announcement
- Quick information cards (date, venue, RSVP)
- Welcome message
- Navigation to other pages

### 2. Our Journey (`journey.html`)
- Photo gallery layout showcasing special moments from your time together
- Memory cards with optional dates and personal stories
- Beautiful quote section
- Easy to add photos and memories

### 3. Wedding Information (`information.html`)
- Comprehensive wedding details
- Schedule timeline
- Venue information
- Accommodations and transportation
- Dress code and registry
- RSVP section
- Contact information

## How to Customize

### 1. Basic Information
Replace all placeholder text in brackets `[like this]` with your actual information:

**Home Page:**
- `[Your Wedding Date]` - Your actual wedding date
- `[Your Venue Location]` - Your venue name and location
- `[Time]` - Ceremony and reception times
- `[RSVP Date]` - RSVP deadline

**Journey Page:**
- `[Optional Date]` - Optional dates for each memory (can be left blank)
- Add your actual journey highlights and special moments
- Replace placeholder text with your favorite memories and adventures
- Add photos to showcase your memories

**Information Page:**
- `[Venue Name]` - Your actual venue details
- `[Hotel Name]` - Recommended hotels
- `[email]` and `[phone]` - Contact information
- `[RSVP Date]` - RSVP deadline

### 2. Adding Photos

**For the Hero Section:**
The hero section uses a beautiful wedding background image. To change it:
1. Replace the URL in `styles.css` line 67 with your own image URL
2. Or save your image in the same folder and update the path

**For the Journey Gallery:**
1. Replace the placeholder divs with actual `<img>` tags
2. Example:
```html
<img src="your-photo.jpg" alt="Description" class="img-fluid">
```

**For Other Sections:**
Add images anywhere by using:
```html
<img src="path-to-your-image.jpg" alt="Description" class="img-fluid rounded">
```

### 3. Changing Colors

The website uses CSS custom properties (variables) for easy color customization. In `styles.css`, you can modify:

```css
:root {
    --maroon: #800020;        /* Main maroon color */
    --maroon-dark: #5a0016;   /* Darker maroon */
    --maroon-light: #a0002a;  /* Lighter maroon */
    --gold: #d4af37;          /* Main gold color */
    --gold-light: #f4d03f;    /* Lighter gold */
    --gold-dark: #b8860b;     /* Darker gold */
}
```

### 4. Adding New Sections

To add new content sections:
1. Copy an existing section structure
2. Modify the content and styling as needed
3. Add any new CSS classes to `styles.css`

### 5. Fonts

The website uses Google Fonts:
- **Playfair Display**: For headings (elegant serif font)
- **Montserrat**: For body text (clean sans-serif font)

To change fonts, update the Google Fonts link in the `<head>` section of each HTML file.

## File Structure

```
wedding-website/
├── index.html          # Home page
├── journey.html        # Our Journey page
├── information.html    # Wedding Information page
├── styles.css          # All styling
└── README.md           # This file
```

## Hosting

This is a static website that can be hosted on:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any web hosting service
- Your own server

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Tips for Updates

1. **Backup your files** before making major changes
2. **Test on mobile** after making changes
3. **Keep image file sizes small** for faster loading
4. **Use descriptive alt text** for accessibility
5. **Update all three pages** when changing navigation or branding

## Support

If you need help customizing the website:
1. Check this README first
2. Look at the existing code structure
3. Make small changes and test frequently
4. The code is well-commented for easy understanding

## Credits

- Built with Bootstrap 5
- Fonts from Google Fonts
- Background images from Unsplash
- Icons are emoji (no external dependencies)

---

**Happy Wedding Planning! 💒** 