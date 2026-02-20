---
layout: default
title: Step 1b - Install Ruby
permalink: /step1b.html
---

# Step 1b: Installing Ruby

Jekyll requires Ruby to run locally.

1. **Download Ruby Installer for Windows. Under "Ruby+Devkit", choose the latest stable version** (for most systems, x64):
[https://rubyinstaller.org/](https://rubyinstaller.org/)

2. **Run the installer:**  
   * Choose recommended settings  
   * Check **“Add Ruby executables to your PATH”**

3. **At the end of installation, the installer will show a prompt.**
```
Choose **Option 1** for a base MSYS2 installation
```
Type 1 and enter.

4. **Verify installation:**
```bash
ruby --version
```
5. **Install bundler:**
```bash
gem install bundler
```
6. **Install Jekyll:**
```bash
gem install jekyll
```

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/step1" class="btn">← Prev</a>
  <a href="{{ site.baseurl }}/step2.html" class="btn">Next →</a>
</div>