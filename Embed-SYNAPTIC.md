# Quotehaven Documentation

## Embedding on a site

Quotehaven can be embedded on to most modern websites by including some HTML, CSS, and JavaScript on the website. Please follow the steps below to embed onto a website.

### 1. Add the domain of the website to your Quotehaven site's whitelist of domains 

This should have already been setup at this stage, but if it hasn't - please get in touch at support@codepotato.co.uk or if you are the account owner, sign into Quotehaven and head to the Settings page.

### 2. Add your Quotehaven site's styles and scripts to the <head> tag of your website

Add the following two lines before the closing `</head>` tag on the page you would like Quotehaven's form to be rendered on. **Make sure to replace "ENTER-YOUR-CODE-HERE" with the ID that Quotehaven provides when you whitelist your site.**

```html
<link rel="stylesheet" href="https://webline.quotehaven.co.uk/css/embed.css">
<link rel="stylesheet" href="https://webline.quotehaven.co.uk/e/css?id=ENTER-YOUR-CODE-HERE">
<script src="https://webline.quotehaven.co.uk/e/js?id=ENTER-YOUR-CODE-HERE"></script>
```

### 3. Add Quotehaven's additional base styles and scripts just before the </body> tag of your website

Add the following script just before the closing `</body>` tag on your website

```html
<script src="https://webline.quotehaven.co.uk/js/embed.js"></script>
```

### 4. Finally, place the following HTML code where you would like the quote form to be rendered.

```html	
<div id="quotehaven_app"></div>
```
