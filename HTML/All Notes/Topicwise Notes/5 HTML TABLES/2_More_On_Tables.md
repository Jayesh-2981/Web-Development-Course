<style>
  body {
    text-align: justify;
  }
</style>

<h1 style="text-align: center;">More on Tables</h1>

<b>Let's take a closer look at HTML tables and delve into some more aspects of using tables in HTML.</b>

## Adding a Caption

To add a title to your table, you can use the `<caption>` element. This element helps both in terms of SEO and accessibility.

```html
<table>
  <caption>
    Student Details
  </caption>
  <!-- Rest of the table here -->
</table>
```

## Table Headers and Footers

Besides `<th>` for individual header cells, HTML tables allow you to group header or footer content using `<thead>` and `<tfoot>`.

```html
<table>
  <thead>
    <!--  header content -->
  </thead>
  <tfoot>
    <!-- footer content -->
  </tfoot>
  <tbody>
    <!-- body content -->
  </tbody>
</table>
```

## Column Groups

You can use the `<colgroup>` and `<col>` elements to apply styles to an entire column in an HTML table.

```html
<table>
  <colgroup>
    <col style="background-color:yellow" />
  </colgroup>
  <!-- rest of the table -->
</table>
```

## Accessibility in Tables

To make your tables more accessible, you can use the scope attribute in `<th>` elements to specify if they are headers for columns, rows, or groups of columns or rows.

```html
<th scope="col">Name</th>
<th scope="col">Age</th>
```

## Sample HTML Table

Here is an example HTML table with all the important elements:

```html
<table border="1">
  <!-- Caption -->
  <caption>
    Employee Information
  </caption>

  <!-- Table Header -->
  <thead>
    <tr>
      <th>ID</th>
      <th>Name</th>
      <th>Position</th>
      <th>Salary</th>
    </tr>
  </thead>

  <!-- Table Body -->
  <tbody>
    <tr>
      <td>1</td>
      <td>Alice</td>
      <td>Developer</td>
      <td>$80,000</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Bob</td>
      <td>Designer</td>
      <td>$70,000</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Carol</td>
      <td>Manager</td>
      <td>$90,000</td>
    </tr>
  </tbody>

  <!-- Table Footer -->
  <tfoot>
    <tr>
      <td colspan="3">Total Employees</td>
      <td>3</td>
    </tr>
  </tfoot>
</table>
```

## Conclusion

We've covered some advanced topics related to HTML tables in this blog. By using these features, you can create tables that are not only visually appealing but also highly functional and accessible. Stay tuned for more insights into HTML and web development!
