# Sonali Jadhav - Individual Clinical Psychology Practice Website

Modern, responsive, bilingual (English & Marathi) landing page for Ms. Sonali Jadhav, MA Clinical Psychologist & Counsellor, Ulhasnagar 4, Maharashtra.

---

## 🚀 How to Host on Render for FREE (Step-by-Step)

Render provides **Free Static Site Hosting** with:
- 100% Free forever (No spin-down / sleep delays)
- Free SSL (HTTPS) certificate
- Custom domain support (e.g., `sonalijadhav.com`)
- Global CDN with fast loading

---

### Step 1: Push This Folder to GitHub

If you haven't pushed this repository to GitHub yet:

1. Go to [GitHub.com](https://github.com) and click **"New repository"**.
2. Name the repository: `sonali-jadhav-psychology` (make it **Public** or **Private**).
3. Do **NOT** initialize with README or .gitignore (we already created them). Click **"Create repository"**.
4. In your terminal (inside this folder `e:\AI\Hospital`), run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Sonali Jadhav psychology website"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/sonali-jadhav-psychology.git
   git push -u origin main
   ```

*(Alternatively, you can drag and drop this folder using [GitHub Desktop](https://desktop.github.com/))*

---

### Step 2: Deploy on Render

1. Log in to [dashboard.render.com](https://dashboard.render.com) (you can Sign In with GitHub).
2. Click the **"New +"** button at the top right and select **"Static Site"**.
3. Choose your GitHub repository: `sonali-jadhav-psychology` and click **"Connect"**.
4. Fill in the simple settings:
   - **Name**: `sonali-jadhav-psychology` (or your preferred name)
   - **Branch**: `main`
   - **Build Command**: *(leave completely blank)*
   - **Publish Directory**: `.` *(a single dot, meaning current folder)*
5. Click **"Create Static Site"**.

Render will deploy your site in about 15 to 30 seconds!
You will get a live URL like:
👉 `https://sonali-jadhav-psychology.onrender.com`

---

### Step 3: (Optional) Connect Your Custom Domain

If you own a custom domain (like `sonalijadhav.in` or `psychologistsonali.com`):
1. In your Render Dashboard, click your static site.
2. Go to **"Settings"** -> **"Custom Domains"**.
3. Click **"Add Custom Domain"** and enter your domain name.
4. Add the CNAME / A records provided by Render into your domain registrar (GoDaddy, Namecheap, Hostinger, etc.).
5. Render automatically generates a free SSL certificate!

---

### Project Files Overview

- `index.html` — The main landing page with bilingual support, appointment wizard, and services.
- `sonali-jadhav.jpg` — Practitioner portrait photo.
- `clinic-consultation.jpg` — Consultation room photo.
- `map-preview.jpg` — Map location tile.
- `render.yaml` — Render automatic configuration blueprint.
- `.gitignore` — Ignores unnecessary temporary system files.
