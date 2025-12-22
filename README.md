# Norouz Peinture – Official Website

This repository contains the source code of the official website of **Norouz Peinture**, a professional painting company based in Angers, France.  
The website is static, optimized for GitHub Pages, and designed to be easy to maintain and update.

---

## 📁 Project Structure

```
/
├── index.html
├── services.html
├── realisations.html
├── a-propos.html
├── contact.html
├── mentions-legales.html
├── politique-confidentialite.html
├── css/
│   └── styles.css
├── assets/
│   ├── img/
│   │   ├── logo.png
│   │   ├── mathieu-portrait-1.jpg
│   │   ├── mathieu-portrait-2.jpg
│   │   └── projects/
│   │       ├── project-01.jpg
│   │       ├── project-02.jpg
│   │       └── ...
└── en/
    ├── index.html
    ├── services.html
    └── ...
```

---

## 🌐 Deployment – GitHub Pages

The website is hosted for free using **GitHub Pages**.

### Configuration:
1. Go to **Settings → Pages**
2. Source: `Deploy from branch`
3. Branch: `main`
4. Folder: `/ (root)`

The site updates automatically after each commit.

---

## 🌍 Custom Domain

The official domain:

```
norouzpeinture.fr
```

### DNS:
- A `CNAME` file is included in the repository.
- DNS records (A + CNAME) must point to GitHub Pages.

---

## 📩 Professional Email (Free via Cloudflare)

Official email address:

```
mathieu@norouzpeinture.fr
```

### How it works:
- No mailbox hosted on a server.
- All incoming emails are forwarded to Gmail using **Cloudflare Email Routing**.

### DNS:
Cloudflare automatically configures:
- MX records  
- SPF  
- TXT verification  

---

## 🖼 Image Management

⚠️ GitHub Pages is **case-sensitive**.  
File names must match exactly.

Correct example:

```html
<img src="assets/img/mathieu-portrait-1.jpg" alt="Mathieu Khalesi">
```

---

## 🛠 How to Update the Website

### Modify a page:
- Edit the `.html` file
- Commit + Push

### Add an image:
- Place it inside `assets/img/` or `assets/img/projects/`
- Use lowercase names without spaces
- Update the HTML path

### Update styles:
- Edit `css/styles.css`

---

## 🚀 Future Improvements

- SEO optimization  
- Full English version  
- Contact form using Formspree or Netlify Forms  
- Minified CSS/HTML  
- SVG icons for a modern look  

---

## 👤 Author

**Mathieu Khalesi**  
Founder – Norouz Peinture  
Angers, France
