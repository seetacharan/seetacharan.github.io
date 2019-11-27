# [Portfolio Site](https://seetacharan.github.io)


### Changing fonts
To get a new google font, you have to add a `<link>` to the `<head>` of the html file, and you have to update the css file so that the tags that you want to have that font get it. For example, if you were trying to change the `<h1>` tag to Google font Federo, your first step would be to either add or change the `<link>` in the html file to 

``` html
<link href="https://fonts.googleapis.com/css?family=Federo&display=swap" rel="stylesheet">
```
To get the link that should be added in to the document, go to [Google Fonts](https://fonts.google.com/), select the font you want by clicking the plus sign, then copy the embed link at the bottom of the page. The url that you have should start with `fonts.googleapis.com/css`, which means that you are pulling in Google's CSS file that contains the font.

And to then, in the css file, add or change this in the `h1` section:

``` css
h1 {
	....
	....
	font-family: Federo;
}
```
