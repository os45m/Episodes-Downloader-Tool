# 📺 Episodes Downloader Tool

## Description in English

**Episodes Downloader Tool** is a Windows desktop utility that simplifies downloading TV series episodes from the internet and organizing them automatically on your machine.

### The Idea

The project grew out of a real frustration: when following multiple series and downloading episodes manually, the process becomes tedious — every time you need to open a downloader, set the path, name the file in the right format, and make sure it ends up in the right folder.

The goal was to build a tool that bundles all those steps into one simple interactive interface, validates every input, and organizes files automatically using the standard `S01E05.mp4` naming convention.

### What Makes This Tool Stand Out

- **Interactive text interface** — no technical knowledge required
- **Two operating modes** — flexible manual mode, or automatic mode via a SERIES folder on the Desktop
- **Smart input validation** — rejects wrong paths and malformed episode numbers before any download starts
- **Standardized file naming** — automatically saves episodes as `S00E00.mp4`
- **Fast downloads** — uses 10 concurrent fragments via yt-dlp
- **Referer URL support** — handles websites that require a request source header
- **Auto folder creation** — if the series folder doesn't exist, the tool offers to create it on the spot

### Technologies Used

- **Windows Batch Script (.bat)** — the core engine of the program
- **yt-dlp** — the powerful downloader that supports hundreds of websites
- **iexpress** — a built-in Windows tool used to bundle the `.bat` script together with `yt-dlp.exe` into a single self-contained `.exe`, so the user just downloads one file and runs it immediately — no setup needed

### Project Structure

```
EpisodesDownloader/
├── EpisodesDownloader.exe   ← Full program (yt-dlp bundled inside)
├── README.md                ← Usage guide
└── DESCRIPTION.md           ← This file
```

## الوصف بالعربية

**Episodes Downloader Tool** هي أداة سطح مكتب مصممة لـ Windows، تُسهّل تنزيل حلقات المسلسلات من الإنترنت وتنظيمها تلقائياً على جهازك.

### الفكرة

فكرة المشروع نشأت من حاجة عملية: عند متابعة مسلسلات متعددة وتنزيل حلقاتها يدوياً، تصبح العملية متعبة — تحتاج كل مرة إلى فتح أداة التنزيل، تحديد المسار، تسمية الملف بالصيغة الصحيحة، ثم التأكد من وضعه في المجلد الصحيح.

الهدف كان بناء أداة تجمع كل هذه الخطوات في واجهة واحدة بسيطة، تتحقق من المدخلات، وتنظم الملفات تلقائياً بصيغة معيارية مثل `S01E05.mp4`.

### ما يميز هذه الأداة

- **واجهة نصية تفاعلية** — لا تحتاج لأي خبرة تقنية
- **وضعان للعمل** — يدوي مرن، أو تلقائي عبر مجلد SERIES على سطح المكتب
- **تحقق ذكي من المدخلات** — يرفض المسارات الخاطئة وأسماء الحلقات غير الصحيحة قبل التنزيل
- **تسمية موحدة للملفات** — يحفظ الحلقات بصيغة `S00E00.mp4` تلقائياً
- **تنزيل سريع** — يستخدم 10 مقاطع متزامنة عبر yt-dlp
- **دعم Referer URL** — للتعامل مع المواقع التي تتطلب مصدر الطلب
- **إنشاء المجلدات تلقائياً** — إذا لم يكن مجلد المسلسل موجوداً، تقترح الأداة إنشاءه

### التقنيات المستخدمة

- **Windows Batch Script (.bat)** — النواة الأساسية للبرنامج
- **yt-dlp** — محرك التنزيل القوي الذي يدعم مئات المواقع
- **iexpress** — أداة Windows مدمجة استُخدمت لدمج ملف الـ bat مع yt-dlp.exe في ملف `.exe` واحد، بحيث لا يحتاج المستخدم لتنزيل أي شيء إضافي — يشغّل البرنامج مباشرة

### بنية المشروع

```
EpisodesDownloader/
├── EpisodesDownloader.exe   ← البرنامج الكامل (يحتوي على yt-dlp بداخله)
├── README.md                ← دليل الاستخدام
└── DESCRIPTION.md           ← هذا الملف
```

---

### License

This project is open-source. Feel free to use, modify, and share it.
yt-dlp is a separate open-source project — see its [GitHub page](https://github.com/yt-dlp/yt-dlp) for its own license terms.
