In this exercise you will modify the generics HTML tags to semantic HTML tags of the previous exercise.

First of all add the tile tag and description meta tag to the head of the index.html file. Then you can also add the media query tag. Feel free to insert the open graph tags.

Try to apply the following tags:
- header
- nav
- main
- section
- footer

keep in mind 

**suggestion**

```HTML
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A portfolio website for a developer" />
  <meta name="keywords" content="HTML, CSS, JavaScript" />
  <meta name="author" content="John Doe" />
  <meta property="og:title" content="John Doe's Portfolio" />
  <meta property="og:description" content="A portfolio website for a developer" />
  <meta property="og:image" content="https://example.com/image.jpg" />
  <meta property="og:url" content="https://example.com" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:site" content="@example" />
  <meta name="twitter:creator" content="@john_doe" />
  <meta name="twitter:title" content="John Doe's Portfolio" />
  <meta name="twitter:description" content="A portfolio website for a developer" />
  <meta name="twitter:image" content="https://example.com/image.jpg" />
  <title>John Doe's Portfolio</title>
</head>

```HTML
<nav>
  <ul>
    <li>
      <a href="./projects.html">
        Projects
      </a>
    </li>
    <li>
      <a href="./about.html">
        About
      </a>
    </li>
    <li>
      <a href="./contact.html">
        Contact
      </a>
    </li>
  </ul>
</nav>