# Jompol Rheemnok — Portfolio Website

## 🚀 Setup (GitHub Pages)

### 1. สร้าง Repository
```
ชื่อ repo: <your-github-username>.github.io
```

### 2. โครงสร้างไฟล์
```
your-username.github.io/
├── index.html              ← ไฟล์หลัก (อันนี้)
├── Resume_AI_Engineer.pdf  ← ใส่ resume ไว้ที่นี่
└── images/
    └── photo.jpg           ← รูปโปรไฟล์ (optional)
```

### 3. ใส่รูปโปรไฟล์
ใน index.html หาบรรทัด:
```html
<div class="avatar-placeholder">🤖</div>
```
แล้วแทนด้วย:
```html
<img src="images/photo.jpg" class="avatar-img" alt="Jompol">
```

### 4. Push ขึ้น GitHub
```bash
git init
git add .
git commit -m "init portfolio"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

### 5. Enable GitHub Pages
- Settings → Pages → Source: Deploy from branch → main

เว็บจะขึ้นที่ `https://<username>.github.io` ใน 1-2 นาที
