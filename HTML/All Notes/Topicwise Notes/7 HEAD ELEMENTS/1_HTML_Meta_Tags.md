<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">HTML Meta Tags</h1>

<b>The `<meta>` tags in HTML provide metadata about the HTML document. Metadata is data (information) about data. `<meta>` tags always go inside the document's `<head>` tag and are typically used to specify the character set, page description, keywords, author, and other metadata.</b>

Below is an example HTML code snippet that includes various types of `<meta>` tags commonly used:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <!-- Character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Responsive design -->
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <!-- Internet Explorer compatibility -->
    <meta name="description" content="This is a description of the web page" />
    <!-- Description for search engines -->
    <meta name="keywords" content="HTML, CSS, JavaScript" />
    <!-- Keywords for search engines -->
    <meta name="author" content="Your Name" />
    <!-- Author name -->
    <title>Document</title>
  </head>
  <body>
    <!-- Your content here -->
  </body>
</html>
```

## Explanation of each meta tag:

1. **Character Encoding (charset):** <meta charset="UTF-8"> sets the character encoding for the webpage. UTF-8 is the most common and recommended.

2. **Viewport:** `<meta name="viewport" content="width=device-width, initial-scale=1.0">` sets the viewport to scale the page to the screen width, useful for responsive design.

3. **IE Compatibility:** `<meta http-equiv="X-UA-Compatible" content="ie=edge">` specifies that the page should be rendered using the latest rendering engine available on Internet Explorer.

4. **Description:** `<meta name="description" content="This is a description of the web page">` provides a brief description of the webpage, which search engines may use in search results.

5. **Keywords:** `<meta name="keywords" content="HTML, CSS, JavaScript">` specifies keywords for the webpage, which were historically used by search engines but are less relevant today.

6. **Author:** `<meta name="author" content="Your Name">` indicates the name of the author of the webpage.

## How to add favicon in HTML?

A favicon is a small icon that appears next to your website's title in browser tabs. It helps in branding and easy identification among multiple tabs.

![favicon-text](assets/favicon-text.png)

### Step 1: Create/Choose Favicon

Make a square image, usually 16x16 or 32x32 pixels, in .ico format. You can create a favicon from [this website](https://favicon.io/)

### Step 2: Upload Favicon

Place the .ico file in your website's root directory, where index.html is located.

### Step 3: Update HTML

Insert the following code in the `<head>` section of your index.html file:

```html
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```

Replace favicon.ico with your file's path if different.

### Step 4: Test

Open your site in different browsers to make sure the favicon appears.

## Conclusion

In summary, `<meta>` tags play a crucial role in providing essential metadata about an HTML document, enhancing its functionality and search engine visibility. From defining character encoding to specifying the author, each tag serves a unique purpose that contributes to the overall performance and accessibility of a webpage. Additionally, implementing a favicon helps in branding and improves user experience by making websites easily recognizable in browser tabs. By understanding and utilizing these elements effectively, web developers can create more efficient and user-friendly web pages.
