# موقع الكتروني خاص ببوت التمويل

- يمكنك استخدام الملفات لكي تقوم بتطوير موقع الخاص 

--------------------------------------------

# API : 

1. لجلب معلومات الكي الخاص بالمستخدم : 

`https://bot.keko.dev/api.php?key={KEY}` : **Response** : [

 - true : `{"ok":true,"chat_id":"775392974","bot_id":"1220697355","bot_username":"TMOLbbot","coin":"775223160"}`

- false : `{"ok":false}` // KEY IS EXPIEED!!

 ]

2. لعرض قناة او مجموعة او لتخطي قناة او مجموعة : `https://bot.keko.dev/api.php`

- Cookie : `key={KEY}` : **Response** : [

 - true : `{

  "ok": true,

  "title": "رماد💔",

  "url": "https://t.me/Ali1233sh",

  "id": "@Ali1233sh", --> {ID}

  "t": "c", // type : chat or group

  "coin": "1000",

  "tgurl": "tg://resolve?domain=Ali1233sh",

  "f": [

    ["msg":"عليك الاشتراك في القناه وبعد ذلك اضغط تحقق 🖤🥀", "alert":"alert-danger"],

    ["msg":"تم خصم 20 من نقاطك بسبب مغادره قناة (اسم قناة) ", "alert":"alert-danger"],

  ], // alert msg

  "MemberCount": 199,

  "photo": "base64"

}`

- false : `{"ok":false}` // KEY IS EXPIEED!!

]

3. للتحقق من الاشتراك في قناة او مجموعة وعرض قناة او مجموعة جديده: `https://bot.keko.dev/api.php?c={ID}`

- Cookie : `key={KEY}` : **Response** : [

 - صحيح: "{
.
  "موافق": صحيح ،

  "title": "رماد💔",

  "url": "https://t.me/Ali1233sh",

  "id": "@Ali1233sh",

  "t": "c", // type : chat or group

  "coin": "1000",

  "tgurl": "tg://resolve?domain=Ali1233sh",

  "f": [

    ["msg":"😊❤️ عليك الاشتراك في القناة من ثم ضغط على زر التحقق", "alert":"alert-danger"],

    ["msg":" 🥳 تم اضافه 10 الى نقاطك بسبب الاشتراك في القناة", "alert":"alert-success"],

    ["msg":"تم خصم 20 من نقاطك بسبب مغادره قناة (اسم قناة) ", "alert":"alert-danger"],

  ], // alert msg

  "MemberCount": 199,

  "photo": "base64"

}`

- false : `{"ok":false}` // KEY IS EXPIEED!!

 ]

--------------------------------------------

- يحق لاي شخص استخدام الملفات داخل صانع ايكو فقط ولا يسمح لغير ذالك 

- BY : https://t.me/mkfrbot







