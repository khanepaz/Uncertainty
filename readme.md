# 📊 محاسبه‌گر عدم قطعیت پیشرفته  
**ابزار وب مبتنی بر استانداردهای بین‌المللی برای محاسبه دقیق عدم قطعیت اندازه‌گیری (Measurement Uncertainty)**

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/MathJS-0077CC?style=for-the-badge&logo=mathjs&logoColor=white" />
  <img src="https://img.shields.io/badge/KaTeX-30B32D?style=for-the-badge&logo=katex&logoColor=white" />
  <img src="https://img.shields.io/badge/XLSX.js-222222?style=for-the-badge&logo=excel&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=font-awesome&logoColor=white" />
  <img src="https://img.shields.io/badge/Open_Source-%F39C12?style=for-the-badge&logo=github&logoColor=white" />
</div>

---

## 🌟 توضیحات کلی

این ابزار یک **محاسبه‌گر عدم قطعیت اندازه‌گیری (Measurement Uncertainty Calculator)** کاملاً آفلاین و مبتنی بر وب است که با استفاده از **فرمول‌های ریاضی، مشتقات جزئی، و استانداردهای ISO/IEC Guide 98-3 (GUM)** طراحی شده است.

مناسب برای:
- آزمایشگاه‌های کالیبراسیون و تست
- مهندسان کنترل کیفیت و استاندارد
- تحقیقات علمی و آکادمیک
- آموزش مفاهیم عدم قطعیت

---

## 🚀 ویژگی‌های کلیدی

✅ **محاسبه خودکار عدم قطعیت ترکیبی و گسترده**  
✅ **پشتیبانی از فرمول‌های سفارشی و پارامترهای از پیش تعریف شده** (چگالی، تنش، مدول الاستیسیته و غیره)  
✅ **محاسبه مشتقات جزئی به صورت خودکار با `MathJS`**  
✅ **نمایش زیبا و حرفه‌ای معادلات با `KaTeX`**  
✅ **خروجی اکسل (Excel Export)** برای گزارش‌دهی رسمی  
✅ **رابط کاربری فارسی، واکنش‌گرا و کاربرمحور**  
✅ **بدون نیاز به سرور — کاملاً آفلاین و قابل اجرا با فایل محلی**  
✅ **پشتیبانی از منابع اضافی عدم قطعیت (دریفت، رزولوشن، کالیبراسیون و ...)**

---

## 🧩 پارامترهای پیش‌فرض

- 🔹 چگالی: `ρ = m / V`
- 🔹 تنش: `σ = F / A`
- 🔹 مدول الاستیسیته: `E = σ / ε`
- 🔹 پارامتر سفارشی: وارد کنید و فرمول خود را تعریف کنید!

---

## 📐 روش محاسبات

این ابزار از **روش GUM (Guide to the Expression of Uncertainty in Measurement)** پیروی می‌کند:

1. شناسایی منابع عدم قطعیت (تکرارپذیری، رزولوشن، کالیبراسیون، دریفت)
2. محاسبه عدم قطعیت استاندارد برای هر منبع
3. محاسبه مشتقات جزئی از فرمول
4. محاسبه عدم قطعیت ترکیبی:  
   \[
   u_c = \sqrt{\sum \left( \frac{\partial f}{\partial x_i} \right)^2 u_i^2}
   \]
5. محاسبه عدم قطعیت گسترده:  
   \[
   U = k \times u_c \quad (k=2)
   \]

---

## 💾 خروجی و اشتراک‌گذاری

- 📥 **خروجی اکسل** (XLSX) با تمام داده‌های تفصیلی
- 🖨️ **چاپ گزارش** با قالب تمیز و حرفه‌ای
- 🧮 **نمایش معادلات محاسباتی به صورت زیبا و قابل ویرایش**

---

## 🖼️ تصویر نمونه

   <img src="https://github.com/khanepaz/Uncertainty/blob/main/img/1.JPG" />
    <img src="https://github.com/khanepaz/Uncertainty/blob/main/img/2.JPG" />
    <img src="https://github.com/khanepaz/Uncertainty/blob/main/img/3.JPG" />
    <img src="https://github.com/khanepaz/Uncertainty/blob/main/img/4.JPG" />
    <img src="https://github.com/khanepaz/Uncertainty/blob/main/img/5.JPG" />



## 🔧 نحوه استفاده

1. فایل `index.html` را دانلود کنید.
2. آن را مستقیماً در مرورگر باز کنید (یا روی سرور قرار دهید).
3. مراحل زیر را دنبال کنید:
   - مرحله ۱: پارامتر اصلی را انتخاب کنید.
   - مرحله ۲: زیرپارامترها و داده‌های تست را وارد کنید.
   - مرحله ۳: منابع اضافی عدم قطعیت را اضافه کنید (اختیاری).
   - مرحله ۴: محاسبه کنید و نتایج را ببینید!

---

## 📦 فناوری‌های مورد استفاده

| فناوری | هدف |
|-------|------|
| `HTML5`, `CSS3`, `JavaScript` | ساختار و استایل اصلی |
| `MathJS` | تجزیه فرمول، محاسبه مشتق و ارزیابی ریاضی |
| `KaTeX` | نمایش زیبا و سریع معادلات ریاضی |
| `SheetJS (xlsx)` | ایجاد فایل اکسل بدون سرور |
| `Bootstrap 5` | طراحی واکنش‌گرا و تمیز |
| `Font Awesome` | آیکون‌های حرفه‌ای |

---

## 📄 مجوز

این پروژه تحت مجوز **MIT License** منتشر شده است.  
کاملاً **متن باز** و قابل استفاده در پروژه‌های شخصی و تجاری.

---

## 📬 بازخورد و همکاری

اگر باگ پیدا کردی، یا ایده‌ای برای بهبود داری، حتماً یک **Issue** باز کن یا یک **Pull Request** بفرست.

همچنین می‌تونی از طریق:
- ✉️ [ایمیل من] — (h.khanepaz@gmail.com)
- 💬 یا دیسکاشن‌های گیت‌هاب با من در ارتباط باشی.
- linkedin : https://www.linkedin.com/in/hamed-khanepaz-7876478a/

---

## 🙏 تشکر

از تو و همه کسانی که به بهبود این ابزار کمک می‌کنند، صمیمانه تشکر می‌کنم.  
هدف من ساخت یک ابزار **دقیق، کاربرمحور و استاندارد** برای جامعه علمی و صنعتی است.

---

> ✨ **توسعه دهنده**  
> — [حامد خانه پز ] | 2025
