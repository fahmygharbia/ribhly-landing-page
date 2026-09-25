# Ribhly — bilingual coming-soon landing page

A static Arabic/English landing page for **Ribhly**, designed for GitHub Pages. Arabic is the default language; visitors can switch to English. The choice is remembered locally in the browser.

## Publish with GitHub Pages

1. Create a **public** GitHub repository (or use an existing one).
2. Upload `index.html` and the `assets/` folder to the **root** of the branch you want to publish. Keep the folder structure intact.
3. Open **Settings → Pages** in your repository.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish and open the URL displayed in the Pages settings.

The page works without a build step, Node.js, paid hosting, external fonts, analytics, or external JavaScript libraries. You can preview it by opening `index.html` in a browser.

## Edit content

- Arabic copy is the text inside the HTML elements marked `data-i18n` and `data-i18n-html`.
- English copy is in the `en` object at the end of `index.html`.
- Replace `assets/ribhly-logo.webp` and `assets/favicon.png` when the final logo is ready.
- All dashboard numbers are **fictional illustrations**, not live results. Platform names are **planned integration targets**, not partnership or availability claims.

## نشر الصفحة بالعربي

ارفع ملف `index.html` ومجلد `assets` إلى جذر مستودع GitHub، ثم افتح **Settings → Pages** واختر **Deploy from a branch**، والفرع `main` والمجلد `/ (root)`، ثم احفظ الإعدادات. الصفحة لا تحتاج إلى Backend أو إعدادات بناء.
