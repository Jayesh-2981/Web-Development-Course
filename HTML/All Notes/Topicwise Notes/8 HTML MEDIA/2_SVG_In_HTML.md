<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">SVG in HTML</h1>

<b>Scalable Vector Graphics (SVG) has become an indispensable part of modern web development. SVG enables developers to create high-quality, scalable graphics that look crisp at any size or resolution. In this blog post, we'll explore the basics of using SVG in HTML, its benefits, and some practical examples.</b>

## What is SVG?

SVG stands for Scalable Vector Graphics. Unlike raster images like PNGs or JPGs, SVGs are not pixel-based. They're composed of vectors—mathematical formulas that describe shapes, paths, and fills. This means SVGs can be resized without losing quality.

## Why Use SVG?

**Scalability:** SVG images can be scaled indefinitely without losing quality, which is ideal for responsive web design.

**File Size:** SVG files are often smaller than their raster counterparts, especially for simple shapes and icons.

**Flexibility:** SVGs can be styled, animated, and manipulated using CSS and JavaScript.

## How to Embed SVG in HTML

SVG can be embedded in HTML in several ways:

1. **Inline SVG:** Directly writing the SVG XML code within HTML.

   ```html
   <svg height="100" width="100">
     <circle
       cx="50"
       cy="50"
       r="40"
       stroke="black"
       stroke-width="3"
       fill="red"
     />
   </svg>
   ```

2. Using an **`<img>` tag:** Point the src attribute to an SVG file.

   ```html
   <img src="image.svg" alt="Sample SVG" />
   ```

3. Using **CSS:** Setting SVG as a background image in a CSS file.
   ```css
   .background {
     background-image: url("image.svg");
   }
   ```

## Creating a Simple Icon

```html
<svg height="30" width="30">
  <rect
    width="30"
    height="30"
    style="fill:rgb(0,0,255);stroke-width:1;stroke:rgb(0,0,0)"
  />
</svg>
```

## Creating Complex Shapes

SVG can also be used to create more complex shapes like polygons, lines, and text.

## Conclusion

SVG offers a powerful way to add scalable and interactive graphics to your HTML documents. Its compatibility with CSS and JavaScript makes it a versatile choice for modern web development. Whether you're creating simple icons or intricate illustrations, SVG has got you covered.
