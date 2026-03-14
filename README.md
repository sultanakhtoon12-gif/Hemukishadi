# Wedding Invitation - Aashiya & Azam 💍

## Complete Wedding Website Package

This package contains the complete, production-ready wedding invitation website with all features and assets.

---

## 📦 What's Included

### Files & Folders:
```
wedding-invitation/
├── index.html              # Main entry point
├── asset-manifest.json     # Asset references
├── audio/                  # Wedding ceremony music
│   ├── kabira.mp3         # Opening & Closing music
│   ├── london_thumakda.mp3 # Haldi ceremony music
│   ├── khudmai.mp3        # Nikah ceremony music
│   └── mehendi.mp3        # (Not used in current version)
├── static/
│   ├── css/
│   │   └── main.*.css     # All styles (Royal colors, textures, animations)
│   └── js/
│       └── main.*.js      # All functionality (React, animations, audio control)
└── audio-test.html        # Audio testing page
```

---

## 🎨 Features Included

### ✨ Sections:
1. **Opening Section** - Burgundy & Gold with Bismillah
   - Bride: Aashiya Alam (D/o Mokhtar Alam)
   - Groom: Azam Khan (S/o Late Nasim Khan)

2. **Haldi Ceremony** - 6th April 2026, 7:00 PM
   - Warm yellow/orange theme
   - Floral patterns & animations

3. **Milad-un-Nabi** - 7th April 2026, 7:00 PM
   - Spiritual amber theme
   - Complete silence (no music)
   - Arabic duas

4. **Nikah Ceremony** - 9th April 2026
   - **Nikah: 8:00 PM**
   - **Dinner: 9:00 PM**
   - Venue: Hasmat Palace, Nawab Road, Chandwara, Muzaffarpur
   - Rich purple & maroon theme with velvet textures

5. **Closing Section** - Burgundy & Gold finale
   - Invitation message
   - Compliments from: Md. Mokhtar Alam
   - Address: At. Haal Sahab, Compound Woad No-45, Chandwara, Muzaffarpur, Bihar

### 🎵 Audio System:
- **Auto-play** on "Enter" button click
- **Section-based switching** (only ONE song plays at a time)
- **Smooth fade transitions** between songs
- **Complete silence** during Milad section

### 🎭 Design Features:
- **Royal color palette**: Burgundy, Gold, Purple, Maroon, Amber
- **Luxury textures**: Silk, Brocade, Velvet, Damask patterns
- **Animations**: 
  - Rotating mandalas
  - Floating paisley patterns
  - Scaling lotus flowers
  - Gold sparkles with depth effect
- **Optimized performance**: Smooth on all devices (no lag)

---

## 🚀 How to Use

### Option 1: Direct Hosting (Recommended)
1. **Upload the entire `build` folder** to your web hosting:
   - Vercel
   - Netlify
   - GitHub Pages
   - Any static hosting service
   - Your own web server

2. **That's it!** The website will work immediately.

### Option 2: Local Testing
1. Open `index.html` directly in your browser
   - **Note**: Audio may not work due to browser security
   - Use a local server instead:
   
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Then open: http://localhost:8000
```

### Option 3: Deploy to Vercel (Free & Easy)
1. Create account at vercel.com
2. Drag & drop the `build` folder
3. Get your live URL instantly!

---

## 📱 Browser Compatibility

**Fully tested on:**
- ✅ Chrome (Desktop & Mobile)
- ✅ Safari (Desktop & Mobile)
- ✅ Firefox
- ✅ Edge
- ✅ Samsung Internet
- ✅ Opera

**Requirements:**
- Modern browser (2020+)
- JavaScript enabled
- **Audio**: Requires user interaction (click "Enter" button)

---

## 🎵 Audio Notes

### Why Audio Needs "Enter" Button:
Modern browsers block auto-play audio until user interacts with the page. This is a security feature - it's normal and expected.

### Audio Sources:
All audio files are **MP3 format** located in the `/audio/` folder:
- `kabira.mp3` - 2.4 MB
- `london_thumakda.mp3` - 3.3 MB
- `khudmai.mp3` - 4.9 MB

### Audio Flow:
1. **Click "Enter"** → Kabira plays
2. **Scroll to Haldi** → London Thumakda plays
3. **Scroll to Milad** → Silence
4. **Scroll to Nikah** → Khudmai Ke Din plays
5. **Scroll to Closing** → Kabira returns

---

## 🎨 Customization

### Want to Change Something?

**Colors**: All colors are in `static/css/main.*.css`
- Search for: `--primary`, `--secondary`, color values

**Text Content**: Embedded in `static/js/main.*.js`
- Names, dates, venues are in the JavaScript bundle

**Audio**: Replace files in `/audio/` folder with same names

**For Major Changes**: You'll need the source code (React project)

---

## 📏 Performance Specs

**File Sizes:**
- Total package: ~15 MB (with audio)
- JavaScript: 109 KB (gzipped)
- CSS: 12.6 KB (gzipped)
- Audio files: ~10.6 MB total

**Load Time:**
- First load: 2-4 seconds (depends on connection)
- Subsequent visits: Instant (cached)

**Optimizations Applied:**
- Reduced animations (6 sparkles instead of 12)
- Optimized textures (4 layers max)
- Smooth animation durations (15-30s)
- Lazy loaded audio
- Image optimization
- Code minification

---

## 🔒 Privacy & Security

- ✅ No tracking scripts
- ✅ No analytics
- ✅ No cookies
- ✅ No external API calls (except fonts from Google)
- ✅ All assets self-hosted (except audio CDN URLs)
- ✅ No personal data collected

---

## 💡 Tips for Best Experience

1. **Use a real domain** for sharing (not file://)
2. **Test on mobile** before sending invitations
3. **Check audio** on different devices
4. **Consider WhatsApp preview** (some features may not show)
5. **Have a backup** (keep this zip file safe)

---

## 🆘 Troubleshooting

### Audio not playing?
- Make sure you clicked "Enter" button
- Check browser volume/mute settings
- Try a different browser
- Check if files are in `/audio/` folder

### Website looks broken?
- Make sure ALL files are uploaded (including audio folder)
- Check browser console for errors (F12)
- Try clearing browser cache

### Slow performance?
- This is a rich, animated website
- Older devices may struggle slightly
- Consider reducing animations in CSS

---

## 📞 Support

This is a complete, self-contained package. Everything you need is included!

**What's Working:**
✅ All sections load correctly
✅ Audio plays with smooth transitions
✅ Animations run smoothly
✅ Mobile responsive
✅ All dates, venues, names correct
✅ Royal colors and textures applied

---

## 🎉 Final Checklist

Before going live, verify:
- [ ] All names spelled correctly
- [ ] All dates correct
- [ ] All venues correct
- [ ] All timings correct
- [ ] Audio files play
- [ ] Test on mobile
- [ ] Test on different browsers
- [ ] Share with family for review

---

**Made with ❤️ for Aashiya & Azam's Special Day**

*May your union be blessed with love, happiness, and prosperity! 💍✨*
