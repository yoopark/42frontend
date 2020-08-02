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

1. `href` attribute

```HTML
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
```

2. background

```HTML
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>
```

3. id, class, name

* *id* : HTML에서 고유명사, CSS에서 Selector(#)
* *class* : HTML에서 그룹, CSS에서 Selector(.)
* *name* : HTML에서 그룹, CSS에서 Selector 불가



4. HTML Javascript

```HTML
<!DOCTYPE html>
<html>
<body>

<h1>My First JavaScript</h1>
<p>Here, a JavaScript changes the value of the src (source) attribute of an image.</p>

<script>
function light(sw) {
  var pic;
  if (sw == 0) {
    pic = "pic_bulboff.gif"
  } else {
    pic = "pic_bulbon.gif"
  }
  document.getElementById('myImage').src = pic;
}
</script>

<img id="myImage" src="pic_bulboff.gif" width="100" height="180">

<p>
<button type="button" onclick="light(1)">Light On</button>
<button type="button" onclick="light(0)">Light Off</button>
</p>

</body>
</html>
```



5. HTML 기본 구성 틀

![img](https://www.w3schools.com/html/img_sem_elements.gif)

* https://www.w3schools.com/html/html5_syntax.asp

---

### III. HTML Form

1. 기본 예시

```HTML
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

