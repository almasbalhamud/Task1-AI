# Task1-AI
مشروع لتصنيف الأشكال الهندسية باستخدام نموذج مدرب عبر Teachable Machine. 
يحتوي المستودع على ملفات النموذج، وملف التصنيفات، وكود بايثون لتجربة التنبؤ .
# 🟢 مشروع تصنيف الأشكال الهندسية

مشروع بسيط لتصنيف الأشكال الهندسية (مثل الدائرة، المربع، المثلث) باستخدام نموذج مدرّب عبر **Teachable Machine** وكود بايثون للتجربة.

---

## 🗂️ محتويات المستودع

- `keras_model.h5` 👉 ملف النموذج المدرب.
- `labels.txt` 👉 ملف الفئات (التصنيفات).
- `predict_script.py` 👉 سكربت بايثون لتجربة التنبؤ.



## تجربة النموذج
قمت بتجربة النموذج باستخدام صورة الاختبار المرفقة






![Circle test](https://github.com/user-attachments/assets/8534f763-0d95-44e8-8d2c-1e07ba17cc04)


وعند تشغيل السكربت على هذه الصورة، كان الإخراج كالتالي:




![screenshot png](https://github.com/user-attachments/assets/6b332322-6641-43b5-a4b9-1762ca6ae291)
هذا يدل على أن النموذج تمكّن من تصنيف الصورة بشكل صحيح وبثقة عالية.




##  🔧 ملاحظة مهمة لحل مشكلة اختلاف الإصدار:

إذا ظهر لك خطأ يتعلق باختلاف إصدار مكتبة TensorFlow أو Keras عند تشغيل السكريبت
![image](https://github.com/user-attachments/assets/168a0981-dd0f-4a59-aca2-60077e6536fe)

يمكنك حل المشكلة بتحميل النسخة المناسبة مباشرة باستخدام هذا الأمر :
![image](https://github.com/user-attachments/assets/3aafbe36-2498-459d-a2b8-46be9c1ee77e)








