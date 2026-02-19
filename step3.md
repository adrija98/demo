---
layout: default
title: Step 3 - Folder Structure Overview
permalink: /step3.html
---

# Step 3: Folder Structure & Cleanup

After creating a new Jekyll site using:

```bash
jekyll new demo_site
```

Your folder looks like this by default:

```
demo_site/
├── _config.yml
├── _posts/
│   └── 2026-02-19-welcome-to-jekyll.md
├── index.md
├── about.md
├── Gemfile
└── other default files...
```

---

## 1️⃣ Default Folders & Files

   - ```_posts/``` — contains blog posts. Can be deleted if you are making a static demo site.
   - ```index.md``` — your home page. Keep it.
   - ```about.md``` — example page. Optional; can be kept or deleted.
   - ```_config.yml``` — configuration for your site. Keep it.
   - Gemfile & Gemfile.lock — used for dependencies. Keep if you plan to use bundle.

---

## 2️⃣ Restructuring for a Simple Demo

You can simplify the site by creating your own structure:
```
demo_site/
├── _config.yml
├── _layouts/
│   └── default.html       # Your HTML template
├── assets/
│   └── style.css          # Styling changes
├── index.md
├── page1.md               
└── page2.md           
```

**Tips:**
   - Delete ```_posts/``` if you don’t need blog functionality
   - Add ```_layouts/default.html``` manually (Jekyll won’t create it)
   - Create ```assets/style.css``` for custom styling
   - Keep index.md as your main page

---

## 3️⃣ Checking Changes Locally

Before you push your changes to GitHub, you should check that your site works locally:

1. Navigate to your project folder:
```bash
cd demo_site
```

2. Install dependencies (if you haven’t already):
```
bundle install
```
3. Build and serve your site locally:
```
bundle exec jekyll serve
```
4. Open your browser and go to: [http://localhost:4000](http://localhost:4000/).
You should see your site as it would appear online.

**Tips:**
  - Refresh the page after changes; Jekyll auto-rebuilds by default.
  - Check all pages and links to ensure nothing is broken.



<div class="nav-buttons">
  <a href="{{ site.baseurl }}/step2" class="btn">← Prev</a>
  <a href="{{ site.baseurl }}/step4.html" class="btn">Next →</a>
</div>
