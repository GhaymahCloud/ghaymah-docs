<!-- Include styles -->
<style>
/* Ghaymah Documentation Unified Styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: #333;

  margin: 0 auto;
  padding: 20px;
}

/* Header Styles */
h1, h2, h3, h4, h5, h6 {
  color: #0066cc;
  margin-top: 1.5em;
  margin-bottom: 0.5em;
  font-weight: 600;
}

h1 { font-size: 2.2em; border-bottom: 2px solid #eaecef; padding-bottom: 0.3em; }
h2 { font-size: 1.8em; border-bottom: 1px solid #eaecef; padding-bottom: 0.3em; }
h3 { font-size: 1.5em; }
h4 { font-size: 1.25em; }

/* Text and Paragraph Styles */
p {
  margin: 1em 0;
  line-height: 1.8;
}

strong {
  font-weight: 600;
  color: #0066cc;
}

/* List Styles */
ul, ol {
  padding-right: 2em;
  margin-top: 1em;
  margin-bottom: 1em;
}

ul li, ol li {
  margin-bottom: 0.5em;
  line-height: 1.6;
}

/* Image Styles */
img {
  max-width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  margin: 1.5em 0;
  display: block;
  margin-left: auto;
  margin-right: auto;
}

/* Special Content Blocks */
.info-box, .warning-box, .tip-box {
  padding: 15px;
  margin: 20px 0;
  border-radius: 5px;
  position: relative;
  padding-right: 50px;
}

.info-box {
  background-color: #e8f4fd;
  border-right: 4px solid #0066cc;
}

.warning-box {
  background-color: #fff8e6;
  border-right: 4px solid #f0ad4e;
}

.tip-box {
  background-color: #e6f9e6;
  border-right: 4px solid #5cb85c;
}

/* Code and Pre Blocks */
code {
  font-family: Consolas, Monaco, 'Andale Mono', monospace;
  background-color: #f6f8fa;
  padding: 0.2em 0.4em;
  border-radius: 3px;
  font-size: 0.9em;
}

pre {
  background-color: #f6f8fa;
  border-radius: 5px;
  padding: 16px;
  overflow: auto;
  font-size: 0.9em;
  line-height: 1.45;
}

/* RTL Specific Adjustments */
[dir="rtl"] {
  text-align: right;
}

/* Container for the entire document */
.doc-container {
  background-color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  padding: 30px;
  margin-bottom: 30px;
}

/* Navigation elements */
.doc-nav {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
  padding-top: 20px;
  border-top: 1px solid #eaecef;
}

.doc-nav a {
  text-decoration: none;
  color: #0066cc;
  display: inline-flex;
  align-items: center;
}

/* Responsive design adjustments */
@media (max-width: 768px) {
  body {
    padding: 15px;
  }

  .doc-container {
    padding: 20px;
  }

  h1 { font-size: 1.8em; }
  h2 { font-size: 1.5em; }
  h3 { font-size: 1.3em; }
}

/* Print-friendly styles */
@media print {
  body {
    font-size: 12pt;
  }

  img {
    max-width: 100% !important;
    page-break-inside: avoid;
  }

  h1, h2, h3, h4, h5, h6 {
    page-break-after: avoid;
  }

  ul, ol {
    page-break-inside: avoid;
  }
}
</style>

<div class="doc-container" dir="rtl">
  <h2 style="color: #0066cc;">إنشاء تطبيق جديد</h2>

  <p>
    بعد إنشاء مشروع في Ghaymah Cloud، يمكنك إضافة تطبيقات إليه. كل تطبيق هو عبارة عن خدمة منفصلة يمكن نشرها وإدارتها بشكل مستقل.
  </p>

  <div class="info-box">
    <p>يمكنك إنشاء عدة تطبيقات داخل المشروع الواحد، مما يساعدك على تنظيم خدماتك المختلفة وإدارتها بكفاءة.</p>
  </div>

  <h3>خطوات إنشاء تطبيق جديد:</h3>

  <ol>
    <li>انتقل إلى المشروع الذي ترغب بإضافة التطبيق إليه.</li>
    <li>انقر على زر <strong>"New App"</strong>.</li>
    <li>أدخل اسم التطبيق.</li>
    <li>اختر نوع التطبيق أو الخدمة التي ستقوم بنشرها.</li>
    <li>قم بتكوين إعدادات التطبيق حسب احتياجاتك.</li>
    <li>انقر على <strong>"Create"</strong> لإنشاء التطبيق.</li>
  </ol>

  <img src="image copy 9.png" alt="إنشاء تطبيق جديد" style="border: 1px solid #eaecef;">

  <div class="warning-box">
    <p>تأكد من اختيار اسم مميز للتطبيق يعكس وظيفته، وذلك لتسهيل التمييز بينه وبين التطبيقات الأخرى في المشروع.</p>
  </div>

  <div class="tip-box">
    <p>يمكنك دائمًا تعديل إعدادات التطبيق لاحقًا من خلال صفحة إعدادات التطبيق.</p>
  </div>

  <div class="doc-nav">
    <a href="gen.md">إعدادات النشر &rarr;</a>
    <a href="theme.md">&larr; إعدادات العرض</a>
  </div>
</div>

<div dir="rtl">

# كيفية إضافة Application إلى مشروع

يهدف هذا الدليل إلى توضيح كافة الخطوات التي تحتاجها لإضافة تطبيق جديد ضمن مشروع على منصة استضافة سحابية، وذلك بدءًا من اختيار المصدر (Source) وحتى تشغيل التطبيق وربط النطاق.

---

## اختيار مصدر التطبيق (Source Type)

عند إنشاء تطبيق جديد، سيُطلب منك تحديد مصدر الكود الذي سيُبنى عليه التطبيق. الخيارات المتاحة هي:

### Container Image

#### ما هو Container Image؟

هو "صورة جاهزة" تحتوي على:

- كود التطبيق
- المكتبات الضرورية (Dependencies)
- إعدادات التشغيل
- نسخة مصغّرة من نظام التشغيل

> تُشغَّل باستخدام نظام الحاويات (Containers) مثل Docker.

#### من أين أحصل عليه؟

- من [Docker Hub](https://hub.docker.com)
- أو من مستودع خاص مثل GitHub Container Registry

#### مثال:

![image copy.png](<image copy 15.png>)

---

### Git Repository

#### ما هو Git Repository؟

هو مستودع كود يحتوي على ملفات المشروع، ويكون مستضافًا على منصات مثل:

- GitHub
- GitLab
- Bitbucket

#### ما الذي تحتاجه؟

- إدخال رابط المستودع (Repository URL)
- إضافة مفتاح API أو Token إذا كان المستودع خاصًا

![image copy.png](<image copy 14.png>)

---

## إعدادات المنفذ (Port Settings)

### ما هو الـ Port؟

المنفذ هو رقم يُستخدم لتحديد "الباب" الذي يستقبل التطبيق من خلاله الاتصالات الشبكية.

### أمثلة شائعة:

| المنفذ | الاستخدام الشائع                 |
|--------|----------------------------------|
| 80     | HTTP (المواقع العادية)           |
| 443    | HTTPS (المواقع المؤمنة)          |
| 3000   | تطبيقات React/Node.js            |
| 5000   | تطبيقات Python مثل Flask         |
| 3306   | MySQL Database                   |


---
## تفعيل الإتاحة العامة (Public Access)

### Public Access

- عند تفعيل هذا الخيار، يصبح التطبيق متاحًا على الإنترنت.
- عند تعطيله، يبقى ضمن الشبكة الداخلية للبنية التحتية فقط.

### متى يُفعَّل؟

- يتم تفعيله عند نشر تطبيق يحتاج الوصول العام مثل مواقع الويب أو الواجهات البرمجية (APIs).
- لا يُفعَّل إذا كان التطبيق لا يحتاج وصول خارجي أثناء التطوير أو لأسباب أمنية.

![image copy.png](<image copy 16.png>)

---

## الإعدادات المتقدمة (Advanced Settings)

### Domain Settings

#### Use Custom Domain

بشكل افتراضي، يتم إنشاء نطاق تلقائي لتطبيقك (Auto-generated Domain).
لربط نطاقك الخاص مثل `myapp.com`، يجب تفعيل هذا الخيار.

---

### كيفية ربط النطاق بـ DNS الخاص بالمنصة

#### 1. الحصول على بيانات الربط:

- توفر المنصة رابطًا من نوع CNAME أو عنوان IP.

#### 2. الدخول إلى لوحة التحكم الخاصة بمزود النطاق (مثل GoDaddy أو Namecheap):

قم بإضافة سجل جديد في DNS:

| النوع     | الاسم         | القيمة                        |
|----------|---------------|-------------------------------|
| CNAME    | www أو @      | `app-name.platform.io`        |
| A Record | @             | عنوان IP إذا تم توفيره        |

> ملاحظة: قد تستغرق التغييرات بعض الوقت لتفعيلها (من دقائق حتى 24 ساعة).



---
### Environment Variables

#### ما هي المتغيرات البيئية؟

هي إعدادات خارجية يتم تمريرها إلى التطبيق لضبط سلوكه دون تعديل الكود مباشرة.

### أهم استخداماتها:

- حفظ المعلومات الحساسة (مثل API Keys)
- تحديد بيئة التشغيل (development أو production)
- تغيير الإعدادات دون الحاجة إلى إعادة نشر التطبيق

### أمثلة:

| Key              | Value                                | الغرض                         |
|------------------|--------------------------------------|-------------------------------|
| `API_KEY`         | `sk-abc123xyz`                       | مفتاح خدمة خارجية             |
| `DEBUG`           | `true` أو `false`                    | تفعيل أو تعطيل وضع التصحيح   |
| `DATABASE_URL`    | `mysql://user:pass@host/db`          | رابط قاعدة البيانات           |
| `ENVIRONMENT`     | `development` أو `production`        | تحديد بيئة التشغيل            |

![image copy.png](<image copy 21.png>)

---

## نشر التطبيق (Deploy)

بعد الانتهاء من جميع الإعدادات:

1. اضغط على زر "Deploy".
2. انتظر انتهاء مرحلة البناء.
3. سيتم تشغيل التطبيق تلقائيًا.
4. سيتم عرض رابط الوصول للتطبيق (حسب إعداد Public Access).

### مشاهدة سجلات التطبيق (Application Logs)

قبل نشر التطبيق بنجاح، يمكنك التحقق من سجلات التطبيق (Logs) للحصول على تفاصيل حول الحالة الحالية. في حال تم تفعيل خاصية البث المباشر، يمكنك متابعة السجلات الحية من خلال هذا المثال:
![image copy.png](<image copy 20.png>)




---

### نشر التطبيق بنجاح

بعد التحقق من السجلات، اضغط على زر "Deploy" مرة أخرى لإتمام نشر التطبيق بنجاح. سيتم تشغيل التطبيق تلقائيًا، ويمكنك الوصول إليه عبر الرابط المتاح بناءً على إعداد Public Access.

![image copy.png](<image copy 19.png>)

---

## نصائح عامة

- تأكد من اختبار التطبيق محليًا قبل نشره.
- راجع الوثائق الخاصة بـ Docker Image أو المستودع لتحديد المتطلبات.
- تحقق من صحة المتغيرات البيئية.
- استخدم سجلات التشغيل (Logs) لتشخيص المشاكل المحتملة.

</div>
