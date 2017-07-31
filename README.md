# tableTotal jquery Plugin

Automatically add total row and/or total column to table.

## Installation

1. Include [jQuery](https://jquery.com/download/) on the page.
2. Include `jquery.tableTotal.js` on the page.

## Usage

### HTML

    <table id="totalMe">
      <thead>
        <tr>
          <th></th>
          <th>Q1</th>
          <th>Q2</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>North</th>
          <td>54</td>
          <td>14<td>
        </tr>
        <tr>
          <th>South</th>
          <td>24</td>
          <td>39</td>
        </tr>
      </tbody>
    </table>

### JS

    $('#totalMe').tableTotal();

## Options

### totalCol

Default: `true`

If `true`, adds a column to your table with row totals.

### totalRow

Default: `true`

If `true`, adds a row to your table with column totals.

### bold

Default: `true`

If `true`, makes all total numbers bold.

## Live Example

You can find a live example of this plugin in [this pen](https://codepen.io/travishorn/pen/Mvyyzz).
