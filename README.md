# 🎓 Senior 2027 Study Plan Dashboard (Class of 2027)
### خطة المذاكرة التفاعلية للثانوية العامة 2026 - 2027

An interactive, responsive, and mobile-optimized study plan dashboard designed for Senior 2027 students. Fully offline-capable, bilingual, and equipped with progress tracking and material inspection.

---

## 🌟 Key Features / المميزات الرئيسية

- **Dual Views (طريقتان للعرض):**
  - **Timeline View (الجدول الزمني):** Week-by-week organized study schedule with visual weekly separators.
  - **Subject Syllabus (فهرس المواد):** Detailed curriculum breakdown per subject with lesson timing and progress bars.
- **Bilingual Interface (عربي / English):** One-click toggle between full Arabic and English UI.
- **Instant Drive Material Linking (ربط مباشر بملفات الدرايف):** Click on any lesson name to view its exact source files, videos, assignments, and PDFs from Google Drive.
- **Multi-layer Progress Saving (حفظ دائم للتقدم):**
  - Persistent `localStorage` tracking.
  - URL Hash backup state (`#done=...`) preventing data loss in restrictive mobile viewers.
  - JSON Import & Export for instant copy-paste synchronization across phone, tablet, and PC.
- **Mobile-First Touch Optimization (محسّن للشاشات الذكية):**
  - 48px responsive touch targets for instant checkbox feedback (`touch-action: manipulation`).
  - Zero-JS CSS fallback modals for maximum compatibility with all mobile browsers.
  - Clean monochrome vector SVG icons (no distracting emojis).
- **Print & PDF Export:** Clean CSS `@media print` styling for high-resolution A4 study roadmaps.

---

## 🚀 Live Demo / الاستخدام المباشر

Once GitHub Pages is activated, this study plan is live at:
👉 **[https://ahmed-elmalah.github.io/study-plan/](https://ahmed-elmalah.github.io/study-plan/)**

---

## 📱 Mobile Setup / الاستخدام على الهاتف

1. Open the GitHub Pages link in **Chrome** or **Safari** on your phone.
2. Tap the browser menu (`⋮` on Chrome or `Share` on Safari) and select **"Add to Home screen"** (**إضافة إلى الشاشة الرئيسية**).
3. It will behave as a standalone web app with full touch support and permanent progress memory.

---

## 🔄 Sync Progress Between Phone & PC / مزامنة اللاب توب والموبايل

1. Click **Export (تصدير)** on your device to copy your progress JSON code or URL.
2. Open the page on your other device, click **Import (استيراد)**, paste the code, and click **Load**.
3. All your completed lessons and progress stats will sync instantly!
