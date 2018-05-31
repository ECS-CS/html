# 📌 CAPSTONE PROJECT: WEEK 3, DAY 2.

# DO NOW 🔊

1.  BE QUIET
2.  GIVE YOUR INSTRUCTOR YOUR ATTENTION
3.  OPEN **CODEPEN.IO** AND SIGN IN
4.  OPEN **https://github.com/ECS-CS/html** IN ANOTHER TAB THEN CLICK **Y1-Q4-Capstone** THEN **Week3Day2.md**
5.  YOU SHOULD ALWAYS HAVE AT LEAST TWO TABS OPENED

# FORKING

1.  After logging into CodePen
2.  Click the profile icon in the top right and go to **Your Profile**
3.  Click **CAPSTONE PROJECT 3**
4.  Then, **FORK** this project and rename the new version to **CAPSTONE PROJECT 4** (ALL CAPS)
5.  The reason we do this is to ALWAYS have a fresh copy of our previous work just incase we make a mistake.

# HTML (5 MINS)

The Footer is the very last section on EVERY webpage. Usually, in this section you find copyright information, an additional navigational menu that your users can use, or a contact form, etc...

In HTML5 there is a special element designed for Footers:

```html
<footer></footer>
```

## STEP 1:

Insert this element after the **LAST** closing `</div>` tag in the **HTML section in CodePen** BUT **before** the closing `</body>` tag.

```html
<footer>My Footer</footer>
```

## EXAMPLE:

An Example of a Footer element:

```html
<footer>
  <p>Website created by: Mr. Bostwick</p>
  <p>Contact information: <a href="mailto:mrbostwick@bostwick.com">
  mrbostwick@bostwick.com</a>.</p>
</footer>
```

# CSS (2 MINS)

## STEP 1:

In order to KEEP our Footer on the bottom of our webpage at all times, we have to add this style at the VERY top of our **CSS section** in CodePen.

```css
body {
  display: grid;
  grid-template-rows: repeat(7, auto);
  min-height: 100vh;
}
```

## STEP 2:

In the **CSS** section in CodePen lets locate this area:

_If you don't have this section you can add it in directly._

```css
#home,
#about,
#projects,
#contactme {
  height: auto;
  border: 1px solid black;
  margin-top: 20px;
  padding: 30px;
}
```

After **#contactme**, lets add a comma and type footer, just like this below:

```css
#home,
#about,
#projects,
#contactme,
footer {
  height: auto;
  border: 1px solid black;
  margin-top: 20px;
  padding: 30px;
}
```

**NOTE**: We add borders to give us a visual cue indicating how our content is split up. You are more then welcome to remove any border or change the color or style of them!

# LAST CAPSTONE LESSON

If you attended every class AND finished every lesson your website should have this general layout:

## https://codepen.io/GainorB/full/bKdpww/

Additionally, this is how your website should look without completing any homework assignments. In other words, if your website is still bare like this example means you haven't completed your homework assignments. Every week, we added to our websites to make it look more unique.

# 🚨🚨 HOMEWORK 🚨🚨

## To receive full credit for this part of your Capstone Project, you will have to do the following:

## HTML CHANGES

(These changes will be made in the **HTML section of CodePen**)

1.  Add content to the `<footer></footer>` element you created

## CSS CHANGES

(These changes will be made in the **CSS section of CodePen**)

2.  Add styles to your Footer element by targeting it with CSS.

**HINT:**

```css
footer {
}
```

# FINISHED CODE

If for any reason you lose your code, or came late to class, absent or (anything else you can think of that kept you from completing this lesson), you can **FORK** this pen to create a copy to your account.

Any other words, this is your **starting point** before you complete your deliverables.

## https://codepen.io/GainorB/pen/bKdpww

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
