# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #3: Inheritance

Child elements may inherit property values from their parent elements.

* `color`
* All the `font` declarations


```css
body {
  font-size: 1.2em;
  color: blue;
  width: 40rem;
}

p {
  /*
   * font-size: 1.2em;
   * color: blue;
   */
}
```


👍 Typography  
👎 Layout  
