<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">HTML Ordered List</h1>

<b>An ordered list is a list of items that are arranged in a specific, sequential order. Each item in the list is usually numbered to indicate its position in the sequence. Ordered lists are commonly used when the sequence of the items is important, such as in step-by-step instructions or rankings.</b>

## Syntax

<img src="./assets/ordered-list-example.png">

## Key Points

- Ordered lists are used for items that follow a sequence.
- They are created using the `<ol>` (Ordered List) tag.
- List items are enclosed within `<li>` (List Item) tags.

## Basic Example

```html
<ol>
  <li>Mango</li>
  <li>Orange</li>
  <li>Litchi</li>
</ol>
```

### Output:

1. Mango
2. Orange
3. Litchi

## Setting the 'type' Attribute

The type attribute specifies the style of numbering. You have several options:

1. Uppercase Roman Numerals: Use type="I"
2. Lowercase Roman Numerals: Use type="i"
3. Arabic Numerals: Use type="1" (This is the default if the type attribute is not specified)
4. Lowercase Alphabetical Letters: Use type="a"
5. Uppercase Alphabetical Letters: Use type="A"

## Setting the 'start' Attribute

The start attribute specifies the starting number for the list.

```html
<ol type="A" start="3">
  <li>Pen</li>
  <li>Pencil</li>
</ol>
```

### Output:

3. Pen
4. Pencil

## Conclusion

In conclusion, ordered lists in HTML are a vital component for presenting information in a sequential manner. By using the `<ol>` and `<li>` tags, developers can effectively communicate steps, rankings, or any ordered data. Understanding the various attributes, such as `type` and `start`, allows for greater customization and enhances the overall user experience on web pages.
