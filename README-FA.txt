NEON RPG - ساخت APK ابری فقط با گوشی اندروید

این بسته برای ساخت APK با GitHub Actions آماده شده است. برای شروع:
1) در گوشی وارد https://github.com شوید و حساب بسازید/وارد شوید.
2) از منوی + گزینه New repository را بزنید.
3) نام مخزن را neon-rpg-android بگذارید و Public یا Private را انتخاب کنید؛ Create repository.
4) فایل ZIP را از حالت فشرده خارج کنید. در صفحه مخزن Add file > Upload files را بزنید.
5) همه محتویات پوشه neon-cloud-apk را آپلود کنید؛ توجه کنید پوشه .github هم باید آپلود شود. اگر آپلود موبایل پوشه مخفی را نشان نداد، در مرورگر حالت Desktop site را فعال کنید.
6) Commit changes را بزنید.
7) وارد تب Actions شوید، workflow با نام Build NEON RPG APK را انتخاب کنید، Run workflow را بزنید.
8) پس از پایان موفق، پایین صفحه اجرای workflow در بخش Artifacts فایل NEON-RPG-APK را دانلود کنید.
9) ZIP دانلودی را باز کنید و app-debug.apk را نصب کنید. ممکن است اندروید اجازه نصب از منبع مرورگر/فایل‌منیجر را بخواهد.

مهم:
- این خروجی نسخه آزمایشی Debug است و برای انتشار عمومی در Play Store امضای Release لازم دارد.
- این APK فعلاً رابط بازی و تصاویر را در خود دارد. چت AI به backend آنلاین نیاز دارد؛ API key را داخل APK یا فایل‌های وب قرار ندهید. سرور server.js نسخه اصلی باید روی میزبانی امن Deploy شود و آدرس API به کلاینت تنظیم شود.
- هیچ API key را در GitHub یا داخل ZIP قرار ندهید.
