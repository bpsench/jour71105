# Tables
Tables are versatile, however, as a best practice, they should only be used to display tabular data in columns and rows, and not used for the grid layout of page components.

## Elements
To create an HTML table's columns and rows, use the following tags:

### `<table>`
Begins and ends the table.

### `<tr>`
Table Row begins and ends each row.

### `<th>`
Table Head is used for the table head row only.

### `<td>`
Table Data is used for each individual table cell.


## Example
Let's revisit the ordered list example, which is a ranking of US cities by population. To include the actual population figures, plus other related info such as state, it is best to use a data table.

```html
<table>
  <tr>
    <th>Rank</th><th>City</th><th>State</th><th>Population</th>
  </tr>
  <tr>
    <td>1</td><td>New York City</td><td>NY</td><td>8,622,698</td>
  </tr>
  <tr>
    <td>2</td><td>Los Angeles</td><td>CA</td><td>3,999,759</td>
  </tr>
  <tr>
    <td>3</td><td>Chicago</td><td>IL</td><td>2,716,450</td>
  </tr>
  <tr>
    <td>4</td><td>Houston</td><td>TX</td><td>2,312,717</td>
  </tr>
  <tr>
    <td>5</td><td>Phoenix</td><td>AZ</td><td>1,626,078</td>
  </tr>
</table>
```

## Result

<table>
  <tr>
    <th>Rank</th><th>City</th><th>State</th><th>Population</th>
  </tr>
  <tr>
    <td>1</td><td>New York City</td><td>NY</td><td>8,622,698</td>
  </tr>
  <tr>
    <td>2</td><td>Los Angeles</td><td>CA</td><td>3,999,759</td>
  </tr>
  <tr>
    <td>3</td><td>Chicago</td><td>IL</td><td>2,716,450</td>
  </tr>
  <tr>
    <td>4</td><td>Houston</td><td>TX</td><td>2,312,717</td>
  </tr>
  <tr>
    <td>5</td><td>Phoenix</td><td>AZ</td><td>1,626,078</td>
  </tr>
</table>

## Challenge
