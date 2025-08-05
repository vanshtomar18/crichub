
# 🏏 CricHub – Seamless Learning for Brighter Future

CricHub is a modern, responsive learning platform designed around the theme of cricket. It aims to educate, inspire, and provide meaningful content through clean design, responsive layouts, and structured components.

## 🌐 Live Preview

You can host the project using [GitHub Pages](https://pages.github.com/) or any static hosting platform (Netlify, Vercel, etc.).

## 📁 Folder Structure

```
project-root/
│
├── index.html             # Main HTML file
├── style.css              # All styles included within a single <style> tag
├── images/                # Folder for assets (logos, illustrations, icons)
│     ├── cricket logo.jpg
│     ├── google logo.png
│     ├── ball.jpeg
│     ├── etc...
```

## 📌 Features

### ✅ Responsive Header
- Logo + navigation links
- Hidden menu + hamburger icon on small screens
- CTA button: "Contact Us"

### ✅ Hero Section
- Bold heading and subheading
- Image with animation on larger screens
- Button group: "Start Now" and "Take Tour"

### ✅ Partner Logos
- Grid of trusted companies: Google, Microsoft, Aaj Tak, Walmart

### ✅ Feature Cards
- 6 custom-styled cards with:
  - Icons
  - Titles
  - Descriptions

### ✅ Testimonials
- 3 testimonial boxes with:
  - Quote
  - Image
  - Author and role

### ✅ Newsletter
- Email input field with custom `Send` button
- JavaScript function to validate and alert user
- Prevents default form behavior

### ✅ Footer
- CricHub branding
- Product, Company, Support, Legal links
- Social media icons
- Copyright

## 🖥️ Technologies Used

- **HTML5**
- **CSS3** – custom media queries, animations, flex/grid
- **JavaScript** – form interaction, DOM updates
- **Google Fonts** – "Inter"
- **Responsive Design** – works on devices <305px and beyond

## 🧠 JS Interactivity

```js
// Changes paragraph text when clicked
function changeText(){
  let send = document.getElementById('news_p');
  send.innerHTML = "Phle cricket ka C to seekh le ja";
  event.preventDefault();
}

// Alerts on Send button click
function sendbtn(){
  alert("Your Email has been received.");
}
```

## 📱 Responsiveness

| Screen Width      | Behavior                                       |
|-------------------|------------------------------------------------|
| < 810px           | Hero section stacks vertically                |
| < 880px           | Feature cards become single column            |
| < 752px           | Nav bar is hidden                              |
| < 305px           | Buttons and some elements hidden automatically |

## 🖼️ Images Required

You’ll need to place these in an `images/` folder or link from a CDN:

- `cricket logo.jpg`
- `cricket.jpg`
- `google logo.png`
- `Microsoft_logo.svg`
- `Aaj_tak_logo.png`
- `walmart logo.jpg`
- `idea logo.jpg`
- `video logo.jpg`
- `handshake.jpg`
- `comp.jpg`
- `call.jpg`
- `graph.avif`
- `wasay habib.jpg`
- `vikratn gupta.jpg`
- `gambhir.webp`
- `ball.jpeg`
- `instaLogo.png`, `fblogo.jpg`, `linkedinLogo.jpg`, `twitter.png`

## ✨ Future Improvements

- Add backend to store newsletter emails
- Add authentication & dashboard
- Implement animation with Typed.js for the hero section role
- Make it a React/Vue app for dynamic rendering

## 🧑‍💻 Author

**Vansh Tomar**  
B.Tech CSE Student | Cricket Enthusiast | Frontend Developer

## 📄 License

This project is for educational and personal portfolio purposes only.
