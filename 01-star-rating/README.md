# Question 1: Star Rating

Create star rating utility using HTML, CSS and JavaScript

## Template

> HTML

```html
<body>
  <div id="star"></div>
  <div id="display-star"></div>

  <script src="script.js"></script>
  <script>
    function getStar(value) {
      document.getElementById("display-star").innerHTML = value;
    }
    new Star("#star", 5, getStar);
  </script>
</body>
```

> External CSS

```html
<link
  rel="stylesheet"
  href="https://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css"
/>
```

> Star Icons

```html
<i class="fa fa-star"></i> <i class="fa fa-star-o"></i>
```

> CSS

```css
.fa-star-o:before {
  content: "\f006";
  color: #5f6368;
}

.fa-star:before {
  content: "\f005";
  color: #d56e0c;
}
```

> JS

```js
/*
 * Creates star rating functionality
 * @param el DOM Element
 * @param count Number of stars
 * @param callback Returns selected star count to callback
 */
function Star(el, count, callback) {
  // write logic to create star rating utility.
}
```

## Demo

> Default state

![default](../assets/1_1.png)

> On Hover

![hover](../assets/1_2.png)

> On Click

![click](../assets/1_3.png)
