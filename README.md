# LazyCat Studio - Developer Website & AdMob app-ads.txt Deployment Guide

This repository contains a professional personal developer website meeting Google Play developer requirements and Google AdMob app-ads.txt verification standards, showcasing three featured Android apps:
1. **EverEver (Safety Guardian)** (`apps/everever.html`)
2. **FakeCall (Simulated Caller)** (`apps/fakecall.html`)
3. **MetalDetector (Magnetic Sensor)** (`apps/metaldetector.html`)

Plus essential pages: Privacy Policy (`privacy.html`), Contact Support (`contact.html`), and AdMob verification (`app-ads.txt`).

---

## 🚀 Deployment Steps (Using GitHub Pages Free Hosting)

### Step 1: Create a GitHub Repository
1. Log in to your [GitHub](https://github.com/) account.
2. Click the `+` icon in the top right corner and select **New repository**.
3. Enter a repository name (e.g., `lazycat-studio`), set it to **Public**, check **Add a README file**, and click **Create repository**.

### Step 2: Upload Website Files
1. Upload all contents from the `developer_website` folder (`index.html`, `privacy.html`, `contact.html`, `app-ads.txt`, `apps/` folder, etc.) into the root of your GitHub repository.
   - Or upload via Git command line:
     ```bash
     git init
     git remote add origin https://github.com/your-username/repository-name.git
     git add .
     git commit -m "Initial English developer website commit"
     git branch -M main
     git push -u origin main
     ```

### Step 3: Enable GitHub Pages
1. Go to your GitHub repository page and click **Settings**.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment** -> **Branch**:
   - Select branch: `main`
   - Select folder: `/ (root)`
4. Click **Save**.
5. Within 1-2 minutes, GitHub will provide your free website URL:
   `https://your-username.github.io/repository-name/`

---

## 🛠️ Configure AdMob app-ads.txt

1. Open `app-ads.txt`.
2. Replace `pub-XXXXXXXXXXXXXXXX` with your actual AdMob Publisher ID from the Google AdMob Console (Account -> App-ads.txt).
3. Commit the change to your GitHub repository.
4. Verify accessibility at: `https://your-username.github.io/repository-name/app-ads.txt`.
5. Submit the URL in the AdMob console for verification (typically takes 24-48 hours).

---

## 📱 Google Play Console Website Settings

1. Log in to [Google Play Console](https://play.google.com/console).
2. Go to **Store presence** -> **Store settings**.
3. Under **Contact details** -> **Website**, enter your GitHub Pages URL.
4. Under **Privacy policy**, enter your privacy policy URL (`https://your-username.github.io/repository-name/privacy.html`).
