# IPTV Player - مشغل القنوات

مشغل IPTV احترافي يدعم ملفات M3U مع واجهة عربية أنيقة.

## المميزات

- ✅ قراءة ملفات M3U من `assets/channels.m3u`
- ✅ دعم تدفقات HLS (.m3u8) و TS (.ts)
- ✅ واجهة عربية RTL احترافية
- ✅ تصنيف القنوات حسب المجموعات
- ✅ بحث فوري في القنوات
- ✅ تصميم متجاوب (جوال + كمبيوتر)
- ✅ اختصارات لوحة المفاتيح
- ✅ دعم الشاشة الكاملة
- ✅ إعادة المحاولة التلقائية

## هيكل المشروع

```
iptv-player/
├── index.html          ← الصفحة الرئيسية
├── css/
│   └── style.css       ← التنسيقات
├── js/
│   └── app.js          ← منطق التطبيق
├── assets/
│   └── channels.m3u    ← ملف القنوات
└── README.md
```

## طريقة الاستخدام

1. ضع ملف `channels.m3u` في مجلد `assets/`
2. افتح `index.html` في متصفح حديث
3. اختر قناة من القائمة

## صيغة ملف M3U

```m3u
#EXTM3U

#EXTINF:-1 tvg-id="ChannelID" tvg-logo="https://logo.png" group-title="المجموعة",اسم القناة
https://example.com/stream.m3u8

#EXTINF:-1 tvg-id="Channel2" group-title="رياضة",قناة رياضية
https://example.com/stream.ts
```

## اختصارات لوحة المفاتيح

| المفتاح | الوظيفة |
|---------|---------|
| ↑ | القناة السابقة |
| ↓ | القناة التالية |
| Space | تشغيل/إيقاف |
| F | شاشة كاملة |
| M | كتم الصوت |

## المتطلبات

- متصفح حديث (Chrome, Firefox, Edge, Safari)
- دعم JavaScript
- اتصال إنترنت للتدفقات المباشرة

## التقنيات

- HTML5 Video
- HLS.js
- Tailwind CSS
- Vanilla JavaScript

## الترخيص

مشروع مفتوح المصدر للاستخدام الشخصي.
