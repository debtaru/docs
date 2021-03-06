---
$title: المعاينة والتحقق
---

عاين صفحة AMP تمامًا مثلما تعاين أي موقع ويب HTML ثابت آخر. لا توجد خطوة إنشاء أو معالجة مسبقة مطلوبة. إما:

  - **أن تفتحها مباشرةً في المتصفح من نظام الملفات** (قد لا تعمل بعض العناصر بسبب فشل XMLHttpRequests).
  - **أو تستخدم خادم ويب محلي، مثل Apache 2 أو Nginx**.
    *(نصيحة: لتسريع خادم الويب، شغّل<span dir="ltr" class="nowrap">`python -m SimpleHTTPServer`</span>.)*

بعد ذلك، تأكّد من أن صفحة AMP **صفحة AMP صالحة بالفعل**، وإلا فلن يتم اكتشافها وتوزيعها بواسطة أنظمة أساسية من جهة خارجية، مثل بحث Google. للتحقق:

  1. افتح صفحتك في متصفحك.
  1. أضف "<span dir="ltr" class="nowrap">`#development=1`</span>" إلى عنوان URL، على سبيل المثال، <span dir="ltr" class="nowrap">`http://localhost:8000/released.amp.html#development=1`</span>.
  1. افتح [وحدة تحكم <span dir="ltr" class="nowrap">Chrome DevTools</span>](https://developers.google.com/web/tools/chrome-devtools/debug/console/) وابحث عن أخطاء التحقق.

[تعرّف على المزيد بشأن التحقق](/ar/docs/fundamentals/validate.html)، وما يتعين فعله عند مصادفة أخطاء.

<div class="prev-next-buttons">
  <a class="button prev-button" href="/ar/docs/getting_started/create/presentation_layout.html"><span class="arrow-prev">سابق</span></a>
  <a class="button next-button" href="/ar/docs/getting_started/create/prepare_for_discovery.html"><span class="arrow-next">التالى</span></a>
</div>
