# HTMLStart

Sublime Text 3 snippet to generate an HTML5 boilerplate with all the essential elements to correctly set your document, including Open Graph tags and favicons.

## Table of Contents

- [Content](#content)
- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)

## Content

The generate document contains:

- The _reccomend minimum_ to make the document work properly on any device, showing a title and a description of the page
- All the essential _Open Graph_ and _Twitter_ tags that enable any web page to become a rich object in a social context
- A complete reference that will help you show your _icon_ on every browser and device
- _Link and scripts_ sample tags (with minified Bootstrap and FontAwesome) following best practices to help the document load faster

## Install

In the command pallette (`⌘` + `⇧` + `P` on Mac) type 'Install' and press enter on `Package Control: Install Package` to see a list of packages.

Search for `HTMLStart`, then press enter again to install.

## Usage

With a blank HTML file open the command palette, type 'HTML' end press enter on `HTMLStart: Start a New Project`.

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
    <meta property="og:description" content="A description of the page">
    <meta property="og:site_name" content="Website Name">
    <meta property="og:image" content="http://example.com/image.jpg"> <!-- 1200x630 -->
    <meta property="og:url" content="http://example.com/page.html">
    <!-- Twitter Cards -->
    <meta name="twitter:title" content="Page Title">
    <meta name="twitter:description" content="A description of the page">
    <meta name="twitter:site" content="Website Name">
    <meta name="twitter:image:src" content="http://example.com/image.jpg">
    <meta name="twitter:creator" content="The author of the page">
    <meta name="twitter:card" content="card-name">
    <!-- Favicons (realfavicongenerator.net) with package placed in images/favicons -->
    <link rel="apple-touch-icon" sizes="180x180" href="images/favicons/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="images/favicons/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="images/favicons/favicon-16x16.png">
    <link rel="manifest" href="images/favicons/manifest.json">
    <link rel="mask-icon" href="images/favicons/safari-pinned-tab.svg" color="#5bbad5">
    <link rel="shortcut icon" href="images/favicons/favicon.ico">
    <meta name="msapplication-config" content="images/favicons/browserconfig.xml">
    <meta name="theme-color" content="#ffffff">
    <!-- Stylesheets and libraries -->
    <link type="text/css" rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link type="text/css" rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link type="text/css" rel="stylesheet" href="style.css">
  </head>

  <body>
    <!-- Scripts -->
    <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.bundle.min.js"></script>
    <script type="text/javascript" src="script.js"></script>
  </body>
</html>
```

## Contribute

[![GitHub forks](https://img.shields.io/github/forks/gabrielecanepa/HTMLStart.svg?style=social&label=Fork)](https://github.com/gabrielecanepa/HTMLStart/network) [![GitHub stars](https://img.shields.io/github/stars/gabrielecanepa/HTMLStart.svg?style=social&label=Star)](https://github.com/gabrielecanepa/HTMLStart/stargazers)

Feel free to send a pull request but only if you have a useful update, the boilerplate is designed to keep a practical, fast and simple use.

[![MIT Licensed](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=for-the-badge)](http://sloria.mit-license.org/)

[↑ back to top](#table-of-contents)
