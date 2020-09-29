#

```
JavaScript HTML DOM
https://www.w3schools.com/js/js_htmldom.asp


```

#
```
https://www.w3schools.com/js/js_htmldom_methods.asp
```
```
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello World!";
</script>

</body>
</html>
```
# DOM==Document Object Model   ==>存取網頁中的元素(html標籤)
```
https://www.w3schools.com/js/js_htmldom_document.asp
https://www.w3schools.com/js/js_htmldom_elements.asp
```
```
<!DOCTYPE html>
<html>
<body>

<h2>Finding HTML Elements by Id</h2>

<p id="intro">Hello World!</p>
<p>This example demonstrates the <b>getElementsById</b> method.</p>

<p id="demo"></p>

<script>
var myElement = document.getElementById("intro");
document.getElementById("demo").innerHTML = 
"The text from the intro paragraph is " + myElement.innerHTML;
</script>

</body>
</html>
```
