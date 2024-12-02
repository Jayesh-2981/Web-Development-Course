<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">More on Forms</h1>

<b>HTML forms are the backbone of interactive websites. They allow users to submit data, which can be processed on the server. While we have covered basic input types in previous tutorials, this tutorial aims to delve deeper into form attributes, both common and new HTML5 additions. We'll also look at HTML5 validation attributes to ensure data integrity.</b>

## Common Attributes

### action

The action attribute specifies the URL where the form data should be sent after submission.

```html
<form action="/submit.php" method="POST"></form>
```

### method

The method attribute defines how data is sent. The two most common methods are GET and POST.

```html
<form action="/submit.php" method="POST"></form>
```

### name

The name attribute specifies the name for the form element, making it easier to reference in scripts or the server-side code.

```html
<input type="text" name="username" />
```

## New HTML5 Attributes

### placeholder

This attribute provides a hint to the user as to what can be entered in the field.

```html
<input type="text" placeholder="Enter your username" />
```

### required

The required attribute makes a field mandatory to fill out.

```html
<input type="text" required />
```

### autofocus

The autofocus attribute automatically focuses the cursor on the particular input when the page loads.

```html
<input type="text" autofocus />
```

## HTML5 Validation Attributes

### required

As mentioned above, this attribute makes a field mandatory.

```html
<input type="text" required />
```

### pattern

The pattern attribute specifies a regular expression that the input must match to be valid.

```html
<input type="text" pattern="[a-zA-Z0-9]+" />
```

## Conclusion

Understanding the different attributes available for HTML forms is crucial for building robust and user-friendly web applications. This tutorial covered both commonly used and new HTML5-specific attributes that enhance functionality and user interaction. Employing these attributes effectively will greatly enhance your web forms.
