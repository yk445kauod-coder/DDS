# 🖥️ نظام العرض الديناميكي (DDS)
# Dynamic Display System - Enterprise AI Platform

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.2.0-61dafb?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.2-3178c6?style=flat-square&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-7.3.2-646cff?style=flat-square&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1.14-38bdf8?style=flat-square&logo=tailwindcss)
![Node.js](https://img.shields.io/badge/Node.js-20.x-green?style=flat-square&logo=node.js)
![Firebase](https://img.shields.io/badge/Firebase-12.15.0-orange?style=flat-square&logo=firebase)

[![Deploy to GitHub Pages](https://github.com/yk445kauod-coder/DDS/actions/workflows/deploy.yml/badge.svg)](https://github.com/yk445kauod-coder/DDS/actions/workflows/deploy.yml)
[![GitHub Stars](https://img.shields.io/github/stars/yk445kauod-coder/DDS?style=social)](https://github.com/yk445kauod-coder/DDS/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/yk445kauod-coder/DDS?style=social)](https://github.com/yk445kauod-coder/DDS/network/members)

---

## 🌟 منصة العرض الديناميكي الذكي

> **منصة ذكية لتحويل بيانات نشاطك إلى تجارب رقمية تفاعلية**

DDS هو نظام عرض ديناميكي متقدم وقابل للتخصيص بدرجة عالية. يقوم بتحويل واجهات الأعمال الثابتة إلى منظومة تفاعلية تعتمد على البيانات. مناسبة لـ **العيادات، الفنادق، الأكاديميات، التجارة الإلكترونية، التجزئة، اللوحات الرقمية، المقاهي، والمعارض الشركاتية**.

</div>

---

## ✨ المميزات الرئيسية | Key Features

| الميزة | Description |
|--------|-------------|
| 🚀 **أداء عالي** | مبني بـ Vite للتجميع السريع والتحميل الفوري |
| 🎨 **تصميم عصري** | واجهة RTL/LTR مع دعم كامل للغة العربية |
| 🤖 **مساعد ذكي** | نظام AI متقدم للإدارة والتحكم |
| 📱 **متجاوب** | تصميم متجاوب لجميع الأجهزة |
| ⚡ **سريع** | React + TypeScript للأداء الأمثل |
| 🔒 **آمن** | Firebase للمصادقة والتخزين |

---

## 🚀 الوحدات الرئيسية | Key Modules

### 📄 صفحة الهبوط للتسويق (`/`)
صفحة أنيقة بتأثير سينمائي مع ميزات تفاعلية:
- **محاكي القطاعات الحي**: النقر على رقائق القطاعات (طبي، فاخر، تعليمي، تجزئة، رقمي، مقهى، مخصص) يغير الواجهات والألوان فوراً
- **شبكات خلفية سينمائية**: مبنية بـ CSS neon mesh مع حركات سلسة
- **الأسئلة الشائعة والتسعير**: جداول كاملة بالعربية والإنجليزية

### 📱 تطبيق العرض للعميل (`/menu`)
كتالوج موجهة للعميل داخل إطار موبايل واقعي:
- **تصميم موبايل أولاً**: شريط حالة مع ساعة حية وإشارات الشبكة
- **بطاقات تفاعلية**: عرض المنتجات والملفات الديناميكية
- **بحث ذكي**: نظام بحث يدعم المرادفات ويزيل الحركات

### 🧠 مركز التحكم بالذكاء الاصطناعي (`/admin`)
منظومة تحكم ذكية للتنسيق متعدد الوكلاء:
- **وكيل النواة العام**: يوزع المهام على الوكلاء المتخصصين
- **5 وكلاء متخصصين**: DevOps، المصمم، المساعد، المحلل، المنشئ

---

## 🔒 الأمان والترخيص | Security & Licensing

* **نظام التفعيل المشفر**: حماية مفاتيح الترخيص باستخدام خوارزمية DJB2
* **معالج إعداد متقدم 5 خطوات** (`/onboarding`):
  1. تفعيل الترخيص
  2. اختيار القطاع
  3. الهوية البصرية
  4. إعداد الذكاء الاصطناعي
  5. قوالب البيانات الأولية

---

## 🛠️ تقنيات المشروع | Tech Stack

| التقنية | الاستخدام |
|--------|----------|
| React 18 | واجهة المستخدم |
| Vite 7 | البناء السريع |
| TypeScript | نوعية الكود |
| Tailwind CSS 4 | التنسيق |
| Firebase | قاعدة البيانات |
| Radix UI | مكونات الواجهة |
| Framer Motion | الحركات |

---

## 📁 هيكل المشروع | Project Structure

```bash
├── src/
│   ├── App.tsx              # الموجه الرئيسي
│   ├── index.css            # الأنماط العامة
│   ├── components/         # المكونات
│   │   ├── AIAdminAssistant.tsx
│   │   └── Layout.tsx
│   ├── lib/                 # المكتبات
│   │   ├── firebase.ts
│   │   └── activation.ts
│   ├── pages/               # الصفحات
│   │   ├── Landing.tsx
│   │   ├── Admin.tsx
│   │   └── MenuLightweight.tsx
│   └── contexts/            # سياقات React
├── public/                  # الملفات الثابتة
├── vite.config.ts           # إعدادات Vite
└── package.json             # التبعيات

---

## 🚀 البدء | Getting Started

```bash
# Install dependencies | تثبيت التبعيات
npm install

# Development mode | وضع التطوير
npm run dev

# Production build | البناء للإنتاج
npm run build

# Preview build | معاينة البناء
npm run serve
```

## 🌐 النشر | Deployment

| المنصة | الطريقة |
|-------|--------|
| GitHub Pages | Push to main - تلقائي |
| Cloudflare Pages | Upload dist folder |
| Netlify/Vercel | Upload dist folder |

---

<div align="center">

**DDS - تحويل البيانات الثابتة إلى تجارب ذكية**

⭐ **[Star](https://github.com/yk445kauod-coder/DDS/stargazers)** | 🍴 **[Fork](https://github.com/yk445kauod-coder/DDS/fork)**

</div>
