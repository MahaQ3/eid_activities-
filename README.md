<div dir="rtl">
# فعاليات العيد :

## الفكرة 

 تدور فكرة المسابقة حول مجموعة من الرحلات  وفريقين , في كل رحله يتم طرح لغز هذا اللغز يدل على مكان ما في الساحة التي تغطى فيها المسابقة ,<br />
 في هذا المكان توضع رسالة تحتوي على كود الانتقال للمرحلة التالية والذي يحسب نقطه في صالح الفريق الذي قام بادخاله .
 
 ## طريقة اللعب :
 قسم المجموعة المشاركة الى فريقين (او اكثر) , شارك رابط [الصفحة الرئيسية](https://github.com/MahaQ3/eid_activities/blob/main/index.php)
 مع قائد كل فريق او جميع الاعضاء مع التزام اعضاء الفريق الواحد بكتابة اسم فريقهم بنفس الاسم تماما , يتم الضغط على زر ابدأ عندما ينتهي جميع الافرقة من كتابة اسمائهم .
 يتم نقلهم تلقائيا بعد ذلك لصفحة الاسئلة للمرحلة الاولى, عند ظهور السؤال يتناقش اعضاء الفريق الواحد عن المكان الذي يدل عليه السؤال ثم يذهبون الى هناك ويبحثون عن الرسالة للحصول على كود الانتقال للمرحلة التالية وادخاله في المربع , اول فريق يقوم بادخال الكود يحصل على نقطه ويتم توجيهه جميع الافرقه للمرحله التي تليها بشكل تلقائي .
 -ملاحظة : يتم تحديث الصفحة كل 30 ثانيه تلقائيا كي يلحق الفريق بالركب في حال قام فريق اخر بايجاد كود الانتقال قبله .
 
 ## طريقة اعداد المسابقة :
 - أولا : قم برفع ملف [القاعدة ](https://github.com/MahaQ3/eid_activities/blob/main/eid_activities.sql)
  <br/> &nbsp;   في قاعدة بياناتنا : يتواجد 3 جداول : <br/>
  جدول (teams):
  هو جدول خاص بالافرقة ونقاطهم 
  <br/> 
  جدول (state):
  يرمز للمرحلة التي فيها الان , توضع في المرحله الاولى في البداية 
<br/>
  جدول (qanda):
  يظهر رقم كل سؤال(مرحلة) وجوابة 
 - ثانيا: قم بالانتقال الى صفحة [الاسئلة](https://github.com/MahaQ3/eid_activities/blob/main/question_page.php) 
  ستلاحظ  ان لديك 7 مراحل , تستطيع تغير السؤال الذي تريد او اضافة او حذف سؤال مع ملاحظة تغير ارقام المراحل بشكل متسلسل هنا وفي جدول "qanda".<br/>
 .ملاحظة : المرحلة الثامنه هي مرحله ثابته لانها الاخيره وهي مرحلة النتائج 
 
 ---
 أتمنى لكم قضاء وقت ممتع.
</div>
