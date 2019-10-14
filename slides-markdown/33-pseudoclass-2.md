# Pseudo-classes

## LoVe HAte
```css
a:link    { color:#FF0000; } /* unvisited link */
a:visited { color:#00FF00; } /* visited link */
a:hover, a:focus   
          { color:#FF00FF; } /* mouse over or select with keyboard*/
a:active  { color:#0000FF; } /* selected link */
```

`a:hover` MUST come after `a:link` and `a:visited` in the CSS definition to be effective!

`a:active` MUST come after `a:hover` in the CSS definition to be effective!
