# صفحات الهبوط — مكتب ريان | 1.1.0

**معاينة الصفحات الأربع:** [فتح GitHub Pages](https://ads2030r-arch.github.io/ryan-landing-pages-preview/)

هذه نسخة اختبار عامة لاختبار تصميم ومحتوى صفحات الهبوط قبل أي رفع إلى WordPress.

| الخدمة | صفحة المعاينة |
|---|---|
| الرفع المساحي | [/lp/surveying-riyadh/](https://ads2030r-arch.github.io/ryan-landing-pages-preview/lp/surveying-riyadh/) |
| الاستشارات الهندسية | [/lp/engineering-consulting-riyadh/](https://ads2030r-arch.github.io/ryan-landing-pages-preview/lp/engineering-consulting-riyadh/) |
| رخص البناء والترميم | [/lp/building-permits-riyadh/](https://ads2030r-arch.github.io/ryan-landing-pages-preview/lp/building-permits-riyadh/) |
| الصكوك العقارية | [/lp/sukuk/](https://ads2030r-arch.github.io/ryan-landing-pages-preview/lp/sukuk/) |

## الحزم

- [حزمة إضافة WordPress 1.1.0](ryan-landing-pages-v1.1.0.zip) — قابلة للرفع، لكنها **غير مثبتة أو مفعّلة على WordPress**.
- [أرشيف المعاينة الثابتة 1.1.0](ryan-landing-pages-preview-v1.1.0.zip) — المصدر الذي يفكّه سير GitHub Actions إلى Pages.
- [بصمات SHA-256](SHA256SUMS) للتحقق من سلامة الحزم.
- `.github/workflows/pages.yml` مسار النشر إلى GitHub Pages.

## حدود المعاينة

الموقع الثابت يحمل `noindex,nofollow` وملف `robots.txt` يمنع الزحف. لا تحفظ الصفحات بيانات الزوار؛ النماذج وأزرار الهاتف وWhatsApp غير فعالة في المعاينة. هذا يسمح بمراجعة النص والتصميم فقط، ولا يمثل اختبار WordPress أو CRM أو GTM/GA4.

حزمة WordPress تستخدم HTML خادميًا للمحتوى والعناوين. في بيئة الإنتاج ستجهز الاستمارة رسالة WhatsApp للمراجعة؛ النقر أو فتح WhatsApp لا يثبت إرسال الرسالة. الإصدار لا يكتب تلقائيًا إلى Ryan Sales CRM ولا يغير إعدادات GTM أو GA4 أو Google Ads.

## الحفاظ على الخصوصية والنطاق

المستودع عام بناءً على اختيار مالك الحساب، ولا يحتوي بيانات دخول أو مفاتيح سرية. لا يمنح المستودع ترخيصًا عامًا لإعادة استخدام العلامة أو المحتوى أو الأصول. لا تستخدم الحزمة على الموقع الإنتاجي قبل المراجعة والاختبار والاعتماد.
