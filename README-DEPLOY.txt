# آریاستایل — نسخه بازبینی‌شده برای GitHub Pages

## انتشار روی GitHub Pages
1. فایل ZIP را استخراج کنید.
2. تمام محتویات پوشه را مستقیماً در ریشه مخزن GitHub قرار دهید؛ فایل `index.html` باید در ریشه مخزن باشد.
3. در GitHub وارد `Settings → Pages` شوید.
4. در بخش `Build and deployment`، گزینه `Deploy from a branch` را انتخاب کنید.
5. شاخه `main` و پوشه `/ (root)` را انتخاب و ذخیره کنید.
6. پس از پایان انتشار، آدرس GitHub Pages را باز کنید و صفحات، منو، جستجو، سبد خرید و علاقه‌مندی‌ها را بررسی کنید.

فایل `.nojekyll` برای جلوگیری از پردازش Jekyll در مخزن قرار دارد. فایل `.htaccess` مخصوص Apache است و GitHub Pages آن را اجرا نمی‌کند؛ وجود آن در مخزن مشکلی ایجاد نمی‌کند اما روی GitHub Pages اثری ندارد.

## آنچه در این بسته وجود دارد
- ۷۶ صفحه HTML
- فایل‌های CSS و JavaScript مشترک
- تصاویر و آیکون‌های محلی
- صفحات دسته‌بندی، جزئیات محصول، جستجو، سبد خرید/تکمیل خرید و صفحات راهنما
- سبد خرید و علاقه‌مندی‌ها با `localStorage`
- طراحی واکنش‌گرا و منوی موبایل

## محدودیت‌های فعلی
این پروژه فعلاً فرانت‌اند استاتیک است. ورود و ثبت‌نام واقعی، دیتابیس، موجودی و قیمت قطعی، ثبت سفارش، پنل مدیریت، پیامک/ایمیل و پرداخت هنوز به بک‌اند متصل نیستند. اطلاعات سبد خرید فقط در مرورگر کاربر ذخیره می‌شود و سفارش واقعی ثبت نمی‌کند.

## پیش از انتشار عمومی
- نقشه سایت تا زمان مشخص شدن آدرس واقعی GitHub Pages عمداً ایجاد نشده است. پس از انتشار، `sitemap.xml` را با URL واقعی بسازید و نشانی آن را در `robots.txt` ثبت کنید.
- قیمت‌ها و تصاویر فعلی نمونه‌اند؛ قبل از فروش واقعی باید با داده‌های نهایی جایگزین شوند.
- قوانین ارسال، مرجوعی، حریم خصوصی و شرایط فروش باید با سیاست واقعی فروشگاه هماهنگ شوند.
- کلیدهای محرمانه و اطلاعات اتصال بک‌اند را هرگز در فایل‌های فرانت‌اند قرار ندهید.

## نقشه راه بک‌اند
فایل `BACKEND-ROADMAP-FA.txt` را برای مراحل پیشنهادی اتصال بک‌اند ببینید.

IMAGE REFRESH (November 2026)
- Updated assets/ariastyle-hero.jpg with a new wide fashion hero image.
- Standardized assets/products/product-01.jpg through product-12.jpg to a consistent 600x700 studio-card format and harmonized their backgrounds.
- Existing asset filenames and relative paths were preserved, so page references do not need to change.
- Before accepting real customer orders, replace demo/sample product photos with photographs that accurately represent the actual products and are authorized for commercial use.
