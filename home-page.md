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
  <h2 style="color: #0066cc;">Dashboard</h2>

  <p>
    بعد تسجيل الدخول، أول صفحة ستظهر لك هي <strong>Dashboard</strong>، والتي تحتوي على:
  </p>

  <ul>
    <li>قائمة بجميع المشاريع التي قمت بإنشائها.</li>
    <li>زر <strong>"New Project"</strong> لإنشاء مشروع جديد.</li>
    <li>مربع بحث للوصول السريع إلى أي مشروع أو تطبيق.</li>
    <li>معلومات تُظهر عدد التطبيقات داخل كل مشروع.</li>
  </ul>

  <img src="image copy 2.png" alt="Dashboard Image">

  <div class="tip-box">
    <p>يمكنك استخدام مربع البحث للعثور بسرعة على أي مشروع أو تطبيق بكتابة اسمه.</p>
  </div>

  <div class="doc-nav">
    <a href="create_project.md">إنشاء مشروع جديد &rarr;</a>
    <a href="Ghaymah_Cloud.md">&larr; الصفحة الرئيسية</a>
  </div>
</div>


