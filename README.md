# ملخصات مادة ضبط الجودة الإحصائي 📚

ملخصات منظّمة لمادة **Statistical Quality Control (1405-433)**، تغطّي **الصفحات (الشرائح) المحددة فقط** التي طلبتها الدكتورة — بدون حشو — مع **القوانين والأمثلة**.

> المرجع: Montgomery, *Statistical Quality Control*, 7th Edition (© John Wiley & Sons).

## 🌐 الموقع المنشور (قابل للمشاركة)

بعد اكتمال أول نشر عبر GitHub Pages سيكون الموقع متاحاً على:

**https://zayed1.github.io/summary-exam/**

> إن لم يفتح الرابط بعد، راجع قسم «تفعيل النشر» في الأسفل.

## 📑 الملخصات المتوفّرة (ملف منفصل لكل Chapter)

| الملف | الشرائح المطلوبة | HTML | PDF |
|-------|------------------|------|-----|
| **Chapter 1** — Quality Improvement | 4–7، 19، 32 | [chapter1.html](docs/chapter1.html) | [chapter1.pdf](docs/chapter1.pdf) |
| **Chapter 5** — Methods & Philosophy of SPC | 3–10، 21–25، 35–45 | [chapter5.html](docs/chapter5.html) | [chapter5.pdf](docs/chapter5.pdf) |
| **Chapter 7** — Control Charts for Attributes (English) | 7–14، 27–29، 31–37، 40–47، 52–67 | [chapter7.html](docs/chapter7.html) | [chapter7.pdf](docs/chapter7.pdf) |

## 📁 بنية المستودع

```
.
├── docs/                     ← الموقع المنشور (HTML + PDF)
│   ├── index.html            ← الصفحة الرئيسية
│   ├── chapter1.html / .pdf
│   ├── chapter5.html / .pdf
│   └── assets/               ← الثيم والخط العربي المضمّن
├── source-files/             ← ملفات المادة الأصلية (PDF)
└── README.md
```

## ✨ مميزات الملخصات

- **HTML + PDF** لكل فصل — للمذاكرة على الشاشة وللطباعة.
- تصميم عربي (RTL) واضح، يعمل على الجوال والكمبيوتر، **بدون إنترنت** (الخط مضمّن).
- المصطلحات بالإنجليزية كما في الامتحان، مع شرح بالعربية.
- القوانين في صناديق مميّزة + **ورقة قوانين (Cheat Sheet)** في Chapter 5.
- مرجع رقم الشريحة بجانب كل فكرة.

## 🚀 تفعيل النشر (GitHub Pages) — خطوة واحدة لمرة واحدة

النشر التلقائي لأول مرة لا يمكن تفعيله برمز Actions (قيد أمني في GitHub)، لذا يلزم تفعيله يدوياً مرة واحدة:

1. افتح **Settings → Pages**.
2. في **Build and deployment → Source** اختر **Deploy from a branch**.
3. اختر الفرع **`main`** والمجلد **`/docs`**، ثم **Save**.
4. خلال دقيقة سيظهر الموقع على الرابط أعلاه، وسيتحدّث تلقائياً مع كل تحديث لـ `main`.

---

### 📌 الحالة والفصول الأخرى
- **Chapter 1 و 5:** بالعربية حالياً، وسيتم تحويلهما إلى الإنجليزية.
- **Chapter 8 و 15:** الملفات موجودة في `source-files/` والشرائح محدّدة — جاهزة للتلخيص عند الطلب.
