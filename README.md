# 🚀 Team Synergy - Portfolio Website

Welcome to the Team Synergy portfolio! This is a professional team portfolio website showcasing your team's skills, projects, and collaborative spirit.

## 📁 File Structure

```
Team Synergy/
├── index.html        # Main HTML file (portfolio structure)
├── styles.css        # CSS styling and responsive design
├── script.js         # JavaScript for interactivity
└── README.md         # This file
```

## 🎯 Features

✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile  
✅ **Modern UI** - Beautiful gradient colors and smooth animations  
✅ **All 5 Team Members** - Complete team member profiles with details  
✅ **Vasishta as Coordinator** - Special badge highlighting team coordinator  
✅ **Skills Map** - Visual representation of team strengths  
✅ **Learning Goals** - Team objectives and areas of focus  
✅ **Open Source Section** - Community interests and contributions  
✅ **Smooth Navigation** - Easy scrolling between sections  
✅ **Contact Information** - Easy-to-find team contact details  

## 🎨 Sections Included

1. **Home** - Eye-catching hero section with team tagline
2. **Team Identity** - Why "Synergy" and team mission
3. **Team Members** - All 5 team members with:
   - Interests
   - Learning goals
   - Career goals
   - Hobbies
   - Special coordinator badge for Vasishta

4. **Team Working Style** - 6 collaboration practices
5. **Skills Map** - Visual skill representation across areas:
   - Frontend
   - Backend
   - IoT
   - Database
   - AI/ML

6. **Learning Goals** - Team objectives, problems to solve, internship goals
7. **Open Source** - Interests, communities, problems they want to solve
8. **Fun** - Fun facts about the team
9. **Contact** - Email, location, and team info

## 🚀 How to Use

### Option 1: Open Directly in Browser
1. Right-click on `index.html`
2. Select "Open with" → Choose your browser
3. The portfolio will load with all styling and animations

### Option 2: Using VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Your portfolio will open in the browser with auto-refresh

### Option 3: Using Python
```bash
python -m http.server 8000
# Then visit: http://localhost:8000
```

## 🎨 Customization

### Update Team Email
Find and replace `your-team-email@example.com` in `index.html` with your actual email.

### Change Colors
In `styles.css`, modify the CSS variables at the top:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #ec4899;
    --accent-color: #f59e0b;
}
```

### Add Team Photos
Replace the initials in `.member-avatar` with actual images:
```html
<div class="member-avatar">
    <img src="path/to/photo.jpg" alt="Name">
</div>
```

Add this CSS to `styles.css`:
```css
.member-avatar img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    object-fit: cover;
}
```

### Update Team Information
- Edit team member details in the "Meet the Team" section
- Update skills proficiency in the "Skills Map" section
- Modify learning goals and open source interests

## 📱 Browser Compatibility

✅ Chrome/Edge  
✅ Firefox  
✅ Safari  
✅ Mobile browsers  

## 🔧 Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Gradients, Animations
- **JavaScript (Vanilla)** - Smooth scrolling, intersection observer
- **Font Awesome 6.4** - Icons (loaded via CDN)

## 🎯 Future Enhancements

Consider adding:
- Blog section for project updates
- Portfolio projects showcase
- Team achievements/awards
- Social media links
- Newsletter signup
- Dark mode toggle
- Multi-language support

## 📧 Support

For any questions about the portfolio structure or customization, feel free to modify the files directly.

## 🌟 Notes

- The coordinator badge highlights Vasishta as the team coordinator
- All team members have distinct profile sections
- The portfolio is fully responsive and mobile-friendly
- Smooth animations enhance user experience
- All information from your brief has been included

---

**Built with ❤️ for Team Synergy**  
*Together we build smarter solutions* 🚀
