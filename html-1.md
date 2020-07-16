프론트엔드 첫걸음 1주차

HTML 문법 익숙해지기

박용준(yopark)

---

### I. HTML 기초 문법(HTML Introduction ~ HTML CSS)

1. HTML 기본 틀

```html
<!DOCTYPE html>
<html>
	<head>
    <title>Page Title</title>
    <link rel="stylesheet" href="styles.css">
	</head>
	<body>
    
    <h1>heading 1</h1>
    <h6>heading 6</h6>
    <p>paragraph</p>
    
    <a href="https://www.naver.com">link</a>
    <img src="naver.jpg">
    
	</body>
</html>
```



2. Tag, Element, Attribute, Argument

```HTML
<a href="https://www.naver.com">link</a>
```

* *Tag* : \<a>\</a>
* *Element* : \<a href="https://www.naver.com">link\</a>
* *Attribute* : href
* *Argument* : "https://www.naver.com"



3. CSS can be added to HTML documents in 3 ways:

* *Inline* : by using the `style` attribute inside HTML elements
* *Internal* : by using a `<style>` element in the `<head>` section
* *External* : by using a `<link>` element to link to an external CSS file

```HTML
#1 
<h1 style="color:blue;"></h1>

#2 
<style>
	h1	{color: blue;}
</style>

#3
h1 {
	color: blue;
}
```

* color, font-family, font-size, border, padding, margin

---

### II. HTML 세부 문법(HTML Links ~ )



