# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #1: Because the C in CSS is for Cascade

In the following example, which colour will the paragraphs be?

```html
<p>Paragraph number 1.</p>
<p>Paragraph number 2.</p>
<p>Paragraph number 3.</p>
```


```css
p {
  color: red;
}

p {
  color: green;
}

p {
  color: blue;
}
```


### "Cascade"

* The order of CSS rules matter.
* When two rules apply that have equal specificity the one that comes _last_ in the CSS is the one that will be used.

Rules lower in the file overwrite rules higher in the file.
