#  CSS selectors

## Just _some_ of this type of element


Most of the time we don't want _all_ the elements of a certain type, but only the ones that are in a particular part of the page.

We can specify this by creating a "filter" of our selectors.

<!-- ![DOM node tree](images/DOM-tree-2.png) -->

> "Find an `<em>` element  
inside a link  
inside a list item  
in an unordered list."

```css
ul li a em {
  color: purple;
}
```

### Note
* We can skip the `li` because it will always be there.
* The CSS selector doesn't need to refer to the _full_ DOM hierarchy.
In fact, it **shouldn't**!
