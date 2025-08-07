# How to build blogs in Github

## Prerequisites
GitHub account – Sign up if you don’t have one.
Ruby + Bundler + Jekyll installed locally (for customization).
Git installed on your system.
(Optional) Code editor, like VS Code.

## 🚀 Step-by-Step Guide
### 1. Choose a Jekyll Theme
You can:
Browse themes: https://jekyllthemes.io or https://jekyllthemes.org
Or use a minimal default: minima

### 2. Fork or Download a Theme Repo
Find a Jekyll theme repo on GitHub.
Click Fork to copy it to your account.
Or click Code > Download ZIP, and then manually upload it to a new repo.
Rename the repo to: yourusername.github.io to use GitHub Pages auto-deploy.

### 3. Install Jekyll Locally (Optional but Recommended)
This lets you preview and customize your blog before pushing to GitHub.

#### ▶️ For macOS/Linux:
bash
Copy
Edit
gem install bundler jekyll
#### ▶️ For Windows:
Follow this guide: https://jekyllrb.com/docs/installation/windows/

### 4. Clone Your GitHub Repo Locally
bash
Copy
Edit
git clone https://github.com/yourusername/yourusername.github.io
cd yourusername.github.io

### 5. Install Dependencies
If the theme has a Gemfile, run:

bash
Copy
Edit
bundle install

### 6. Preview the Site Locally
bash
Copy
Edit
bundle exec jekyll serve
Open browser: http://localhost:4000

Live updates while editing .html, .md, or .yml files.

### 7. Customize Your Blog
You can now edit:

File	Purpose
_config.yml	Blog settings: title, author, description, URL, theme
_posts/	Your blog articles as markdown files
_layouts/	Page templates
_includes/	Reusable components
assets/	CSS/JS/images
index.md or index.html	Homepage content

You can also add pages like about.md, contact.md, etc.

### 8. Push to GitHub
bash
Copy
Edit
git add .
git commit -m "Initial commit with custom Jekyll blog"
git push origin main
GitHub will automatically build and deploy your Jekyll site.

### 9. Visit Your Site
Go to:

arduino
Copy
Edit
https://yourusername.github.io
🎨 Extra Customization Tips
Change theme colors and layout via CSS in assets/css/style.scss

Add navigation menu in _layouts/default.html

Use plugins like jekyll-seo-tag, jekyll-feed for SEO and RSS

Add Google Analytics, Disqus, etc.

#### ⚠️ Important Notes
GitHub Pages only supports specific Jekyll plugins. See: https://pages.github.com/versions/

If using unsupported plugins, you must build the site locally and push the _site/ folder or use GitHub Actions.

#### 🛠 Want Help Starting From Scratch?
Let me know and I can generate a basic Jekyll blog starter template customized for you, including:

Your blog name and author info

Custom layout

Example posts

SEO and sitemap support