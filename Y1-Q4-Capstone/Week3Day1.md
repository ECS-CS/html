# 📌 CAPSTONE PROJECT: WEEK 3, DAY 1.

# DO NOW 🔊

1.  BE QUIET
2.  GIVE YOUR INSTRUCTOR YOUR ATTENTION
3.  OPEN **CODEPEN.IO** AND SIGN IN
4.  OPEN **https://github.com/ECS-CS/html** IN ANOTHER TAB THEN CLICK **Y1-Q4-Capstone** THEN **Week3Day1.md**
5.  YOU SHOULD ALWAYS HAVE AT LEAST TWO TABS OPENED

# FORKING

1.  After logging into CodePen
2.  Click the profile icon in the top right and go to **Your Profile**
3.  Click **CAPSTONE PROJECT 2**
4.  Then, **FORK** this project and rename the new version to **CAPSTONE PROJECT 3** (ALL CAPS)
5.  The reason we do this is to ALWAYS have a fresh copy of our previous work just incase we make a mistake.

# HTML (10 MINS)

After completing last week's assignment, we should all have functional navigation links. Today we will focus on adding the remaining sections for our links to navigate to.

In class we created this HTML element together:

```html
<div id="home">My Content Goes Here</div>
```

**AND** our navigational menu looks like this:

```html
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contactme">Contact Me</a></li>
    </ul>
  </nav>
```

## STEP 1:

Let's create the remaining sections for our links to navigate to.

We have 3 links that don't navigate anywhere. We need to position the 3 elements below and make a small change to them to get it to work with our menu.

**Question: What do we have to update below to get our new HTML elements to work with our menu?**

```html
<div id="home">My Content Goes Here</div>
```

```html
<div id="home">My Content Goes Here</div>
```

```html
<div id="home">My Content Goes Here</div>
```

## STEP 2:

We should now have this:

Notice the **id** attribute matches the **href** attribute in our anchor tags minus the **hashtag** (#). In fact, in HTML **#** corresponds to **id**.

```html
<div id="about">My Content Goes Here</div>
```

```html
<div id="projects">My Content Goes Here</div>
```

```html
<div id="contactme">My Content Goes Here</div>
```

Great now, we have 3 elements our links can navigate to.

**Question: Where should we place these elements?**

## STEP 3:

Insert these 3 elements after the **LAST** closing `</div>` tag in the **HTML section in CodePen** BUT **before** the closing `</body>` tag.

Insert all 3 elements back-to-back, after the element we added last class:

```html
<div id="home">My Content Goes Here</div>

<div id="about">My Content Goes Here</div>
<div id="projects">My Content Goes Here</div>
<div id="contactme">My Content Goes Here</div>
```

# CSS (1 MINS)

We are going to style the sections we created above using the code below.

Let's copy and paste the code below in the **CSS section** of CodePen below what we currently have.

```css
#home,
#about,
#projects,
#contactme {
  width: 100%;
  height: 300px;
  border: 1px solid black;
  margin-top: 20px;
  padding: 30px;
}
```

**NOTE**: We add borders to give us a visual cue indicating how our content is split up. You are more then welcome to remove any border or change the color or style of them!

# 🚨🚨 HOMEWORK 🚨🚨

## To receive full credit for this part of your Capstone Project, you will have to do the following:

## HTML CHANGES

(These changes will be made in the **HTML section of CodePen**)

1.  Insert `<p></p>` tags around the **CONTENT** in the new HTML elements we added above.
2.  Update 'My Content Goes Here' with your own content. Must be a minimum of 3 sentences.
3.  You probably noticed the `<p></p>` tags you added, are already styled. Let's add a class to the `<p></p>` tags.

**HINT:**

```html
<div id="about"><p class="....">My Content Goes Here</p></div>
```

```html
<div id="projects"><p class="....">My Content Goes Here</p></div>
```

```html
<div id="contactme"><p class="....">My Content Goes Here</p></div>
```

## CSS CHANGES

(These changes will be made in the **CSS section of CodePen**)

**We added 3 elements together in class, so now you have to target **EACH** element individually and STYLE it.**

4.  Target the class you added above, and style it. (ex: font-size, font-weight, color, text-align, etc..)
5.  Target the class you added above, and style it. (ex: font-size, font-weight, color, text-align, etc..)
6.  Target the class you added above, and style it. (ex: font-size, font-weight, color, text-align, etc..)

# FINISHED CODE

If for any reason you lose your code, or came late to class, absent or (anything else you can think of that kept you from completing this lesson), you can **FORK** this pen to create a copy to your account.

Any other words, this is your **starting point** before you complete your deliverables.

## https://codepen.io/GainorB/pen/JZjNoq

## 🚨 MAKE SURE YOU SAVE AND SIGN OUT 🚨

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
