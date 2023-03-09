In this part we will add some style to our portfolio website.

These are the colors used in the layout:

- Button color: `#845ec2`
- Primary text color: `#000`
- Secondary text color: `#6b7280`
- Card Border radius: `0.5rem`
- Button hover color: `#d65db1`

1. Add a `style.css` file to the `css` folder.
2. Add a `link` tag to the `head` of the `index.html` file to link the `style.css` file.
3. Add style to the navbar, try to apply properties to give it a shadow and spacing between the links and borders.
4. We can notice from the layout image that there are some elements which are side by side try to apply the correct properties to them.
5. Create a `card` and `button` class and try to apply properties to give it a shadow and spacing between the links and borders.
6. Try to apply the correct font properties to titles and paragraphs.

**suggestions:**

```CSS
.card {
  margin-bottom: 1.5rem;
  display: block;
  max-width: 24rem;
  border-radius: 0.5rem;
  border-width: 1px;
  border-opacity: 1;
  border-color: rgb(229 231 235 0.5);
  opacity: 1;
  background-color: rgb(255 255 255 0.5);
  padding: 1.5rem;
  box-shadow: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px 0 rgb(0 0 0 / 0.06);
}
```
