# HTMLStart

Sublime Text 3 snippet to generate an HTML5 boilerplate with all the essential elements to correctly set your document, including Open Graph tags and favicons.

## Table of Contents

- [Content](#content)
- [Install](#install)
  - [Manual](#manual)
  - [Via Package Control](#via-package-control)
- [Usage](#usage)
- [Contribute](#contribute)

## Content

The generate document contains:

- The **reccomend minimum** to make the document work properly on any device and show a title and a description of the page
- All the essential **Open Graph** and **Twitter** tags that enable any web page to become a rich object in a social context
- A complete reference that will help you show your **favicon** on every browser and device
- Some sample **link and script** tags (with minified _Bootstrap_ and _FontAwesome_ included) following best practices to help your document load faster

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

and **paste the file** in the directory.

### Via Package Control

In the command pallette (`⌘ Cmd` + `⇧ Shift` + `P` on Mac, `Ctrl` + `⇧ Shift` + `P` on Linux/Windows) type 'Install' and press enter on `Package Control: Install Package` to see a list of available packages.

Search for `HTMLStart`, then press enter again to install.

## Usage

In a new **blank HTML file** open the command palette, type 'HTML' end press enter on `Snippet: HTMLStart`.

Another way to print the boilerplate is to digit `HTMLStart` at the top of a blank HTML file and press `Tab ↹` on your keyboard.

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
    <meta property="og:image" content="http://example.com/image.jpg"> <!-- 1200x630 -->
    <meta property="og:url" content="http://example.com/page.html">
    <!-- Twitter Cards -->
    <meta name="twitter:title" content="Page Title">
    <meta name="twitter:description" content="A description of the page.">
    <meta name="twitter:site" content="Website Name">
    <meta name="twitter:image:src" content="http://example.com/image.jpg"> <!-- 800x418 or 800x800 -->
    <meta name="twitter:creator" content="Author Name">
    <meta name="twitter:card" content="card-name">
    <!-- Favicons (using realfavicongenerator.net, with package placed in images/favicons) -->
    <link rel="apple-touch-icon" sizes="180x180" href="images/favicons/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="images/favicons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="images/favicons/favicon-16x16.png">
    <link rel="manifest" href="images/favicons/site.webmanifest">
    <link rel="mask-icon" href="images/favicons/safari-pinned-tab.svg" color="#5bbad5">
    <link rel="shortcut icon" href="images/favicons/favicon.ico">
    <meta name="msapplication-TileColor" content="#2b5797">
    <meta name="msapplication-config" content="images/favicons/browserconfig.xml">
    <meta name="theme-color" content="#ffffff">
    <!-- External libraries -->
    <link href="https://fonts.googleapis.com/css?family=Lato|Open+Sans" rel="stylesheet">
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <!-- Stylesheets -->
    <link href="style.css" rel="stylesheet">
  </head>

  <body>

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
* the _reccomend minimum_ must be present and comes first
* _stylesheets_ are linked at the bottom of the head and external libraries must be loaded first
* all the _scripts_ are placed at the bottom of the body and external scripts come before

## Contribute

[![MIT Licensed](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=for-the-badge)](http://sloria.mit-license.org/)

[↑ back to top](#htmlstart)
