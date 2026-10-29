[Uploading README.md…]()
# بافته‌های کرمان

فروشگاه آنلاین صنایع دستی کرمان. یک صفحه‌ی ساده (`index.html`) به‌همراه پوشه‌ی `images`.

## راه‌اندازی روی GitHub Pages
1. در github.com یک Repository جدید بسازید (مثلاً `kerman-crafts`) و روی Public بگذارید.
2. همه‌ی فایل‌ها و پوشه‌ی `images` را به آن آپلود کنید (Add file ← Upload files).
3. به Settings ← Pages بروید. در Source گزینه‌ی «Deploy from a branch»، شاخه‌ی `main` و پوشه‌ی `/ (root)` را انتخاب و Save کنید.
4. بعد از یکی دو دقیقه سایت در آدرس `https://USERNAME.github.io/kerman-crafts/` باز می‌شود.

## تنظیم تماس و دریافت سفارش
در ابتدای اسکریپت داخل `index.html`، خط `var CONFIG={wa:'',tg:'',insta:'',phone:''};` را پیدا کنید و پر کنید:
- `wa`: شماره واتس‌اپ با کد کشور و بدون صفر، مثل `989121234567`. با پر شدن آن، سفارش‌ها در واتس‌اپ شما باز می‌شوند.
- `tg` و `insta`: نام کاربری تلگرام و اینستاگرام.
- `phone`: شماره تماس برای نمایش در پایین صفحه.
