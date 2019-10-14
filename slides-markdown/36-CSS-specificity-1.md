# Conflicting rules

a.k.a. Why is my CSS not working?!

## Reason #2: Specificity

In the following example, which colour will the paragraphs be?

```html
<p id="first" class="important">Paragraph number 1.</p>
<p class="important">Paragraph number 2.</p>
<p class="important">Paragraph number 3.</p>
```


```css
#first {
  color: red;
}

p.important {
  color: green;
}

p {
  color: blue;
}
```

Answer:
1. Red
2. Green
3. Green
