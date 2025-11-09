```
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <hr>
    <section class="box">
        before<div class="a">display: inline-block</div>after
    </section>
    <hr>

</body>
</html>
```

```
section{
    line-height: 50px;
    color: red;
}

div{
    width: 200px;
    height: 50px;
    display: inline-block;
}

.a{
    background-color: pink;
}
```