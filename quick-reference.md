# Make Your Github Pages Site

1. Log into https://github.com
2. Click the + sign in the upper right hand corner and then click "new repository"
3. Name your repository [yourusername].github.io as in mjlavin80.github.io
4. Click the box to initialize the site with a README
5. Click the green "create repository" button

# Create index.html with basic page elements

1. Navigate to your repository and click "create new file"
2. In the "name your file" box, type "index.html"
3. In the "edit new file" field below the title, paste the following base markup with your "about me" paragraph

```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>[Your Name]'s Github Pages Site</title>
    </head>
    <body>
      <h1>[Your Name]'s Github Pages Site</h1>
      <nav>My Menu</nav>
      <main>
        <h2>About Me</h2>
        <p>[About me text here]</p>
      </main>
      <footer>
        My Footer
      </footer>
    </body>
  </html>
```

# Add a style.css file

1. Navigate to your repository and click "create new file"
2. In the "name your file" box, type "style.css"
3. Add a test rule to your css file, perhaps something like ``` h1 { color: lightgray; }
4. Navigate back to your repository and click the "index.html" file 
5. Locate and click the pencil incon, which will bring to an editor view
6. Paste the following line of code just before the ```html </head> ``` tag

```html
<link rel="stylesheet" type="text/css" href="style.css">
```

# Create your main menu
