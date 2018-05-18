# 📌 CAPSTONE PROJECT: WEEK 1, DAY 1.

# DO NOW 🔊

1.  BE QUIET
2.  GIVE YOUR INSTRUCTOR YOUR ATTENTION
3.  OPEN **CODEPEN.IO** AND SIGN IN
4.  OPEN **https://github.com/ECS-CS/html** IN ANOTHER TAB THEN CLICK **Y1-Q4-Capstone** THEN **Week1Day1.md**
5.  YOU SHOULD ALWAYS HAVE AT LEAST TWO TABS OPENED

# STRUCTURE OF THE 4TH QUARTER

1.  We have 4 full weeks remaining in the 4th Quarter.
2.  Every class, we will tackle a piece of our Capstone Project.
3.  After every class, if you don't finish the **DELIVERABLE** it will become **HOMEWORK**, which is due two days from class at 6PM.
4.  Therefore at the end of the quarter you will have 4 TEST grades, that will get averaged to form your Capstone Grade, resulting in 5 grades for the quarter.

# HTML (10 MINS)

## STEP 1:

A couple weeks ago, we learned that every webpage has this structure. Let's type this in the **HTML section in CodePen.**

```html
<html>
  <head>
    <title>My Webpage Title</title>
  </head>
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

After the closing `</div>` tag but before the closing `</header>` tag we created in Step 2, lets copy and paste the `<nav>` tags and it's contents.

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

If you completed every step correctly, our HTML document should look like this. All of this code, should be in the **HTML section in CodePen**.

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

# CSS (5 MINS)

The ONLY way to learn CSS is by practicing and playing around with properties. CSS describes how our HTML elements look in the browser by targeting the HTML elements we created.

## STEP 1

We are styling the `<div>` element by giving it a background-image, height, font-size, and a font color.

**Now, lets right click on this link and open in a new tab:**

🚨 https://www.w3schools.com/cssref/

## W3Schools is a great resource that will teach us CSS/HTML. It will show us the possible values for the CSS properties we defined below.

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

Copy and Paste the remaining CSS into the CSS section of CodePen. **(AFTER what you had before)**

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

Our CSS stylesheet should look like this. All of this code, should be in the **CSS section in CodePen**.

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

# 🚨🚨 DELIVERABLE 🚨🚨

## To receive full credit for this part of your Capstone Project, you will have to do the following:

## HTML CHANGES

(These changes will be made in the **HTML section of CodePen**)

1.  Update the title of your webpage (the text between `<title></title>` tags).
2.  Change the header text from "Mr. Bostwick's Blog"

## CSS CHANGES

(These changes will be made in the **CSS section of CodePen**)

3.  Update the Header image. Using google, find your own header image (Remember you need the **Image Address**). You can change the **height** of the div to fit your image.
4.  Change the 'font-size' of the `<div>`.
5.  Change the background color of the `<nav>` element.
6.  Change the :hover color of navbar. **(HINT: look for the ul li:hover {} element)**

# FINISHED CODE

If for any reason you lose your code, or came late to class, absent or (anything else you can think of that kept you from completing this lesson), you can **FORK** this pen to create a copy to your account.

Any other words, this is your **starting point** before you complete your deliverables above.

## https://codepen.io/GainorB/pen/QrVpxQ

# 🚨 MAKE SURE YOU SAVE AND SIGN OUT 🚨

# LEARNING RESOURCES

1.  Learn HTML: https://www.w3schools.com/html/default.asp
2.  Learn CSS: https://www.w3schools.com/css/default.asp

# EXTENDED CLASS HOURS

## If for any reason you need more time to work on an assignment, we are available to work with you directly during lunch or after school until 6PM.

# MAC KEYBOARD SHORTCUTS

1.  CMD + C: copy
2.  CMD + V: paste
3.  CMD + X: cut
4.  CMD + A: select all
5.  CMD + Z: undo
