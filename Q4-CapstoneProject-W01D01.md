# DO NOW

1.  BE QUIET
2.  GIVE YOUR INSTRUCTOR YOUR ATTENTION
3.  OPEN **CODEPEN.IO** AND SIGN IN
4.  OPEN **https://github.com/ECS-CS/html** IN ANOTHER TAB THEN CLICK **Q4-CapstoneProject-W01D01.md**
5.  YOU SHOULD HAVE TWO TABS OPENED

# HTML

## STEP 1:

A couple weeks ago, we learned that every webpage has this structure. Let's type this in the **HTML section** in CodePen.

```html
<html>
<header>
<title>My Webpage Title</title>
<body>
</body>
</html>
```

## STEP 2

Inside the `<body></body>` tags, lets add the following:

1.  `<header>`: represents a container for introductory content or a set of navigational links.
2.  `<div>`: defines a division or a section in an HTML document. Often used as a container for other HTML elements to style them with CSS.

```html
<header>
  <div>Mr. Bostwick's Blog</div>
</header>
```

## STEP 3

Under the `<div>` but before the closing `</header>` tag we created in Step 2, lets copy and paste the `<nav>` tags and it's contents.

1.  `<nav>`: defines a set of navigation links.
2.  `<ul>`: defines an unordered (bulleted) list.
3.  `<li>`: defines a list item, nested inside the `<ul></ul>` tags.

```html
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Projects</li>
      <li>Contact Me</li>
    </ul>
  </nav>
```

## FIN

If you completed every step correctly, our HTML document should look like this. All of this code, should be in the **HTML** section in CodePen.

```html
<html>
<head>
<title>My Webpage Title</title>
</head>
<body>
<header>
  <div>Mr. Bostwick's Blog</div>
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Projects</li>
      <li>Contact Me</li>
    </ul>
  </nav>
</header>
</body>
</html>
```

# CSS

The ONLY way to learn CSS is by practicing and playing around with properties. CSS describes how our HTML elements look in the browser by targeting the HTML elements we created.

## STEP 1

We will **target** the `<div>` we created in Step 1 of HTML by doing the following:

We are styling the `<div>` by giving it a background-image, height and a font-size.

**Now, lets right click on this link and open in a new tab:**

🚨 https://www.w3schools.com/cssref/

```css
div {
  background-image: url("https://images.complex.com/complex/images/c_limit,w_680/fl_lossy,pg_1,q_auto/necg5t6ikqpsh8zkfhj6/lebron-james-cavaliers-celtics-january-2018");
  height: 270px;
  background-repeat: no-repeat;
  background-position: top;
  background-size: cover;
  color: white;
  text-align: center;
  line-height: 270px;
  font-size: 60px;
  border: 1px solid black;
}
```

## STEP 2

Copy and Paste the remaining CSS into the CSS section of CodePen.

In this segment, we are targeting the `<nav>`, `<ul>`, and `<li>` tags and adding styles to them.

For example, we gave the `<nav>` element a lightgrey background, and when the text is hovered, we change the background color to white.

```css
nav {
  margin-top: 5px;
  width: 100%;
  background-color: lightgrey;
}

ul {
  list-style: none;
  text-align: center;
  margin: 0;
  padding: 0;
}

ul li {
  display: inline-block;
  padding: 20px 40px;
}

ul li:hover {
  text-decoration: underline;
  background-color: white;
  font-weight: 700;
  cursor: pointer;
}
```

## FIN

If you completed every step correctly, our CSS stylesheet should look like this. All of this code, should be in the **CSS** section in CodePen.

```css
div {
  background: url("https://images.complex.com/complex/images/c_limit,w_680/fl_lossy,pg_1,q_auto/necg5t6ikqpsh8zkfhj6/lebron-james-cavaliers-celtics-january-2018");
  height: 270px;
  background-repeat: no-repeat;
  background-position: top;
  background-size: cover;
  color: white;
  text-align: center;
  line-height: 270px;
  font-size: 60px;
  border: 1px solid black;
}

nav {
  margin-top: 5px;
  width: 100%;
  background: lightgrey;
}

ul {
  list-style: none;
  text-align: center;
  margin: 0;
  padding: 0;
}

ul li {
  display: inline-block;
  padding: 20px 40px;
}

ul li:hover {
  text-decoration: underline;
  background-color: white;
  font-weight: 700;
  cursor: pointer;
}
```

# 🚨🚨 DELIVERABLE

To receive full credit for this part of your Capstone Project, you will have to do the following:

## HTML CHANGES

(These changes will be in the **HTML section of CodePen**)

1.  Update the Header image. Using google, find your own header image (Remember you need the **Image Address**).
2.  Update the title of your webpage (the text between `<title></title>` tags).

## CSS CHANGES

(These changes will be in the **CSS section of CodePen**)

3.  Change the header text from "Mr. Bostwick's Blog"
4.  Change the 'font-size' of the `<div>`.
5.  Change the background color of the `<nav>` element.
6.  Change the :hover color of navbar. **(HINT: look at ul li:hover {})**

# LEARNING RESOURCES

1.  Learn HTML: https://www.w3schools.com/html/default.asp
2.  Learn CSS: https://www.w3schools.com/css/default.asp
