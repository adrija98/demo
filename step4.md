---
layout: default
title: Step 4 - Push Changes to GitHub
permalink: /step4.html
---

# Step 4: Push Changes to GitHub

Once your local site is working correctly, push it to GitHub:

1. **Initialize Git (if you haven’t):**
```bash
git init
git add .
git commit -m "Initial commit"
```

2. **Create a GitHub repository named demo_site.**

3. **Link your local repo to GitHub:**
```bash
git remote add origin https://github.com/<your-username>/demo_site.git
git branch -M main
git push -u origin main
```

✅ Your changes are now on GitHub!

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/step3" class="btn">← Prev</a>
  <a href="{{ site.baseurl }}/step5.html" class="btn">Next →</a>
</div>
