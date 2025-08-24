# Shaheen Towers - Static Site
هذا المشروع يحتوي على ملف `index.html` فقط (صفحة ثابتة).
يستخدم Tailwind و Google Fonts و Font Awesome من CDN — لذلك لا يحتاج إلى أي بناء/باكدج.

## الرفع على GitHub Pages
1) أنشئ Repository عام على GitHub باسم `shaheen-towers` (أو أي اسم).
2) ارفع هذا الملف `index.html` كما هو (جذر الريبو).
3) من Settings → Pages:
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save
4) بعد دقيقة، سيظهر رابط الموقع بالشكل:
   `https://USERNAME.github.io/REPO-NAME/`

## تعديل/إضافة صور
- الصور الحالية روابط خارجية تعمل تلقائيًا.
- لو حبيت تضيف صورك:
  - ضعها داخل مجلد `assets/` واربطها مثل: `<img src="assets/my.jpg">`.
  - ارفع الصور مع الريبو على GitHub.
