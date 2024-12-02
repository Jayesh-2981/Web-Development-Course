<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">HTML Input Types</h1>

<b>Input types in HTML forms are the backbone of interactive web applications. They allow users to send information to web servers for various purposes like searching, logging in, or providing feedback. In this blog, we'll explore common HTML input types: text, password, radio, and checkbox.</b>

## Text Input

The text input type is the most basic form of input and is widely used for collecting simple text data.

```html
<input type="text" name="username" placeholder="Enter your username" />
```

In the above example, the placeholder attribute provides a hint to the user about what to enter.

## Password Input

The password input type is similar to the text type but hides the characters entered by the user for security reasons.

```html
<input type="password" name="password" placeholder="Enter your password" />
```

## Radio Buttons

Radio buttons are used when you want the user to select only one option from a set of choices.

```html
<input type="radio" id="male" name="gender" value="male" />
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female" />
<label for="female">Female</label>
```

## Checkbox

Checkboxes allow the user to select multiple options from a set.

```html
<input type="checkbox" id="subscribe" name="subscribe" value="yes" />
<label for="subscribe">Subscribe to newsletter</label>
```

## More input types

Here is a comprehensive list of input types you can use in html

<table border=1>
    <thead>
        <tr>
            <th>Input Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>text</td>
            <td>Allows the user to type a single line of text.</td>
        </tr>
        <tr>
            <td>password</td>
            <td>Allows the user to type a password.</td>
        </tr>
        <tr>
            <td>submit</td>
            <td>Represents a button that, when pressed, submits the form.</td>
        </tr>
        <tr>
            <td>reset</td>
            <td>Represents a button that, when pressed, resets all the form controls to their initial values.</td>
        </tr>
        <tr>
            <td>radio</td>
            <td>Represents an option in a set of options that are mutually exclusive with each other.</td>
        </tr>
        <tr>
            <td>checkbox</td>
            <td>Represents an option in a set that may be selected independently of other options.</td>
        </tr>
        <tr>
            <td>button</td>
            <td>Represents a clickable button.</td>
        </tr>
        <tr>
            <td>color</td>
            <td>Allows the user to select a color.</td>
        </tr>
        <tr>
            <td>date</td>
            <td>Allows the user to select a date.</td>
        </tr>
        <tr>
            <td>datetime-local</td>
            <td>Allows the user to select a date and time with no time zone.</td>
        </tr>
        <tr>
            <td>email</td>
            <td>Allows the user to enter an email address.</td>
        </tr>
        <tr>
            <td>file</td>
            <td>Allows the user to select one or more files from their device storage.</td>
        </tr>
        <tr>
            <td>hidden</td>
            <td>Represents a value that is not displayed but is submitted to the server.</td>
        </tr>
        <tr>
            <td>image</td>
            <td>Defines an image that acts as a submit button.</td>
        </tr>
        <tr>
            <td>month</td>
            <td>Allows the user to select a month and year.</td>
        </tr>
        <tr>
            <td>number</td>
            <td>Allows the user to enter a number.</td>
        </tr>
        <tr>
            <td>range</td>
            <td>Allows the user to select a number from a range.</td>
        </tr>
        <tr>
            <td>search</td>
            <td>Allows the user to enter a search query string.</td>
        </tr>
        <tr>
            <td>tel</td>
            <td>Allows the user to enter a telephone number.</td>
        </tr>
        <tr>
            <td>time</td>
            <td>Allows the user to select a time.</td>
        </tr>
        <tr>
            <td>url</td>
            <td>Allows the user to enter a URL.</td>
        </tr>
        <tr>
            <td>week</td>
            <td>Allows the user to select a week.</td>
        </tr>
    </tbody>
</table>

## Conclusion

Understanding the different types of HTML input is crucial for creating interactive and user-friendly forms. Each input type serves a specific purpose, making it easier to collect, validate, and process user data.
