# [Portfolio Site](https://seetacharan.github.io)


### Changing fonts
To get a new google font, you have to add a `<link>` to the `<head>` of the html file, and you have to update the css file so that the tags that you want to have that font get it. For example, if you were trying to change the `<h1>` tag to Google font Federo, your first step would be to either add or change the `<link>` in the html file to 

``` html
<link rel="stylesheet" href="https://fonts.google.com/specimen/Federo">
```

And to then, in the css file, add or change this in the `h1` section:

``` css
h1 {
	....
	....
	font-family: Federo;
}
```
