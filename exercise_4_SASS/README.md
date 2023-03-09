In this exercise you will refactor your CSS code to use SASS.

## Steps

1. Create a new folder called `exercise_4_SASS` and copy the `index.html` file from the previous exercise.
2. Create a new file called `style.scss` and copy the CSS code from the previous exercise.
3. Install the `node-sass` package.
4. Create a new script in the `package.json` file called `sass` which will compile the `style.scss` file to `style.css`.
5. Run the `sass` script and check that the `style.css` file is created.
6. Add the `style.css` file to the `index.html` file.
7. Run the `start` script and check that the website is working.
8. Refactor the CSS code to use SASS features.

**Suggestions:**

```SCSS
.navbar {
  background-color: #333;
  overflow: hidden;
  position: fixed;
  top: 0;
  width: 100%;
  .item {
    padding: 14px 16px;
  }
}
```
