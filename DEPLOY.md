# 📦 دليل النشر | Deployment Guide

<div align="center">

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=githubpages&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflarepages&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

</div>

---

## 🚀 GitHub Pages (الطريقة الموصى بها)

### Setup | الإعداد

```bash
# 1. Push to main branch
git push origin main

# 2. GitHub Actions will auto-deploy
```

### Manual Deployment | النشر اليدوي

1. اذهب إلى **Settings > Pages**
2. Source: **Deploy from a branch**
3. Branch: **`gh-pages`** / **(root)**
4. احفظ

---

## ☁️ Cloudflare Pages

### الطريقة 1: GitHub Integration (تلقائي)

1. اذهب إلى [Cloudflare Dashboard](https://dash.cloudflare.com)
2. **Workers & Pages > Create application > Pages**
3. Connect to **GitHub**
4. الإعدادات:
   - **Production branch**: `main`
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`

### الطريقة 2: Wrangler CLI

```bash
npm install -g wrangler
wrangler pages deploy dist
```

### الطريقة 3: Drag & Drop

1. `npm run build`
2. اسحب مجلد `dist` إلى Cloudflare

---

## 🌐 Netlify

```bash
# Build
npm run build

# Deploy via CLI
netlify deploy --prod --dir=dist
```

---

## ▲ Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

---

## ⚙️ إعدادات البناء | Build Settings

```json
{
  "Build Command": "npm run build",
  "Output Directory": "dist",
  "Install Command": "npm install"
}
```

---

## 🔧 Environment Variables (اختياري)

```env
# Base path for subdirectory deployment
BASE_PATH=/

# Firebase (if using)
VITE_FIREBASE_API_KEY=...
VITE_FIREBASE_AUTH_DOMAIN=...
VITE_FIREBASE_DATABASE_URL=...
```

---

## ✅ Checklist للنشر

- [x] الكود نظيف (بدون node_modules)
- [x] `.nojekyll` موجود
- [x] `_redirects` أو `404.html` للإرسال التوجيهي
- [x] GitHub Actions workflow محدث
- [x] البناء يعمل محلياً

---

<div align="center">

**جاهز للنشر!** 🚀  
**Ready to Deploy!** 🚀

</div>
