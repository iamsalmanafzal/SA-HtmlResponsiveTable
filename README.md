# SA Responsive Table
This is a jQuery and CSS based responsive table library.

## How to use

* Add `sa-table` class on the table
* Insert this table into a div element with class `table-container`
* To make a specific table non-responsive you can add `no-responsive` class with `sa-table` class

You final code will look like this:

```html
<div class="table-container">
  <table class="sa-table">
    <thead>
    <tr>
        <th>Heading 1</th>
        <th>Heading 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Content</td>
        <td>Content</td>
      </tr>
    </tbody>
  </table>
</div>
