# HTMLStart

Sublime Text 3 snippet to generate an HTML5 boilerplate with all the essential elements to set up a simple web page, including Open Graph tags and favicons.

## Table of Contents

- [Content](#content)
- [Install](#install)
  - [Manual](#manual)
  - [Via Package Control](#via-package-control)
- [Usage](#usage)
- [Contribute](#contribute)

## Content

The snippet contains:

- The **recommend minimum** to make your document render properly on any device
- All **Open Graph** and **Twitter** tags to make your page sharable on every social network
- A complete reference to show your **favicon** on every browser and device
- Some sample **link and script** tags following best practices

## Install

### Manual

Fork, clone or directly download [the repository](https://github.com/gabrielecanepa/HTMLStart) and copy the file `htmlstart.sublime-snippet`.

In your terminal type

* On **macOS**

```bash
mkdir ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/Snippets && cd $_ && open .
```

* On **Linux/Windows**

```bash
mkdir ~/AppData/Roaming/Sublime\ Text\ 3/Packages/User/Snippets && cd $_ && open .
```

and **paste the file** in the opened directory.

### Via Package Control

In the command pallette (`⌘ Cmd` + `⇧ Shift` + `P` on Mac, `Ctrl` + `⇧ Shift` + `P` on Linux/Windows) type 'Install' and select `Package Control: Install Package` to see a list of available packages.

Search for `HTMLStart` and press enter again to install the package.

## Usage

In a new **blank HTML file** open the command palette, type 'html' and select `Snippet: HTMLStart`.

Another way to print the boilerplate is to digit `start` at the top of your blank HTML file and press `Tab ↹` on your keyboard.

That generates:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Recommend minimum -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta charset="UTF-8">
    <title>Page Title</title>
    <meta name="description" content="A description of the page.">
    <!-- Open graph -->
    <meta property="og:title" content="Page Title">
    <meta property="og:description" content="A description of the page.">
    <meta property="og:site_name" content="Website Name">
    <meta property="og:image" content="http://example.com/image.jpg"> <!-- 1200x630 recommended -->
    <meta property="og:url" content="http://example.com/page.html">
    <!-- Twitter cards -->
    <meta name="twitter:title" content="Page Title">
    <meta name="twitter:description" content="A description of the page.">
    <meta name="twitter:site" content="Website Name">
    <meta name="twitter:image:src" content="http://example.com/image.jpg"> <!-- 800x418 or 800x800 recommended -->
    <meta name="twitter:creator" content="Author Name">
    <meta name="twitter:card" content="card-name">
    <!-- Favicons (using realfavicongenerator.net, with package placed in images and arbitrary colors) -->
    <link rel="apple-touch-icon" sizes="180x180" href="images/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="images/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="images/favicon-16x16.png">
    <link rel="manifest" href="images/favicons/site.webmanifest">
    <link rel="mask-icon" href="images/safari-pinned-tab.svg" color="#5bbad5">
    <link rel="shortcut icon" href="images/favicon.ico">
    <meta name="msapplication-TileColor" content="#2b5797">
    <meta name="msapplication-config" content="images/browserconfig.xml">
    <meta name="theme-color" content="#ffffff">
    <!-- External resources and stylesheets -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato|Open+Sans">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-- Stylesheets -->
    <link href="style.css" rel="stylesheet">
  </head>

  <body>
    <!-- Page content -->

    <!-- External scripts -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.bundle.min.js"></script>
    <!-- Scripts -->
    <script src="script.js"></script>
  </body>
</html>
```

**Notes:**

Modify the content for your needs but **don't change the order** of the tags, that consistently ensure proper document rendering:
* the _recommend minimum_ must be present and comes first
* _stylesheets_ are linked at the bottom of the head and external libraries must be loaded first
* all _scripts_ are placed at the bottom of the body and external scripts come before

[↑ back to top](#htmlstart)
