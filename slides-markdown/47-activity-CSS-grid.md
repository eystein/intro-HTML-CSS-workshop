### Activity 14

# Layout with CSS Grid

Continue with your own template, or create a new one if you like, or clone one - mine or anyone else's.

Example of setup. Try be a bit more creative with the layout than what I've been here! 😀

```css
body {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: auto;
  grid-template-areas:
    "header header header"
    "main main sidebar"
    "footer footer footer";
}

header { grid-area: header;  }
main   { grid-area: main;    }
aside  { grid-area: sidebar; }
footer { grid-area: footer;  }
```

CodePen example: [bit.ly/a14-css-grid](http://bit.ly/a14-css-grid)
