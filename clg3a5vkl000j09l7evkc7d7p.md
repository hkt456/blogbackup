---
title: "Introduction to HTML-Part 1"
datePublished: Wed Apr 05 2023 06:00:32 GMT+0000 (Coordinated Universal Time)
cuid: clg3a5vkl000j09l7evkc7d7p
slug: introduction-to-html-part-1
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680446672101/3b964428-ffda-492b-82e8-627e6334e14e.jpeg
tags: web-development, html5, vscode

---

---

# Preface

After 2 posts about not-so-programmish topics, this blog is looking like it's more like a personal journal. So to prove that I was not lying about this blog being a programming blog, I have decided to start a series on web development!

Make sure to stay tuned!

---

# The background of HTML

HTML, which stands for Hypertext Markup Language, is a fundamental building block for creating websites and blogs. It is a markup language used to structure content on the web by defining the different types of content such as text, images, links, and more. HTML allows content creators to add headings, paragraphs, lists, images, and other media to their pages.

For a blog, HTML is used to create the overall structure of the website, such as defining the header and footer, setting up the layout of the pages, and formatting the text of the blog posts. HTML tags are used to define the different elements of the page and provide information about how the content should be displayed in the browser.

---

## The History of HTML

HTML was first introduced in 1991 by Tim Berners-Lee, a British computer scientist who is widely credited as the inventor of the World Wide Web. At the time, Berners-Lee was working at the European Organization for Nuclear Research (CERN) and was seeking a way to share information between scientists and researchers working in different locations.

The first version of HTML, HTML 1.0, was a very basic language that allowed users to create simple web pages with headings, paragraphs, and lists. Over time, as the web grew in popularity, HTML evolved to include more complex features such as tables, forms, and multimedia content.

In 1995, the World Wide Web Consortium (W3C) was founded to develop and maintain web standards, including HTML. The release of HTML 2.0 in the same year marked the beginning of a more formalized standardization process.

In the years that followed, HTML continued to evolve, with new versions and features being added regularly. HTML 3.2, released in 1997, introduced support for tables, image maps, and forms, while HTML 4.0, released in 1998, added support for cascading style sheets (CSS) and scripting languages like JavaScript.

In 2000, the W3C released XHTML 1.0, which was based on XML, a more structured and modular markup language. XHTML was designed to be more extensible and to support the development of more complex web applications.

Today, HTML is the foundation of the web, and the latest version, HTML5, provides support for multimedia content, improved accessibility, and a more flexible and modular approach to web development.

---

## Give me a high (HTML)5!

HTML5 is the latest version of HTML, which is the core markup language used to structure content on the web. HTML5 was released by the World Wide Web Consortium (W3C) in 2014 and is the result of a collaborative effort by web developers and browser vendors to improve the language and its capabilities.

One of the key benefits of HTML5 is its ability to support multimedia content natively without the need for third-party plugins like Adobe Flash or Microsoft Silverlight. This includes support for audio and video elements, as well as animations and graphics using the new Canvas element.

HTML5 also includes new elements and attributes that make it easier to structure web content and make it more accessible to users. These include new semantic elements like &lt;header&gt;, &lt;footer&gt;, &lt;nav&gt;, and &lt;section&gt;, which help to provide additional meaning and context to the content.

Another important feature of HTML5 is its support for responsive web design, which allows websites to adapt their layout and content to different screen sizes and devices. This is achieved through new features like media queries and the viewport meta tag.

Overall, HTML5 provides web developers with a more powerful and flexible set of tools for creating dynamic, interactive, and accessible web content.

---

# Basic HTML

## The structure

Let's jump right into the syntax and the basic structure of an HTML code.

```plaintext
Hello World! I am learning HTML!
```

Now I want to print the above message onto my website, what should I do?

Firstly, we need to create an HTML file. According to "Coders' rulebook", most main HTML files should be named "index.html"

Secondly, if you are using Visual Studio Code as your IDE, there's a trick to instantaneously create a default HTML structure:

```plaintext
!
```

By typing '!' and pressing *"RETURN", you will get the following result:*

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

This is what a basic HTML structure looks like, don't worry if you don't understand it, we will get to it in a moment.

---

## The Syntax

To change the content of our page, we will need to alter the content inside the `body` tag.

To give a heading to our website, we will need to add a `<h1>` tag.

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>This is my first HTML web!<h1>
</body>
</html>
```

This should appear on your locally hosted page:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680667736826/4b7c9450-2649-474d-96a2-8655ede2d762.jpeg align="center")

Apart from the `<h1>` tag, you also have 5 other tags for your heading: `<h2>` ,`<h3>` `<h4>` ,`<h5>` ,`<h6>`

And to put more text content on your page, you can also use other tags like `<p1>` , `<span>`,...

If you want to do your own research on what kinds of tags there are, you can use this website as a reference: [https://www.w3schools.com/TAGs/](https://www.w3schools.com/TAGs/)

## Example

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>This is my first HTML web!<h1>
    <h2>The reasons why I should learn HTML</h2>
    <p>It is the frontend backbone of website development</p>
    <p>It is easy!</p>
    <h2>Why it is so fun to learn HTML</h2>
    <p>Because this blog is so detailed!</p>
    <p>Just kidding!</p>
</body>
</html> 
```

The output:

![dskfj](https://cdn.hashnode.com/res/hashnode/image/upload/v1680668319865/e7acb6df-b454-4033-91d4-52888551b03d.jpeg align="center")

You can also use other elements in HTML to decorate texts (bold it,...), and we will discuss how to do that in later blogs in this series.

---

# Conclusion

We have learned the basic syntax and structure of an HTML file and actually implemented the knowledge to a basic webpage.

In the next blog, we will go deeper into the capabilities of HTML, like how to embed an image and buttons,...

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1680673748609/08ef5a94-e79f-492e-be11-eda09c640cf9.png align="center")

Thank you for going so far into this blog. This is actually my first time writing a programming tutorial. If you have any questions or feedback, feel free to put a comment below, I will make sure to reply to you asap!