# Documentation
The following CSS styles can be used to create Twitter-style elements:

# Button
This sample HTML code can be used to make a button.
```<button class="button">Button Text</button>```

# Image
This sample HTML code can be used to make an image/avatar

```<img src="avatar.jpg" alt="User Avatar" class="avatar">```

# List
This sample HTML code can be used to make a list.
```
<ul class="list">
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```
# Text
This sample HTML code can be used to make a piece of text.
```<p class="text">my name is skyler white yo.</p>```

# CSS
Import this code into your website for a Twitter-like look.
```
  <style>
:root {
  --twitter-blue: #1da1f2;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}

.button {
  display: inline-block;
  padding: 0.5rem 1rem;
  font-weight: 600;
  text-align: center;
  white-space: nowrap;
  background-color: var(--twitter-blue);
  color: #fff;
  border-radius: 9999px;
  transition: background-color 0.2s ease-in-out;
}

.button:hover {
  background-color: #0d8bf0;
  cursor: pointer;
}

.input-field {
  display: block;
  padding: 0.5rem;
  font-size: 1rem;
  border: 1px solid #ccd6dd;
  border-radius: 4px;
}

.avatar {
  display: inline-block;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
}

.text {
  font-size: 1rem;
  line-height: 1.5;
  color: #1c1e21;
}

.link {
  color: var(--twitter-blue);
  text-decoration: none;
  font-weight: 600;
  transition: opacity 0.2s ease-in-out;
}

.link:hover {
  opacity: 0.7;
}

  </style>
  ```
  # Reminder
  Please credit me if you're going to use this for a public project.
