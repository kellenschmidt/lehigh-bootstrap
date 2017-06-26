# Lehigh Bootstrap

[![Stories in Ready](https://badge.waffle.io/Thakugan/LehighBootstrap.png?label=ready&title=Ready)](https://waffle.io/Thakugan/LehighBootstrap?utm_source=badge)

This is an extension for Bootstrap written in Sass. It was created to be used in the new design for Lehigh Hanson's portal and mobile apps.

## Installation

To just be able to use this extension, download the lehigh-bootstrap.min.css file from /dist/css.

In order to make edits, clone the repository and make any desired changes to the .scss files under the scss folder. To compile and minify the sass files, cd into the cloned repository and run in the command line:

```
npm install
grunt
```

## Usage

Add this into the `<head>` tag of your main html page.

```
  <link rel="stylesheet" href="./dist/css/lehigh-bootstrap.min.css">
```

To get the font, Montserrat, either download the font or add this to the `<head>` tag.

```
  <link href="https://fonts.googleapis.com/css?family=Montserrat:300,300i,400,500,700" rel="stylesheet">
```
