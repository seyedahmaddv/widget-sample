# ویجت‌های تعاملی مسابقه‌ای

این پروژه شامل مجموعه‌ای از ویجت‌های تعاملی برای مسابقات و کمپین‌های آنلاین است. ویجت‌ها شامل گردونه شانس، کوئیز تعاملی، کد تخفیف، نظرسنجی، لیدربورد و بازی کلیک سریع هستند که همگی در یک صفحه HTML پیاده‌سازی شده‌اند.

## مشاهده دمو آنلاین

[https://widget-sample-101.netlify.app/](https://widget-sample-101.netlify.app/)

## امکانات

- 🎡 گردونه شانس با انیمیشن و نمایش جایزه تصادفی
- 🧠 کوئیز تعاملی با نمایش پاسخ صحیح
- 🎫 کد تخفیف با قابلیت کپی سریع
- 📊 نظرسنجی لحظه‌ای با نمایش درصد آرا
- 🏆 جدول امتیازات (لیدربورد)
- 🎮 بازی کلیک سریع با شمارش امتیاز در مدت زمان محدود

## نحوه استفاده

کافیست فایل `index.html` را در مرورگر خود باز کنید یا آن را روی هاست دلخواه خود قرار دهید.

## نمونه کد نصب ویجت روی سایت

```html
<script>
(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "https://yoursite.com/widget.js";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'campaign-widget'));
</script>
```

## ارتباط با من

<a href="https://www.linkedin.com/in/seyedahmaddv" target="_blank">لینکدین من</a>  


---

این پروژه صرفاً جهت نمونه طراحی شده است.