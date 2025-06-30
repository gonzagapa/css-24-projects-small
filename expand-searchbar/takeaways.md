# Search bar project

Things that I learned

- Use the property **outline-offset** to draw the outline beyond the bordge edges.

- Make sure that your placeholder text has more color contrast with:

```css
::-moz-placeholder {
  color: #333;
  opacity: 1;
}

::-webkit-input-placeholder {
  color: #333;
}
```

- Every input should have a label tag.

- Code snippet to hide text

```css
.hiden {
  clip-path: rect(0 0 0 0);
  border: 0;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  position: absolute;
}
```
