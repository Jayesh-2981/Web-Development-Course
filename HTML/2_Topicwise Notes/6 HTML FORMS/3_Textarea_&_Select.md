<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">Textarea & Select</h1>

<b>In addition to the basic input types, HTML forms offer other controls like textarea and select for richer user interaction. These elements allow for more complex data collection and provide a better user experience. In this blog, we will dive into these form controls and provide examples.</b>

## The Textarea Element

The textarea element is used when you need multiline text input from the user. This is particularly useful for comments, reviews, or any other type of input where the length is unpredictable.

```html
<textarea name="comment" rows="4" cols="50">
      Enter your comment here...
</textarea>
```

The rows and cols attributes define the visible dimensions of the textarea.

## The Select Element

The select element creates a dropdown menu for the user. It is useful when you have a predefined list of options for the user to choose from.

```html
<select name="fruits">
  <option value="apple">Apple</option>
  <option value="banana">Banana</option>
  <option value="cherry">Cherry</option>
</select>
```

Each option inside the select tag represents an item in the dropdown list.

## Combining Textarea and Select

You can combine textarea and select in the same form to capture varied types of user input.

```html
<form action="/submit">
  <textarea name="comment" rows="4" cols="50">
Enter your comment here...</textarea
  >
  <select name="fruits">
    <option value="apple">Apple</option>
    <option value="banana">Banana</option>
    <option value="cherry">Cherry</option>
  </select>
  <input type="submit" value="Submit" />
</form>
```

## Output of textarea and select

[Video Demo](./assets/html-textarea.mp4)

## Conclusion

The textarea and select elements add another layer of interactivity to HTML forms, allowing for more complex and useful data collection. Understanding how to use these elements effectively can greatly enhance your web application's user interface.
