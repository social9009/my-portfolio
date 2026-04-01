# 🚀 Akshay Sawant — AWS DevOps Engineer Portfolio

[![AWS Certified](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![DevOps](https://img.shields.io/badge/Role-AWS_DevOps_Engineer-00D4FF?style=for-the-badge&logo=amazonwebservices&logoColor=white)](https://github.com/yourusername/portfolio)
[![Experience](https://img.shields.io/badge/Experience-4.5_Years-00FF88?style=for-the-badge)](https://github.com/yourusername/portfolio)
[![Location](https://img.shields.io/badge/Location-Pune,_India-FF6B2B?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com)

> Personal portfolio website built with pure **HTML, CSS, and JavaScript** — no frameworks, no build tools. Fully static, deployable anywhere.

🌐 **Live Demo:** [https://yourusername.github.io/portfolio](https://yourusername.github.io/portfolio)

---

## 📂 Project Structure

```
portfolio/
├── index.html              # Main portfolio page (single-file app)
├── assets/
│   ├── profile.jpg         # Your profile photo ← ADD THIS
│   └── resume.pdf          # Your resume PDF ← ADD THIS
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

---

## ✨ Features

- 🌑 **Dark tech theme** with animated background grid
- 🖱️ **Custom cursor** with hover glow effects
- 🎞️ **Smooth scroll reveal** animations on all sections
- 💫 **Floating particles** background effect
- 📱 **Fully responsive** — works on mobile, tablet, desktop
- ⚡ **Zero dependencies** — pure HTML/CSS/JS, no npm, no build step
- 🎨 Cyan/orange AWS-inspired color palette

---

## 🛠️ Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, title, stats card, CTA buttons |
| **About** | Bio, contact info, AWS certification |
| **Skills** | 6 skill categories with hover effects |
| **Experience** | Timeline with 3 roles (2017–2025) |
| **Projects** | 3 featured DevOps projects |
| **Contact** | Email, phone, GitHub, LinkedIn |

---

## 🚀 Quick Start (Run Locally)

```bash
# Clone the repo
git clone https://github.com/yourusername/portfolio.git
cd portfolio

# Option 1: Open directly in browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# Option 2: Serve with Python (recommended)
python3 -m http.server 8080
# Open: http://localhost:8080

# Option 3: Serve with Node.js npx
npx serve .
# Open: http://localhost:3000
```

---

## 📸 Adding Your Profile Photo

1. Get your photo (crop it square, min 400×400px)
2. Save it as `assets/profile.jpg`
3. The website auto-loads it — fallback shows initials "AS" if missing

```bash
# Example: copy from Downloads
cp ~/Downloads/my-photo.jpg assets/profile.jpg
```

---

## 🌍 Deploy to GitHub Pages (Free Hosting)

```bash
# Step 1: Initialize git (if not done)
git init
git add .
git commit -m "Initial portfolio commit"

# Step 2: Create repo on GitHub (github.com → New Repository)
# Name it: portfolio  (or yourusername.github.io for root domain)

# Step 3: Push to GitHub
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main

# Step 4: Enable GitHub Pages
# Go to: Settings → Pages → Source: Deploy from branch → main → / (root) → Save

# Your site will be live at:
# https://yourusername.github.io/portfolio
```

---

## 🐳 Run in Docker (for hosting inside a container)

```bash
# Build the Docker image
docker build -t akshay-portfolio .

# Run the container
docker run -d -p 80:80 --name portfolio akshay-portfolio

# Access at: http://localhost
```

### Dockerfile (create this file):
```dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

---

## ✏️ Customization

| What to change | Where |
|----------------|-------|
| Name / title | `index.html` → hero section |
| GitHub URL | Search `yourusername` → replace all |
| LinkedIn URL | Search `yourprofile` → replace |
| Colors | CSS `:root` variables at top of `<style>` |
| Projects | `#projects` section in `index.html` |
| Profile photo | Replace `assets/profile.jpg` |

---

## 📬 Contact

- **Email:** akshaysawant9009@gmail.com
- **Phone:** +91 9096505065
- **Location:** Hinjawadi, Pune, Maharashtra

---

## 📄 License

MIT License — free to use as a template. Credit appreciated but not required.
