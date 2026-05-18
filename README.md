# 📺 Episodes Downloader Tool — دليل الاستخدام

> **أداة لتنزيل حلقات المسلسلات بشكل منظم وسريع**
> **A tool for downloading TV series episodes in an organized and fast way**

## ⚖️ إبراء ذمة شرعي وقانوني / Disclaimer

### 🌐 العربية

> **إبراء ذمة أمام الله:** تم تطوير هذا البرنامج كأداة برمجية لأغراض الأتمتة والتعلم والتعمق التقني فقط. وأنا **أبرأ إلى الله سبحانه وتعالى** من أي استخدام لهذه الأداة فيما يغضبه، أو في تحميل ومشاهدة المحرمات (كاللقطات الماجنة، الأفكار الهدامة، أو الموسيقى المحرمة)، أو أي محتوى لا يرضي الله عز وجل. 
>
> **ملاحظة قانونية هامة:** هذه الأداة هي مشروع مفتوح المصدر. المطور لا يتحمل أي مسؤولية (أخلاقية، شرعية، أو قانونية) عن كيفية استخدام الأفراد لهذا البرنامج، أو عن نوعية المحتوى (سواء كان محمياً بحقوق نشر أو غير لائق) الذي يختاره المستخدمون لتحميله ومشاهدته. الأداة وسيلة تقنية محايدة تماماً، وكل مستخدم مسؤول بالكامل عن إدخالاته، وعن توافق استخداماته مع الأحكام والشروط والقوانين المحلية، وهو المسؤول الأول والأخير عن صحيفة أعماله وما يختار تحميله بيده؛ فاتق الله ولا تجعل هذا الجهد حجة عليك يوم القيامة.

---

### 🌐 English

> **Islamic Disclaimer:** This tool was developed solely as a technical utility for automation and educational purposes. As a Muslim, **I completely disassociate myself before Allah (SWT)** from any misuse of this software to download or watch anything that is prohibited in Islam (Haram)—such as inappropriate scenes, forbidden music, or unlawful content. The tool is a neutral piece of code, and each user is fully responsible before Allah for what they choose to download and watch. Please fear Allah and use it responsibly.
>
> **Important Legal Note:** This tool is an open-source utility built strictly for technical, educational, and automation development purposes. The developer holds absolutely **zero responsibility** for how individuals choose to use this software, or for any copyrighted, restricted, or inappropriate content users may download and watch using it. Users are solely responsible for compliance with their local laws, copyright regulations, and the terms of service of any third-party platforms.
> 
---

## 🌐 English

### Requirements

- Operating System: **Windows**
- Nothing else — yt-dlp is bundled inside the program automatically
- Internet connection

---

### How to Run

1. Download `EpisodesDownloader.exe` — **that's it, no extra files needed**
2. Double-click to launch
3. Choose a mode from the main menu

---

### Main Menu

When you launch the program, you'll see three options:

```
[1] Manual Batch Download    — Manually specify any save path
[2] Download using SERIES folder on Desktop — Use a SERIES folder on your Desktop
[3] EXIT — Close the program
```

---

### Mode 1 — Manual Batch Download

Allows you to specify any folder on your computer to save episodes into.

**Steps:**

1. **Enter the save path** — Example: `C:\Users\Ahmed\Videos`
   - The path must already exist on your system
   - The program verifies the path before continuing

2. **Enter the series name** — Example: `Breaking Bad`
   - If the folder doesn't exist, the program will offer to create it
   - Special characters are not allowed: `\ / : * ? " < > |`

3. **Enter the episode number** — Format: `S00E00`, Example: `S01E05`
   - The program validates the format automatically
   - Valid examples: `S01E01`, `S02E13`, `S1E5`

4. **Enter the Referer URL** (optional) — Press Enter to skip
   - Required by some websites that validate the request source

5. **Enter the video URL** — Must start with `http://` or `https://`

6. The download starts automatically and saves as `S01E05.mp4`

---

### Mode 2 — SERIES Folder on Desktop

This mode works automatically with a folder named **SERIES** on your Desktop.

**Steps:**

1. If the `SERIES` folder doesn't exist, the program will offer to create it
2. **Choose a series from the list** — The program lists all folders inside `SERIES`
   - Enter the number of your series from the list
   - Or type `new` to create a new series folder
3. **Enter the episode number** — Format: `S00E00`
4. **Enter the Referer URL** (optional)
5. **Enter the video URL**
6. The episode is downloaded and saved inside the selected series folder

---

### Important Notes

- Type `back` at any step to return to the main menu
- Downloads use **10 concurrent fragments** for maximum speed
- Files are saved as `.mp4` by default
- All inputs are validated before the download begins

---

### Suggested Folder Structure

```
SERIES/
├── Breaking Bad/
│   ├── S01E01.mp4
│   ├── S01E02.mp4
│   └── S02E01.mp4
├── Game of Thrones/
│   ├── S01E01.mp4
│   └── S01E02.mp4
└── ...
```

---


## 🌐 اللغة العربية

### المتطلبات

- نظام تشغيل: **Windows**
- لا شيء آخر — yt-dlp مدمج داخل البرنامج تلقائياً
- اتصال بالإنترنت

---

### طريقة التشغيل

1. نزّل ملف `EpisodesDownloader.exe` — **هو كل شيء، لا توجد ملفات إضافية**
2. شغّله بالنقر المزدوج
3. اختر الوضع المناسب من القائمة الرئيسية

---

### القائمة الرئيسية

عند تشغيل البرنامج ستظهر لك ثلاثة خيارات:

```
[1] Manual Batch Download    — التنزيل اليدوي (تحدد المسار بنفسك)
[2] Download using SERIES folder on Desktop — التنزيل من مجلد SERIES على سطح المكتب
[3] EXIT — الخروج
```

---

### الوضع الأول — التنزيل اليدوي (Manual Batch Download)

يتيح لك هذا الوضع تحديد أي مسار على جهازك لحفظ الحلقات فيه.

**خطوات الاستخدام:**

1. **أدخل مسار الحفظ** — مثال: `C:\Users\Ahmed\Videos`
   - يجب أن يكون المسار موجوداً مسبقاً
   - البرنامج سيتحقق من وجوده تلقائياً

2. **أدخل اسم المسلسل** — مثال: `Breaking Bad`
   - إذا لم يكن المجلد موجوداً، سيعرض البرنامج إنشاءه تلقائياً
   - لا يمكن استخدام الأحرف الخاصة: `\ / : * ? " < > |`

3. **أدخل رقم الحلقة** — بالصيغة `S00E00`، مثال: `S01E05`
   - البرنامج يتحقق من صحة الصيغة تلقائياً
   - مثال صحيح: `S02E13`

4. **أدخل Referer URL** (اختياري) — اضغط Enter للتخطي
   - يُستخدم عند بعض المواقع التي تحتاج إلى مصدر الطلب

5. **أدخل رابط الفيديو** — يجب أن يبدأ بـ `http://` أو `https://`

6. سيبدأ التنزيل تلقائياً وتُحفظ الحلقة بالاسم المحدد (مثال: `S01E05.mp4`)

---

### الوضع الثاني — مجلد SERIES على سطح المكتب

هذا الوضع يعمل بشكل تلقائي مع مجلد اسمه **SERIES** على سطح المكتب.

**خطوات الاستخدام:**

1. إذا لم يكن مجلد `SERIES` موجوداً على سطح المكتب، سيعرض البرنامج إنشاءه
2. **اختر المسلسل من القائمة** — يعرض البرنامج كل المجلدات الموجودة داخل `SERIES`
   - اكتب رقم المسلسل من القائمة
   - أو اكتب `new` لإنشاء مجلد مسلسل جديد
3. **أدخل رقم الحلقة** — بالصيغة `S00E00`
4. **أدخل Referer URL** (اختياري)
5. **أدخل رابط الفيديو**
6. سيبدأ التنزيل وتُحفظ الحلقة داخل مجلد المسلسل المختار

---

### ملاحظات مهمة

- يمكنك كتابة `back` في أي خطوة للرجوع إلى القائمة الرئيسية
- التنزيل يستخدم **10 مقاطع متزامنة** لأقصى سرعة ممكنة
- الملفات تُحفظ بصيغة `.mp4` تلقائياً
- البرنامج يتحقق من صحة كل إدخال قبل المتابعة

---

### هيكل المجلدات المقترح

```
SERIES/
├── Breaking Bad/
│   ├── S01E01.mp4
│   ├── S01E02.mp4
│   └── S02E01.mp4
├── Game of Thrones/
│   ├── S01E01.mp4
│   └── S01E02.mp4
└── ...
```


*Powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp)*

---
---


