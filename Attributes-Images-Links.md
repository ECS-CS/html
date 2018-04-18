# OBJECTIVE

1.  What are HTML attributes?
2.  What are anchor tags and how do we use them?
3.  How do we include images on our webpage?
4.  Do Image tags have closing tags?

# DO NOW (5-10 MINS)

**Choose a typing exercise:**

1.  General: https://www.typingtest.com/test.html?minutes=2&textfile=oz.txt
2.  Coding: http://www.speedcoder.net/lessons/html/1/

# HTML ATTRIBUTES

Elements can also have attributes, which look like this:

![HTML Attributes](/assets/html_attributes__p.jpg)

**Attributes contain extra information about the element which you don't want to appear in the actual content.** In this case, the **class** attribute allows you to give the element an identifying name that can be later used to target the element with style information. (We will dive into this further soon)

**An attribute should have:**

1.  A space between it and the element name (or the previous attribute, if the element already has one or more attributes)
2.  Attributes are always specified in the **start tag**.
3.  Attributes usually come in name/value pairs like: **attribute name="value"**

Full List of HTML Attributes: https://www.w3schools.com/tags/ref_attributes.asp

* **HTML attributes vary per the Element.** In other words, certain attributes don't work for every HTML element.

# LINKS (HYPERLINKS)

![HTML Attributes](/assets/html_attributes__link.png)

Another example of an element is `<a>` — this stands for **"anchor"** and will make the piece of text it wraps around into a **hyperlink**. This can take a number of attributes:

1.  **href:** This attribute specifies the web address that you want the link to go to; where the browser navigates to when the link is clicked. For example, **href="https://www.google.com/"**.
2.  **title:** The title attribute specifies extra information about the link. For example, **title="Google"**. This will appear as a tooltip when hovered over.
3.  **target:** The target attribute specifies the browsing context which will be used to display the link. For example, **target="\_blank"** will display the link in a new tab. If you want to display the link in the current tab just omit this attribute.

# IMAGES

![HTML Attributes](/assets/html_attributes__image.jpg)

Images can improve the design and the appearance of a web page. In HTML, images are defined with the <img> tag.

1.  The `<img>` tag is empty, it contains attributes only, **and does not have a closing tag**.
2.  The **src** attribute specifies the URL (web address) of the image:

```html
<img src="url">
```

3.  The **alt** attribute provides an alternate text for an image, if the user for some reason cannot view it.
4.  The value of the alt attribute should describe the image (a short description):

```html
<img src="url" alt="Description of Image">
```

# 🚨 INDEPENDENT ACTIVITY 🚨

## Lets practice adding images

1.  Go on google, find an image you like
2.  Get the image's URL (Right click on Image > Copy Image Address)
3.  Remember the image URL ends with an image extension (.jpg, .gif, .png)
4.  **Don't forget to include all neccessary attributes.**

## Creating your first link

1.  Let's create a link to our favorite website. How would we make this link open in a new tab? Add the correct attribute.

##

# REVIEW OF HTML ATTRIBUTES, IMAGES, LINKS

1.  Attributes contain extra information about the element.
2.  Attributes are always specified in the **start tag**.
3.  Attributes usually come in name/value pairs like: **attribute name="value"**
4.  The `<img>` tag is empty, it contains attributes only, **and does not have a closing tag**.

# CLOSING QUESTIONS 🚨

1.  What are HTML attributes?
2.  What are some examples of HTML attributes, and what element do they belong to?
3.  What is an anchor `(<a></a>)` tag?

# LEARNING RESOURCES

1.  Full List of HTML Attributes: https://www.w3schools.com/tags/ref_attributes.asp
2.  Learn HTML: https://www.w3schools.com/html/default.asp
