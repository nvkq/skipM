# تخطي تحديد سرعة الإنترنت (4G/5G) لشركات الاتصالات
[<img src="https://img.shields.io/badge/Version-2.1-blue" alt="Experimental">](https://nvkq.github.io/skipM/STC.html)
 <img src="https://img.shields.io/badge/Status-Experimental-orange" alt="Experimental">

---

## **الوصف**  
هذه الطريقة تعتمد على "خدعة تقنية" لتجاوز تحديد السرعة التي تفرضها شركات الاتصالات عبر استغلال آلية عمل مواقع قياس السرعة (مثل Speedtest).  
الفكرة الأساسية هي جعل شركة الاتصالات تعتقد أنك تجري اختبار سرعة باستمرار، مما يمنحها سرعة أعلى مؤقتًا، والاستفادة من هذه السرعة في تصفح المواقع أو التحميل.

---

## **كيف تعمل؟**  
1. **المبدأ:**
   - شركات الاتصالات غالبًا تُظهر سرعات عالية أثناء اختبارات السرعة (لكسب تصنيفات عالمية).  
   - عند استخدام التطبيقات العادية (مثل YouTube أو التحميل)، تعود السرعة للانخفاض بسبب التقييد.  

2. **التنفيذ:**
   - إنشاء صفحة ويب تحتوي على **مؤقت** (Timer) لمدة 5 ثوانٍ.  
   - تحديث الصفحة تلقائيًا كل 5 ثوانٍ لإرسال طلبات لخوادم Speedtest.  
   - هذا يخدع شركة الاتصالات لمنح السرعة القصوى باستمرار.

---

## **الفوائد المحتملة**  
✅ تجاوز التقييد المؤقت للسرعة أثناء استخدام التطبيقات.  
✅ تحسين سرعة التحميل والتصفح في بعض الحالات.  
✅ لا يتطلب برامج معقدة (يعتمد على صفحة ويب بسيطة).

---

## **التحديات والقيود**  
⚠️ **قد لا تعمل في الحالات التالية:**  
- إذا كنت تستخدم باقة محدودة السرعة مسبقًا.  
- إذا اكتشفت شركة الاتصالات النشاط غير الطبيعي (مثل الطلبات المتكررة).  
- استهلاك عالي للبيانات والبطارية بسبب التحديث التلقائي.
- - لا تعمل إذا كانت باقة الإنترنت لديك **محدودة السرعة** (مثل 10 ميجابت/ثانية).  
- بعض الشركات تستخدم تقنيات متقدمة (مثل **Deep Packet Inspection**) لا تتأثر بهذه الطريقة.  

---

## **البدائل المقترحة**  
1. **استخدام VPN:**  
   لإخفاء حركة المرور الحقيقية عن شركة الاتصالات (غير مضمون).  
2. **تحسين إعدادات الشبكة:**  
   تغيير DNS أو استخدام بروتوكولات اتصال أسرع.  
3. **الترقية إلى باقة غير محدودة:**  
   الحل الأمثل لكنه قد يكون مكلفًا.

---

## **ملاحظات مهمة**  
- ⚠️ **تحذير:** قد تنتهك هذه الطريقة شروط استخدام شركة الاتصالات، مما يعرض حسابك للإيقاف.  
- 🔄 **تحديثات:**  
  - تمت إضافة "إصلاحات كبيرة" لتحسين التوافق مع الخوادم.  
  - السيرفر الآن يتأكد تلقائيًا من عمل الخوادم المستهدفة.  

---

## **الاستخدام**  
1. قم بزيارة الصفحة المُعدة مسبقًا (https://nvkq.github.io/skipM/).  
2. اترك الصفحة تعمل في الخلفية أثناء استخدام التطبيقات الأخرى.  

> **تنويه:** النتائج تختلف حسب سياسات شركة الاتصالات ونوع الباقة.
> > ⚠️ **تحذير**: هذا المشروع تجريبي تعليمي، استخدامه على مسؤوليتك!
> 
