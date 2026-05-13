# PETA-Z · Revista de Cannabis

Professional cannabis magazine website with editorial structure, community voting, and multimedia integration.

## 📋 Project Overview

PETA-Z is a serious, context-driven cannabis publication designed to organize information around regulation, cultivation, wellness, culture, and data verification. The platform combines editorial journalism with community participation through voting mechanisms and monthly featured strains.

## 🎯 Core Features

### Editorial Structure
- **Actualidad** - Legal changes, market updates, sector pulse
- **Cultivo** - Practical growing guides, substrates, lighting
- **Bienestar** - CBD, wellness, consumption formats
- **Estudios y Datos** - Fact-checking, rumor verification, research
- **Cultura** - Interviews, clubs, music, social context
- **Guías** - Evergreen content for new readers

### Community Engagement
- **Weed del Mes** - Monthly featured strain reviews with:
  - Editorial review and tasting notes
  - Seed bank information
  - Specs: Provider, flavor profile, plant type, editorial assessment
  - Open voting system with sorteo (giveaway)
  - Participation form with email collection

### Multimedia
- **PETA-Z TV** - YouTube playlist integration
  - 24-hour rotating programming schedule
  - Live broadcast simulation with hourly blocks
  - Featured video module
  - Mute/unmute controls
  - Progress tracking with countdown timer

### Editorial Team
- **Daniel** - Context & regulation
- **Laura** - Wellness & general audience
- **Pedro** - Cultivation techniques
- **Carla** - Data verification

## 🏗️ Technical Stack

- **Frontend**: HTML5, CSS3 (custom design system)
- **Styling**: CSS Grid, Flexbox, CSS Variables
- **Interactive Features**: Vanilla JavaScript
- **Video**: YouTube IFrame API
- **Storage**: LocalStorage for demo voting
- **Design System**: Custom color palette with design tokens

## 🎨 Design System

### Color Palette
```
--bg: #f5f0e6 (warm background)
--paper: rgba(255, 251, 244, 0.88) (card surfaces)
--ink: #181512 (primary text)
--green: #2b6a3c (brand secondary)
--green-deep: #1d4729 (accent)
--gold: #d5b166 (highlight)
```

### Typography
- **Headings**: Oswald (400, 500, 700)
- **Body**: Public Sans (400, 500, 600, 700)
- **Monospace**: IBM Plex Mono (400, 500)

## 📱 Responsive Design

- Desktop-first layout with 1440px max-width
- Tablet optimizations (1100px breakpoint)
- Mobile-friendly (720px breakpoint)
- Fluid grid system with CSS clamp()

## 🎮 Interactive Components

### Vote System
```javascript
// Monthly voting form
- Name input
- Email collection
- Score selection (10/7/4 scale)
- LocalStorage persistence (demo)
- Sorteo entry mechanism
```

### YouTube Player Integration
```javascript
// Features:
- Playlist integration (24 rotating videos)
- Featured video priority
- Hourly schedule simulation
- Mute/unmute controls
- Progress bar with countdown
- Live sync functionality
```

### Time Display
- Real-time clock (Madrid timezone)
- Spanish date formatting
- 24-hour format

## 📂 File Structure

```
index.html          # Single-page application with embedded CSS & JS
                   # Contains full editorial design, forms, and player
```

## 🚀 Quick Start

1. **Open in browser**: Simply open `index.html` in any modern web browser
2. **No dependencies**: All code is self-contained (external: Google Fonts, YouTube API)
3. **Demo mode**: Vote form saves to localStorage for testing

## 🔧 Configuration

Edit the `CONFIG` object in the JavaScript section:

```javascript
const CONFIG = {
  playlistId: "PLbqctNqeN92RckkeX6w0ZvsA7uU3z2oYC",  // YouTube playlist ID
  featuredVideoId: "ksrz_urRlOk",                     // Hero video
  timezone: "Europe/Madrid",                           // Local timezone
  labels: {                                            // Custom video labels
    ksrz_urRlOk: "Pieza destacada PETA-Z",
    hIGVxeoeETg: "Capítulo base de la playlist"
  }
};
```

## 📋 Vote Form Data Structure

```javascript
{
  month: "2026-04",
  name: "User Name",
  email: "user@example.com",
  score: "10",  // 10 = featured, 7 = good candidate, 4 = not convinced
  weed: "Blue Dream Auto"
}
```

## 🔗 External Resources

- Google Fonts (Oswald, Public Sans, IBM Plex Mono)
- YouTube IFrame API
- Responsive across all modern browsers

## 📝 Content Sections

### Hero Section
- Brand identity
- Value proposition
- Call-to-action buttons
- Feature highlights

### Main Grid
- 2-column layout: editorial content + sidebar
- Story cards with mini-tags
- Section navigation

### Side Column
- Editorial team bios
- Newsletter signup
- Future feature ideas

## 🎯 SEO & Meta

- Responsive meta viewport
- Spanish language markup
- Semantic HTML structure
- Accessibility considerations in color contrast

## 📊 Demo Features

- ✅ Functional vote form (LocalStorage)
- ✅ YouTube player integration
- ✅ Real-time clock with Madrid timezone
- ✅ Responsive design
- ✅ CSS animations and transitions
- ✅ Interactive guide/playlist

## 🔮 Future Development

- Ranking history of featured strains
- Expanded tasting sheet with terpene profiles
- Legal framework for sorteo (jurisdiction-specific)
- Backend integration for form processing
- Database for vote persistence
- User accounts & personalization

## 💚 Brand Voice

Professional, informative, and context-driven. No hype, clear language, anti-marketing approach. The publication treats cannabis as both a regulatory subject and cultural phenomenon.

---

**Version**: 0.1 (Demo)  
**Status**: Ready for browser testing  
**Last Updated**: May 2026
