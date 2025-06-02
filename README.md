
# Tesla Dashboard

لوحة بيانات تفاعلية مبنية باستخدام [Plotly Dash](https://dash.plotly.com/) و[Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/)، لعرض وتحليل بيانات السيارات.

---

## 📁 هيكل المشروع

```
plotly_dash/
│
├── components/
│   ├── layout.py          # تصميم الواجهة
│   └── callbacks.py       # الكول باكس للواجهة
│
├── data/
│   ├── cars_data.csv      # بيانات السيارات
│   └── data_loader.py     # تحميل البيانات ومعالجتها
│
├── app.py                 # الملف الرئيسي لتشغيل التطبيق
```

---

## 🚀 تشغيل المشروع

### 1. تثبيت المتطلبات

قم بتثبيت الحزم المطلوبة عن طريق:

```bash
pip install -r requirements.txt
```

> إذا لم يكن لديك ملف `requirements.txt` يمكنك إنشاؤه بالاعتماد على الحزم التالية:

```txt
dash
dash-bootstrap-components
pandas
```

### 2. تشغيل التطبيق

```bash
python app.py
```

ثم افتح المتصفح على:
```
http://127.0.0.1:8050
```

---

## 🧠 مميزات المشروع

- تصميم باستخدام Bootstrap لجعل الواجهة جذابة وسهلة الاستخدام.
- فصل الكود إلى ملفات: الواجهة، الكولباكس، وتحميل البيانات.
- إمكانية التوسع مستقبلًا بسهولة.
- مناسب لتحليل بيانات السيارات، خاصة المركبات الكهربائية مثل Tesla.

---

## 📌 ملاحظات

- تأكد من أن ملف `cars_data.csv` موجود في مجلد `data/`.
- يمكنك تعديل التصميم من `layout.py`، أو إضافة تفاعلات جديدة في `callbacks.py`.

---


## 👨‍💻 تم بواسطة

كريم فرحات – قناة مختصة بالبرمجة والأمن السيبراني 🚀  
[Telegram]((https://t.me/FarahatSchool)) | [GitHub](https://github.com/KareemOFarahat)

---

## 📜 الترخيص

MIT License
