# 🎮 Kapeesh Sharma — Portfolio Website

A futuristic, high-performance personal portfolio website built with clean HTML5, CSS3, and modern JavaScript. Designed specifically for **Kapeesh Sharma**, a 19-year-old B.Tech CSE Core student at JECRC University and aspiring Game Developer.

---

## 🌟 Highlights & Features

- **🎮 Cyber & Game Dev Aesthetic**: Neon glow gradients, dark mode styling, and glassmorphism inspired by modern game engines (Unity & Unreal).
- **✨ Interactive Background**: Real-time canvas particle mesh that subtly interacts with cursor movement.
- **⚡ Playable Arcade Mini-Game ("Space Survivor")**:
  - Full HTML5 Canvas playable game built right into the site!
  - Steer the spaceship, dodge/destroy asteroids, and collect purple energy cores.
  - Controls: `Arrow keys` / `A` & `D` to steer, `Spacebar` to shoot lasers (with touch controls for mobile).
  - High score tracking stored in your browser!
- **🔊 Web Audio API 8-Bit Retro Sound Effects**: Real-time synthesized audio (laser blasters, point chimes, explosions) with an instant mute/unmute toggle in the navbar.
- **⌨️ Dynamic Typing Hero**: Showcases your passions, college, and career aspirations automatically.
- **📱 100% Responsive**: Looks great on smartphones, tablets, laptops, and ultra-wide desktop monitors.
- **📫 Direct Contact Section**:
  - Direct 1-click email copy button with tooltip.
  - Direct LinkedIn profile button linked to: `https://linkedin.com/in/kapeesh-sharma-133030419`
  - Integrated message trigger pre-filling your Gmail address: `kapeeshsharma70@gmail.com`.
- **🚀 100% GitHub Pages Ready**: Zero build tools required. Upload directly to GitHub to get a live URL.

---

## 📂 Project Structure

```text
portfolio/
├── index.html        # Main HTML file containing all sections
├── style.css         # Modern cyberpunk & game dev CSS styling
├── script.js         # Canvas particles, typewriter, arcade game & audio logic
├── .nojekyll         # Disables Jekyll processing on GitHub Pages
└── README.md         # Documentation & step-by-step GitHub deployment guide
```

---

## 🚀 How to Host on GitHub Pages (Step-by-Step Guide)

You can publish this portfolio for free with a live URL (e.g., `https://<your-username>.github.io`) using GitHub Pages! Follow these steps:

### Option A: Using the GitHub Website (Quickest & Easiest)

1. **Log in to GitHub**:
   - Go to [GitHub.com](https://github.com) and sign in.
2. **Create a New Repository**:
   - Click the **`+`** icon in the top right corner and select **New repository**.
   - Name your repository (e.g. `portfolio` or `kapeesh-portfolio`).
     > *Tip: If you name it `yourusername.github.io` (replace `yourusername` with your real GitHub username), your website URL will simply be `https://yourusername.github.io`!*
   - Set the repository to **Public**.
   - Do NOT check "Add a README file" (we already have one).
   - Click **Create repository**.
3. **Upload the Files**:
   - On the next screen, click the link that says **"uploading an existing file"**.
   - Drag and drop all the files from this folder (`index.html`, `style.css`, `script.js`, `README.md`, `.nojekyll`).
   - Click **Commit changes**.
4. **Enable GitHub Pages**:
   - In your repository, click **Settings** (tab at the top).
   - In the left sidebar, click **Pages** (under "Code and automation").
   - Under **Build and deployment > Branch**:
     - Select **`main`** (or `master`).
     - Leave the folder as **`/(root)`**.
     - Click **Save**.
5. **View Your Live Website**:
   - Wait 1–2 minutes. Refresh the GitHub Pages settings page.
   - You will see a banner: *"Your site is live at `https://yourusername.github.io/portfolio/`"*.
   - Click the link to open your live portfolio! 🎉

---

### Option B: Using Git in Terminal / Command Prompt

If you have Git installed on your computer:

```bash
# 1. Open terminal inside this folder
cd "c:\Users\HP\OneDrive\Desktop\portfolio"

# 2. Initialize a git repository
git init

# 3. Add all files to staging
git add .

# 4. Commit the files
git commit -m "Initial release of Kapeesh Sharma game developer portfolio"

# 5. Rename branch to main
git branch -M main

# 6. Link to your GitHub repository (replace with your repo URL)
git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/<YOUR-REPO-NAME>.git

# 7. Push to GitHub
git push -u origin main
```

Then go to **Settings > Pages > Branch: `main` > Save**.

---

## 🛠️ How to Customize Later

- **Adding a Resume**:
  - Place your `resume.pdf` into this folder.
  - In `index.html`, add a link `<a href="resume.pdf" class="btn btn-outline" download>Download Resume</a>`.
- **Adding Real Project Screenshots**:
  - Create an `assets/` folder, drop your game screenshots inside, and replace the project icons in `index.html`.
- **Updating Skills & Projects**:
  - Edit `index.html` to add new game engines, game jam entries, or college projects as you create them!

---

## 👨‍💻 About Kapeesh Sharma
- **Age**: 19 Years
- **Education**: B.Tech CSE Core @ JECRC University
- **Aspiration**: Game Developer & Gameplay Programmer
- **Hobbies**: Playing Cricket, Watching Movies, Video Games
- **Email**: [kapeeshsharma70@gmail.com](mailto:kapeeshsharma70@gmail.com)
- **LinkedIn**: [kapeesh-sharma-133030419](https://linkedin.com/in/kapeesh-sharma-133030419)

---
*Created with passion for interactive digital entertainment.*
