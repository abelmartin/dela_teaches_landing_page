# Dela Teaches — Jekyll Landing Page & Language Blog

Official website for **Dela Teaches LLC** ([delateaches.com](https://delateaches.com)), built with [Jekyll](https://jekyllrb.com/) and hosted natively on [GitHub Pages](https://pages.github.com/).

---

## 🚀 Quick Start: Running Locally

Follow these steps to preview and edit the site locally before pushing changes to GitHub.

### 1. Prerequisites
Ensure you have Ruby and Bundler installed on your system:
- **Ruby** (v3.0+)
- **Bundler** (`gem install bundler`)

### 2. Install Dependencies
Run the following command in the project root to install Jekyll and required GitHub Pages gems:

```bash
bundle install
```

### 3. Start the Development Server
To launch Jekyll's local preview server with live reloading:

```bash
bundle exec jekyll serve --livereload
```

Once started, open your web browser and navigate to:
👉 **`http://localhost:4000`**

Any changes you make to Markdown files (`.md`), layouts, or CSS will automatically update in your browser.

---

## 🛠️ Project Structure

```text
├── _config.yml         # Site metadata, permalink patterns & GitHub Pages plugins
├── Gemfile             # Ruby gem dependencies (github-pages)
├── index.md            # Home page (/)
├── about.md            # About Dela (/about/)
├── lessons.md          # Lessons & Pricing (/lessons/)
├── testimonials.md     # Student Reviews (/testimonials/)
├── quick-start.md      # How to Get Started (/quick-start/)
├── newsletter.md       # Newsletter landing page (/newsletter/)
├── contact.md          # Contact & Discovery Call booking (/contact/)
├── blog/
│   └── index.html      # Blog post index (/blog/)
├── _posts/             # Blog article Markdown files
│   ├── YYYY-MM-DD-title.md
├── _layouts/           # Page templates (default.html, page.html, post.html)
├── _includes/          # Reusable components (header.html, footer.html, newsletter-form.html)
└── assets/
    └── css/style.css   # Main stylesheet (purple/gold brand theme)
```

---

## 📝 Writing & Publishing Blog Posts

To publish a new blog post:

1. Create a new `.md` file inside `_posts/` with the filename format:
   ```text
   YYYY-MM-DD-your-post-title.md
   ```
2. Include the front matter header at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title Here"
   date: 2026-07-28 10:00:00 -0400
   author: "Dela"
   categories: language-learning
   tags: [pronunciation, fluency]
   ---
   ```
3. Write your post content using standard Markdown syntax below the header.
4. When published, Jekyll automatically generates the post URL at:
   `https://delateaches.com/blog/your-post-title`

---

## 📦 Building for Production & GitHub Deployment

GitHub Pages natively detects Jekyll in your repository and builds the site automatically when changes are pushed to your main branch.

To manually verify the production build locally before committing:

```bash
bundle exec jekyll build
```

This compiles the static site into the `_site/` directory (which is ignored by Git).

---

## ⚙️ GitHub Repository Configuration Checklist

When pushing to GitHub for the first time or setting up deployment, verify the following settings in your repository:

### 1. Enable GitHub Pages Deployment
1. Go to your repository on GitHub: `https://github.com/<your-username>/dela_teaches_landing_page`.
2. Click **Settings** (top navigation tab) &rarr; **Pages** (left sidebar under *Code and automation*).
3. Under **Build and deployment**:
   - **Source**: Select **Deploy from a branch**.
   - **Branch**: Select **`main`** and **`/ (root)`**.
   - Click **Save**.

### 2. Verify Custom Domain & HTTPS
1. Under **Custom domain**, ensure `delateaches.com` is listed (populated automatically by the `CNAME` file).
2. Check **Enforce HTTPS** (this ensures all visitor traffic is securely encrypted over `https://`).

### 3. Push Your Changes
Run the following terminal commands to publish your update:
```bash
git add .
git commit -m "Convert site to Jekyll with real routes and language blog"
git push origin main
```

### 4. Monitor Deployment Status
1. Click the **Actions** tab at the top of your GitHub repository.
2. You will see an automated workflow run titled **pages-build-deployment**.
3. Once the workflow turns **Green** (completed in ~30–60 seconds), your site is live at [delateaches.com](https://delateaches.com)!

