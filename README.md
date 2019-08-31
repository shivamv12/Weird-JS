# Weird Behavior of JS
<div style="text-align:center;">
<img src="https://i.ytimg.com/vi/F08X6uEifFU/maxresdefault.jpg" height="300px" width="100%"><br/><br/>
</div>
<p>We all know that JavaScript is quite a funny language with tricky parts. Some of them can quickly turn our everyday job into hell, and some of them can make us laugh out loud. Here, I am going to make collection of some javascript weird problems &amp; questions. Which you even can't think about.</p>
<br/><br/>
<table>
  <thead><tr><th>Sr. No.</th><th>Question</th></tr></thead>
  <tbody>
    <tr><td>1.</td><td>console.log([ ] === [ ]);
      <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR<br/>
      console.log([ ] == [ ]);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      returns <b>FALSE</b>.</td></tr>
    <tr><td>2.</td><td>let a = {'name' : 'Shivam'}<br/>
      let b = a;<br/>
      b.name = 'Sam';<br/>
      console.log(a.name);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Guess Output : <b>Sam or Shivam?</b>
      </td></tr>
    <tr><td>3. </td><td>typeof <b>undefined</b>;
      <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR<br/>typeof(<b>undefined</b>);
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Output : <b>undefined</b></td></tr>
    <tr><td>4. </td><td>typeof <b>null</b>;<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      OR<br/>typeof(<b>null</b>);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output : <b>object</b></td></tr>
    <tr><td>5. </td>
      <td>typeof <b>String</b>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      typeof(<b>String</b>);<br/>AND<br/>
      typeof <b>Number</b>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      typeof(<b>Number</b>);<br/>AND<br/>
      typeof <b>Object</b>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      typeof(<b>Object</b>);<br/>AND<br/>
      typeof <b>Boolean</b>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      typeof(<b>Boolean</b>);<br/>AND<br/>
      typeof <b>Function</b>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      typeof(<b>Function</b>);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Output : <b>Function</b></td></tr>
    <tr><td>6. </td><td>['1', '7', '11'].map(parseInt);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Can you guess the <b>Output</b>?</td></tr>
    <tr><td>7. </td><td>console.log(0.2 + 0.1 === 0.3);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Can you guess the <b>Output</b>?</td></tr>
    <tr><td>8. </td><td>
      console.log(Math.max() > Math.min());&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Output : <b>True</b> or <b>False</b>?
      </td></tr>
    <tr><td>9. </td><td>
      console.log(018 - 017);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      Can you guess the <b>Output</b>?</td></tr>
    <tr><td>10. </td><td>
      Have you ever hear about the <b>"Bang Bang Operator" (!!)</b> in JS?
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <a href="https://medium.com/better-programming/javascript-bang-bang-i-shot-you-down-use-of-double-bangs-in-javascript-7c9d94446054" target="_blank">Answer</a></td></tr>
    <tr><td>11. </td><td><b><i>Write a JS function to take any number of Arguments.</b></i><br/><br/>
      function add(...args) {<br/>
      &nbsp;&nbsp;let result = 0;<br/>
      &nbsp;&nbsp;for (let arg of args)<br/>
      &nbsp;&nbsp;&nbsp;&nbsp;result += arg;<br/>
      &nbsp;&nbsp;console.log(result);<br/>
      }<br/>
      add(1) // returns 1<br/>
      add(1,2) // returns 3<br/>
      add(1, 2, 3, 4, 5) // returns 15<br/>
      </td></tr>
    <tr><td>12. </td><td>What are Spread Operators?</td></tr>
  </tbody>
</table>
