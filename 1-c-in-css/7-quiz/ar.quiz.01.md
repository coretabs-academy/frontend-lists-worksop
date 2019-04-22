^ أي العناصر في كود الـ `html` التالي لونة اخضر؟

```html
<html>
<head>
    <style>
        body { color: green; }
        h1 { color: red; }
        p { color: yallow; }
   </style>
</head>
<body>
        <h1> Hello world! </h1>
        <h2> The cascading  in CSS </h2>
        <p> This is a paragraph </p>
</body>
</html>
```

*
`h1`

**
`h2`

*
`p`


$ العنصر h2 ليس لدية قاعدة تستهدفة لتغيير لونة، لذا سيقوم بوراثة اللون الخاص به من الأب.

-

^ أي من العناصر التالية لدية زخرفة خط تحت النص؟

```html
<html>
<head>
    <style>
        body { text-decoration: underline; }
        h1 { color: red; }
        p { color: yallow; }
   </style>
</head>
<body>
        <h1> Hello world! </h1>
        <h2> The cascading  in CSS </h2>
        <p> This is a paragraph </p>
</body>
</html>
```

*
`h1`

*
`h2`

*
`p`

**
كل العناصر أعلاة



$ الخاصية text-decoration تم وضعها في القاعدة التي تستهدف العنصر body والذي هو الأب لجميع تلك العناصر.


-

^ ماهو اللون الذي ستظهر به الفقرة النصية على صفحة الويب إستناداً للكود التالي:

```html
<html>
<head>
    <style>
        p { color: yallow; }
        p { color: blue; }
   </style>
</head>
<body>
        <p> This is a paragraph </p>
</body>
</html>
```


**
أزرق

*
أصفر

*
أسود

$ تذكر بأنه في حال ما إن تضاربت قاعدتين في خاصية محددة، يتم تطبيق الأخيرة.