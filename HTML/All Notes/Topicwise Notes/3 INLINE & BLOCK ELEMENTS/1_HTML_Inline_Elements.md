<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">HTML INLINE ELEMETNS</h1>

- <b>Inline Elements don't start on a new line. It only takes the width required to cover the content.

- HTML elements are generally divided into two categories: Block-level and Inline elements.
  </b>

<img src="./assets/inline-block-image.jpg" alt="inline block image">

- No matter what the width is, block elements will always start on a new line and take up the full available width of their container by default.

- This means they essentially claim all the horizontal space for themselves, pushing any content that comes after them to a new line.

- But the inline elements will fit snugly within the flow of other elements, taking up only as much width as their content requires.

## What are Inline Elements?

- Inline elements do not start on a new line and only take up as much width as necessary. They are part of the flow within other elements.

- Inline elements can contain other inline elements, but they generally should not contain block-level elements. For example, you could nest a `<strong>` (strong emphasis) element within a `<span>` (a generic inline container) element, like so:

  ```html
  <span>This is <strong>important</strong> text.</span>
  ```

- However, placing a block-level element like a `<div>` or `<p>` inside an inline element like `<span>` or `<a>` is typically considered incorrect HTML and could lead to unexpected behavior in terms of layout and styling.

  ```html
  <!-- This is generally considered incorrect -->

  <span>
    This is
    <div>not recommended</div>
    text
  </span>
  ```

## Common Inline Elements

- `<span>`: A generic inline container for text
- `<a>`: Defines a hyperlink
- `<strong>`: Defines important text
- `<em>`: Defines emphasized text
- `<img>`: Embeds an image
- `<input>`: Defines an input control

## Examples

- Here is an example of using inline elements within a paragraph.

- This text contains [a link](), an **important text**, and an _emphasized text_.

## Styling Inline Elements

You can use CSS to style inline elements. However, some properties like width and height may not apply.

Here is an exhaustive list of the most used **Inline Elements:**

```html
<a> - Defines a hyperlink to navigate to another page or resource.
<abbr> - Represents an abbreviation with an optional <title> attribute for explanation.
<acronym> - Used for acronyms (obsolete in HTML5; use <abbr> instead).
<button> - Represents a clickable button.
<br> - Inserts a single line break.
<big> - Makes text larger than the surrounding text (obsolete in HTML5).
<bdo> - Overrides the current text direction (useful for right-to-left or left-to-right scripts).
<b> - Makes text bold, without adding semantic importance.
<cite> - Represents the title of a work (e.g., book, paper, etc.).
<code> - Denotes a block of computer code.
<dfn> - Indicates a definition term.
<i> - Italicizes text, often for technical or stylistic purposes.
<em> - Emphasizes text, typically rendered in italics.
<img> - Embeds an image into the document.
<input> - Defines a form control to collect user input.
<kbd> - Represents user input from a keyboard.
<label> - Associates a text label with a specific form element.
<map> - Defines a map with clickable areas on an image.
<object> - Embeds multimedia objects, such as videos, audio, or PDFs.
<output> - Represents the result of a calculation or user action.
<tt> - Displays text in a monospace font (obsolete in HTML5).
<time> - Represents a specific time or date.
<samp> - Represents sample output from a computer program.
<script> - Embeds or refers to JavaScript code.
<select> - Creates a drop-down list.
<small> - Displays text in a smaller font size.
<span> - A generic inline container for applying styles or grouping elements.
<strong> - Represents strong importance, usually rendered as bold.
<sub> - Represents subscript text.
<sup> - Represents superscript text.
<textarea> - Defines a multi-line text input field.
```

## Conclusion

Inline elements in HTML are essential for structuring content without disrupting the flow of text. Unlike block-level elements, which occupy the full width and start on a new line, inline elements only take up the space necessary for their content. They can contain other inline elements, but nesting block-level elements within them is generally discouraged. Understanding the characteristics and proper usage of inline elements is crucial for effective web design and development. Common inline elements include `<span>`, `<a>`, `<strong>`, and `<img>`, among others. Styling inline elements can enhance their appearance, but certain CSS properties may not apply as expected.
