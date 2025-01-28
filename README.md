
 Project Overview  
**Anmolyogi** is an astrology-based web platform aimed at providing personalized services like daily horoscopes, astrology reports, compatibility analysis, and one-on-one sessions with expert astrologers. The website is tailored to astrology enthusiasts seeking an engaging, informative, and user-friendly experience.

Your **responsibility** in this project was focused exclusively on **UI/UX design**, ensuring the interface meets user needs while aligning with the brand’s theme and goals.

---


**Objective**  
To design a visually engaging and easy-to-navigate website that captures the mystical essence of astrology while ensuring usability for a broad audience.  

 **Design Deliverables**  
1. **Wireframes and Prototypes**  
   - Developed low-fidelity wireframes to outline basic layouts.  
   - Created interactive prototypes using Figma for user testing and feedback.  

2. **Responsive Layouts**  
   - Designed layouts that adapt seamlessly to desktops, tablets, and smartphones.  
   - Ensured smooth user journeys across all screen sizes.

3. **Theme and Aesthetics**  
   - Crafted a visually appealing interface using astrology-related motifs like stars, constellations, and zodiac symbols.  
   - Selected color schemes and typography reflecting a mystical, calm, and inspiring atmosphere.  

4. **Accessibility and Usability**  
   - Focused on inclusive design principles to cater to users with different abilities.  
   - Ensured WCAG compliance for text contrast, font size, and navigation.  

5. **User-Centric Approach**  
   - Conducted user research to understand the target audience, which includes astrology enthusiasts ranging from casual visitors to serious followers.  
   - Designed intuitive navigation for features like personalized reports, daily horoscope access, and astrologer booking systems.

---

 **Design Features**  
- **Homepage**  
   - Highlighted services (daily horoscopes, reports, astrologer sessions) with clear call-to-action buttons (e.g., "Get Your Horoscope").  
   - Included a visually engaging hero section with a dynamic quote or animation.  

- **Navigation Bar**  
   - Simple yet intuitive menu with links to core features: Home, Services, About Us, and Contact.  
   - Sticky header to enhance usability.  

- **Astrology Report Page**  
   - Easy-to-read layout showcasing reports, zodiac charts, and graphs.  
   - Dropdown filters for selecting report types (e.g., love, career, or health).  

- **User Dashboard**  
   - Clean and minimalistic design for managing profiles, accessing purchased reports, and tracking appointments with astrologers.  

---

 **Design Tools & Techniques**  
1. **Figma**:  
   - **Wireframing**: Developed low- and high-fidelity wireframes for layout visualization.  
   - **Prototyping**: Enabled interactive mockups to simulate user flows.  
   - **Collaboration**: Shared designs with the team for iterative feedback.  

2. **Adobe Illustrator**:  
   - Designed custom icons and illustrations aligned with the astrology theme.  

3. **Color Palettes**:  
   - Used tools like **Coolors** to generate complementary color schemes.  
   - Theme: Purple, blue, and gold gradients for a mystical yet professional vibe.  

4. **Typography**:  
   - Used legible and elegant fonts (e.g., **Poppins** for body text, **Playfair Display** for headings).  

---
 **Extensions/Frameworks Used**  
- Figma Plugins:  
   - **Unsplash**: To find free astrology-themed imagery.  
   - **Iconify**: For adding zodiac and celestial icons.  
   - **Figmotion**: For animating transitions within the prototype.  
   - **Content Reel**: To simulate dummy text and images for reports.  

- UI Framework References:  
   - **Material Design**: To guide spacing, sizing, and visual hierarchy.  
   - **Atomic Design**: Built reusable UI components for scalability.  

---

 **Impact of Your Design Work**  
1. **Enhanced User Experience**:  
   The intuitive layout and engaging visuals simplify navigation, making it easier for users to access personalized astrology services.  

2. **Boosted Engagement**:  
   Eye-catching design elements like gradients, icons, and animations draw users in, encouraging them to explore the site further.  

3. **Seamless Collaboration**:  
   Delivered ready-to-develop Figma prototypes, enabling the development team to implement the designs with minimal friction.  

---

**CSS Styling**  
```css
/* Root Variables for Global Theme */
:root {
  --primary-color: #6a1b9a; /* Astrology theme: Mystic Purple */
  --secondary-color: #fdd835; /* Bright Yellow for highlights */
  --background-gradient: linear-gradient(to bottom, #1a237e, #311b92);
  --text-color: #ffffff;
  --card-bg: #4527a0;
  --hover-color: #7b1fa2;
  --border-radius: 16px;
  --font-family: 'Poppins', sans-serif;
}

/* Global Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: var(--font-family);
  background: var(--background-gradient);
  color: var(--text-color);
  line-height: 1.6;
}

/* Header Styling */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background: rgba(0, 0, 0, 0.7);
  backdrop-filter: blur(8px);
}

header nav a {
  text-decoration: none;
  color: var(--text-color);
  margin-left: 20px;
  font-size: 1rem;
}

header nav a:hover {
  color: var(--secondary-color);
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 4rem 2rem;
}

.hero h1 {
  font-size: 3rem;
  color: var(--secondary-color);
}

.hero p {
  margin-top: 1rem;
  font-size: 1.2rem;
  color: var(--text-color);
}

/* Cards Section */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  padding: 2rem;
}

.card {
  background: var(--card-bg);
  border-radius: var(--border-radius);
  padding: 1.5rem;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
}

.card h3 {
  color: var(--secondary-color);
  margin-bottom: 1rem;
}

.card p {
  color: var(--text-color);
  font-size: 1rem;
}

/* Footer */
footer {
  text-align: center;
  padding: 1rem;
  background: rgba(0, 0, 0, 0.7);
  color: var(--text-color);
}
```

---

**HTML Structure**  
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anmolyogi - Astrology Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Anmolyogi</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <h1>Unlock Your Destiny</h1>
    <p>Personalized astrology predictions, insights, and more!</p>
  </section>

  <!-- Cards Section -->
  <section class="cards" id="services">
    <div class="card">
      <h3>Daily Horoscope</h3>
      <p>Get insights into your day with our accurate daily horoscopes.</p>
    </div>
    <div class="card">
      <h3>Astrology Reports</h3>
      <p>Detailed reports tailored to your birth chart.</p>
    </div>
    <div class="card">
      <h3>Personalized Guidance</h3>
      <p>One-on-one sessions with our expert astrologers.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Anmolyogi | All Rights Reserved</p>
  </footer>
</body>
</html>
```

---

 **Extensions and Plugins for Figma**  
1. **Iconify**  
   - Offers astrology-themed icons and symbols for use in your designs.  
   - Install: [Iconify Plugin](https://www.figma.com/community/plugin/735098390272716381/Iconify)

2. **Unsplash**  
   - Access high-quality, free images for backgrounds and visuals.  
   - Install: [Unsplash Plugin](https://www.figma.com/community/plugin/738454987945972471/Unsplash)

3. **Color Palettes**  
   - Helps generate astrology-themed color schemes.  
   - Install: [Color Palettes Plugin](https://www.figma.com/community/plugin/770443272579419575/Color-Palettes)

4. **Figma to Code**  
   - Export your Figma designs directly into HTML/CSS for seamless integration.  
   - Install: [Figma to Code](https://www.figma.com/community/plugin/804782110879380120/Figma-to-Code)

5. **Contrast Checker**  
   - Ensures accessibility by verifying text-to-background contrast ratios.  
   - Install: [Contrast Plugin](https://www.figma.com/community/plugin/733249202379192758/Contrast)

---

 **Responsive Frameworks**  
For responsive designs, consider integrating **Tailwind CSS** alongside your CSS code for a utility-first approach. Alternatively, **Bootstrap** is a good choice for grid and component-based designs.  

**Next Steps**  
1. **Add Animations**: Use libraries like **GSAP** or **Framer Motion** to animate transitions and make the site more dynamic.  
2. **SEO Optimizations**: Ensure proper meta tags, alt texts, and a sitemap for better visibility.  
3. **Test Responsiveness**: Use tools like Chrome DevTools or BrowserStack to test your site across devices.  



