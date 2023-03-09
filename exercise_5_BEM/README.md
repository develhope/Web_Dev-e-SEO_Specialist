In this exercise you will refactor your SASS code to use BEM methodology.

**Suggestions:**

- Use the `&` selector to avoid repeating the parent selector.
- Use the **block** syntax for components.
- Use the **block\_\_element** syntax for elements inside a component.
- Use the **block\_\_element--modifier** syntax for modifiers of a component.

**Suggestions:**

```SCSS
.navbar {
  background-color: #333;
  overflow: hidden;
  position: fixed;
  top: 0;
  width: 100%;
  &__item {
    padding: 14px 16px;

    &--active {
      background-color: #111;
    }
  }
}
```
