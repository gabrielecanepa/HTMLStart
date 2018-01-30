# HTMLStart

Sublime Text 3 snippet to generate an HTML5 boilerplate with all the essential elements to correctly start your page, including Open Graph tags and favicons.

## Table of Contents

- [Content]
  - [Recommend minimum](#reccomend-minimum)
  - [Open Graph tags](#open-graph-tags)
  - [Twitter cards](#twitter-cards)
  - [Favicons](#favicons)
  - [Stylesheets and libraries](#stylesheets-and-libraries)
  - [Scripts](#scripts)
- [Install](#install)
  - [Manual](#manual)
  - [Via Package Control](#via-package-control)
- [Usage](#usage)
- [License](#license)

## Content

This boilerplate contains the essential elements to make the document work properly on any device and application:

- **Reccomend Minimum**


---

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML Boilerplate' then press enter to install.

## Usage

With a blank HTML file open, type

    htmlboiler

and press `TAB`.

That generates:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Recommend minimum -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Page Title</title>
    <meta name="description" content="A description of the page">
    <!-- Open graph -->
    <meta property="og:title" content="Page Title">
    <meta property="og:description" content="Page description">
    <meta property="og:site_name" content="Website name">
    <meta property="og:image" content="http://example.com/image.jpg"> <!-- 1200x630 -->
    <meta property="og:url" content="http://example.com/page.html">
    <!-- Twitter Cards -->
    <meta name="twitter:card" content="card_name">
    <meta name="twitter:site" content="Webasite name">
    <meta name="twitter:title" content="Page Title">
    <meta name="twitter:description" content="Page description">
    <meta name="twitter:creator" content="Creator name">
    <meta name="twitter:image:src" content="http://example.com/image.jpg">
    <!-- Favicons (realfavicongenerator.net) -->
    <link rel="apple-touch-icon" sizes="180x180" href="/images/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/images/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/images/favicon-16x16.png">
    <link rel="manifest" href="/images/manifest.json">
    <link rel="mask-icon" href="/images/safari-pinned-tab.svg" color="#5bbad5">
    <link rel="shortcut icon" href="/images/favicon.ico">
    <meta name="msapplication-config" content="/images/browserconfig.xml">
    <meta name="theme-color" content="#ffffff">
    <!-- Stylesheets and libraries -->
    <link type="text/css" rel="stylesheet" href="style.css">
  </head>

  <body>
    <!-- Scripts -->
    <script type="text/javascript" src="script.js"></script>
  </body>
</html>
```

[↑ back to top](#table-of-contents)

## License

[MIT Licensed](http://sloria.mit-license.org/).
