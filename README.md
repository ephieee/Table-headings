# Table-headings

<th>
The <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) Even if a cell has no content, you should still use a <td> or <th> element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)Using <th> elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also enables you to control the appearance of tables better when you start to use CSS.You can use the scope attribute on the <th> element to indicate whether it is a heading for a column or a row. It can take the values: row to indicate a heading for a row or col to indicate a heading for a column.

<table>
 <tr>
  <th></th>
  <th scope="col">Saturday</th>
  <th scope="col">Sunday</th>
 </tr>
 <tr>
  <th scope="row">Tickets sold:</th>
  <td>120</td>
  <td>135</td>
 </tr>
 <tr>
  <th scope="row">Total sales:</th>
  <td>$600</td>
  <td>$675</td>
 </tr>
</table>
