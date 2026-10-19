# Trend Maker

معرض إلكتروني + طلب عبر واتساب بكود المنتج + لوحة تحكم.

## النشر
1. أنشئ ريبو على GitHub وارفع كل الملفات (أو `git init && git add . && git commit -m init && git push`).
2. Settings → Pages → Source: Deploy from a branch → `main` / root.
3. المتجر: `https://USERNAME.github.io/REPO/` — لوحة التحكم: `.../admin.html`

## لوحة التحكم
1. GitHub → Settings → Developer settings → Fine-grained tokens → اختر الريبو فقط، صلاحية **Contents: Read and write**.
2. افتح `admin.html`، أدخل `USERNAME/REPO` والتوكن ورقم واتساب، واضغط حفظ.
3. أضف المنتجات؛ كل حفظ يعمل commit تلقائي والموقع يتحدث خلال دقيقة.

التوكن يتخزن في متصفحك فقط. لا تشاركه مع أحد.
