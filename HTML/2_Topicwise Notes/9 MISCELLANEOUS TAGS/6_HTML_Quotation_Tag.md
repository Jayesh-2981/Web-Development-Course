<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">HTML Quotation Tag</h1>

<b>The use of quotations is common in textual content. HTML provides specific tags to handle this: `<blockquote>` for block quotations and `<q>` for inline quotations. In this blog, we'll explore these tags, their attributes, and how to style them.</b>

## What Are `<blockquote>` and `<q>` Tags?

The `<blockquote>` and `<q>` tags serve to define quotations in HTML. While `<blockquote>` is used for longer, block-level quotes, `<q>` is used for shorter, inline quotes.

## Why Use These Tags?

They provide semantic meaning to your quotations, making it easier for search engines to understand the context and relevance of the content.

## Basic Syntax

### `<blockquote>` Tag

```html
<blockquote cite="source-url">Quotation text here.</blockquote>
```

### `<q>` Tag

## Attributes

Both `<blockquote>` and `<q>` tags support the cite attribute:

- **cite:** Specifies the URL of the quote's source.

## Practical Examples

### Using `<blockquote>` for Long Quotes

```html
<blockquote cite="https://example.com">
  This is a long quote from an external source. This quote can span multiple
  lines and paragraphs.
</blockquote>
```

### Using <q> for Short, Inline Quotes

```html
The philosopher said,
<q cite="https://example.com">The unexamined life is not worth living.</q>
```

## Styling with CSS

You can style these tags using CSS to better match the aesthetics of your website.

## Conclusion

The `<blockquote>` and `<q>` tags are essential for semantically marking up quotations in HTML. They provide both readability and SEO benefits. Understanding how to use these tags effectively can add more depth and clarity to your web content.
