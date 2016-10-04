# x - code - languages - html

## Base template

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>X</title>
    <meta name="description" content="X">
    <meta name="author" content="rspt">

    <link rel="stylesheet" href="css/styles.css?v=1.0">
  </head>

  <body>
    <script src="js/scripts.js"></script>
  </body>
</html>
```

## Social

In order to make your website displays nicealy on Facebook & Twitter, you can
add the following meta tags:

```html
<!--  Essential META Tags -->

<meta property="og:title" content="The title, headline or name of the object (max 70 char for Twitter).">
<meta property="og:description" content="A short description or summary of the object. [Between 2 and 4 sentences.] (max 200 char)">
<meta property="og:image" content="https://path/to/thumbnail.jpg">
<meta property="og:url" content="https://path/to/canonical/url.html">
<meta name="twitter:card" content="summary_large_image">


<!--  Non-Essential, But Recommended -->

<meta name="og:site_name" content="John Doe inc.">
<meta name="twitter:image:alt" content="Alt text for image">


<!--  Non-Essential, But Required for Analytics -->

<meta property="fb:app_id" content="your_app_id" />
<meta name="twitter:site" content="@website-username">
```

## Favicons

*   [Favicon Cheat Sheet](https://github.com/audreyr/favicon-cheat-sheet)

## Resources

*   [StackOverflow HTML Documentation](http://stackoverflow.com/documentation/html)
*   [HEAD](https://github.com/joshbuchea/HEAD) - A list of everything that goes
    in the `<head>` of your document
