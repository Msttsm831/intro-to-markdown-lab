![Boilerplate](https://images.unsplash.com/photo-1517134062979-e1234be8a085?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

# How to Write an HTML Boilerplate
In web development, an HTML boilerplate serves as the foundation for every web page you build. It ensures your document is properly formatted and contains essential elements to function across browsers. This tutorial walks you through writing an HTML boilerplate from scratch.

## 1. What is an HTML Boilerplate?
An HTML boilerplate is a pre-written structure of code that provides the basic framework of an HTML document. It includes essential tags and attributes that every web page should have. Think of it as the skeleton of your web page.

## 2. The Basic Structure of an HTML Boilerplate

An HTML boilerplate includes the following main sections:

1. The **doctype** declaration: Defines the version of HTML.
2. The `<html>` tag: Wraps all your content.
3. The `<head>` section: Contains metadata and resources.
4. The `<body>` section: Contains visible content.


## 3. Writing Your Boilerplate
### Step 1: The Doctype Declaration
Start your file with the following line:

`<!DOCTYPE html>`
This declaration tells the browser you’re using **HTML5**, the latest standard.

### Step 2: The HTML Tag
Wrap all your code in the `<html>` element:

`<html lang="en">`
The lang="en" attribute specifies the language of your document. It's essential for accessibility and SEO.

### Step 3: The Head Section
Add the `<head>` section to include metadata about your document:

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document Title</title>
```

* `<meta charset="UTF-8">`: Ensures proper text rendering.
* `<meta name="viewport">`: Makes your site mobile-friendly.
* `<title>`: Specifies the name of your webpage.


### Step 4: The Body Section
Add the `<body>` tag for visible content:

>`<h1>`Welcome to My Website`</h1>` `<p>`This is a basic HTML boilerplate.`</p>`
>The `<body>` tag will house your headings, paragraphs, images, and more.

### Step 5: The Complete Boilerplate

Here’s what your full boilerplate looks like:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Boilerplate</title>
</head>
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a basic HTML boilerplate.</p>
</body>
</html>
```

>Comments can help document your code: `<!-- This is a comment -->`

Test your boilerplate in a browser to ensure it renders correctly.

### 5. Conclusion
Now that you’ve learned how to write an HTML boilerplate, you can use it as a starting point for all your projects. It’s a simple but powerful foundation for creating professional and consistent web pages.

For more information on HTML, check out the MDN Web Docs: 
[MDN DOCS](https://developer.mozilla.org/en-US/docs/Web/HTML)