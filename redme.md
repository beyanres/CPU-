# 🖥️ نظم التشغيل 2 - العملي

<p align="center">
  <img src="https://img.shields.io/badge/University-Mari%20Private%20University-blue?style=for-the-badge" alt="University">
  <img src="https://img.shields.io/badge/Course-OS2%20Practical-cyan?style=for-the-badge" alt="Course">
  <img src="https://img.shields.io/badge/Supervisor-Dr.%20Hassan%20Hegar-purple?style=for-the-badge" alt="Supervisor">
</p>

<p align="center">
  <strong>منصة تعليمية تفاعلية لمادة نظم التشغيل 2 العملي</strong><br>
  <em>Built by: Dr. Hassan Hegar - Mari Private University</em>
</p>

---

## 🎓 معلومات المشروع

| المعلومة | التفاصيل |
|----------|----------|
| **المشرف** | د. حسن حجار |
| **الجامعة** | جامعة ماري الخاصة |
| **المادة** | نظم التشغيل 2 - العملي |
| **القسم** | Smart Traffic AI - Deadlock Prevention |
| **التقنيات** | HTML5, CSS3, JavaScript (Pure) |
| **اللغة** | العربية (RTL) |
| **الوضع** | Dark / Light Mode |

---

## 📋 المحتوى

### 📖 المفاهيم النظرية (6)

| # | المفهوم | الوصف |
|---|---------|-------|
| 1 | 📝 التنفيذ المتسلسل | Sequential Execution - تنفيذ المهام واحدة تلو الأخرى |
| 2 | 🔀 الخيوط (Threads) | وحدات تنفيذ خفيفة ضمن نفس العملية |
| 3 | ⚠️ Race Condition | حالة السباق - تنافس Threads على نفس المورد |
| 4 | 🔒 Mutex Lock | قفل التزامن - منع دخول أكثر من Thread |
| 5 | 🛑 Deadlock | الجمود - الانتظار الدائري بين العمليات |
| 6 | 📊 لوحة المراقبة | Dashboard شاملة مع رسوم بيانية |

### 🛠️ المشاريع العملية (7)

| # | المشروع | الوصف | التقنية |
|---|---------|-------|---------|
| 1 | 🧮 **CPU Scheduler** | FCFS, SJF, Round Robin مع مخطط Gantt | Scheduling Algorithms |
| 2 | 🏧 **ATM Machine** | محاكاة ATM مع Mutex Lock للرصيد | Mutex |
| 3 | 🚂 **Railway Crossing** | مزلقان سكة حديد مع Mutex للحاجز | Mutex |
| 4 | 🚗 **Smart Traffic AI** | تقاطع طرق ذكي لمنع Gridlock | **Deadlock Prevention** |
| 5 | 🚁 **Drone Coordination** | تنسيق طائرات بدون طيار مع Mutex | Mutex |
| 6 | 🎮 **Game Server** | خادم لعبة متعدد اللاعبين مع Mutex Scoreboard | Mutex |
| 7 | 🖨️ **Printer Manager** | 3 طابعات و 6 مستخدمين باستخدام Semaphore | Semaphore |

---

## 🚀 التشغيل

### ⭐ الطريقة 1: الموقع المباشر (GitHub Pages)

🔗 **[اضغط هنا لفتح المشروع](https://YOUR_USERNAME.github.io/os2-practical/)**

> استبدل `YOUR_USERNAME` باسم مستخدم GitHub الخاص بك

### 💻 الطريقة 2: محلياً (Python Server)

```bash
# تحميل المستودع
git clone https://github.com/YOUR_USERNAME/os2-practical.git
cd os2-practical

# تشغيل السيرفر المحلي
python "نظم_التشغيل(18).py"

# فتح المتصفح على
# http://localhost:8788
```

### 🌐 الطريقة 3: فتح مباشر

افتح الملف `index.html` مباشرة في أي متصفح حديث.

---

## 📂 هيكل المشروع

```
os2-practical/
├── 📄 index.html              ← الموقع التفاعلي (الرئيسي)
├── 🐍 نظم_التشغيل(18).py      ← السيرفر المحلي + HTML مدمج
├── 📖 README.md               ← هذا الملف
├── 🚫 .gitignore              ← ملفات مستبعدة
└── 🖼️ images/                 ← صور توضيحية
    ├── traffic-ai.png
    ├── deadlock-hold-wait.png
    └── deadlock-cycle.png
```

---

## ✨ المميزات

- ✅ **واجهة عربية** بالكامل مع دعم RTL
- ✅ **Dark / Light Mode** للراحة البصرية
- ✅ **13 قسم** تعليمي تفاعلي
- ✅ **محاكاة حية** لكل المفاهيم
- ✅ **مخطط Gantt** تفاعلي لـ CPU Scheduler
- ✅ **Responsive Design** يعمل على الجوال والتابلت
- ✅ **بدون مكتبات خارجية** - Pure HTML/CSS/JS
- ✅ **صفحة غلاف احترافية** (Landing Page)

---

## 📸 لقطات شاشة

### 🏠 صفحة الغلاف
> صفحة غلاف احترافية تعرض إحصائيات المشروع والأقسام الرئيسية

### 🚗 Smart Traffic AI
> محاكاة تقاطع طرق ذكي لمنع Gridlock باستخدام Traffic Lights + Prioritization

### 🛑 Deadlock Prevention
> عرض شروط Coffman الأربعة مع محاكاة تفاعلية

---

## 🎓 المفاهيم المغطاة

### 🔒 Synchronization
- Mutex Lock
- Semaphore
- Critical Section

### ⚠️ Concurrency Issues
- Race Condition
- Deadlock (شروط Coffman)
- Starvation

### 🧮 Scheduling
- FCFS (First Come First Serve)
- SJF (Shortest Job First)
- Round Robin

---

## 📧 التواصل

<p align="center">
  <strong>جامعة ماري الخاصة</strong><br>
  <em>قسم نظم التشغيل 2 - العملي</em><br>
  <strong>المشرف: د. حسن حجار</strong>
</p>

---

<p align="center">
  Built with  for Education | OS2 Practical Project
</p>
