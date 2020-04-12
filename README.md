# dark-gist

Display your gist in dark theme by adding `full-dark-gist` or `semi-dark-gist` class to parent or root element. 
# Using on white background
If you want use this styles on light background I would suggest you to add this css class in your styles, it improves visibility of Gist
```css
.gist .gist-file{
  background-color: black !important;
  border-color: black !important;
}
```
# Supportend languages
- HTML 
- JS
- CSS

# Example

Download and add css file to document:

```html
  <link rel="stylesheet" href="darkGist.css">

  <!-- min version -->
  <link rel="stylesheet" href="darkGist.min.css">
```
And now add to root or parent element of gist one of the given classes: 
`full-dark-gist`
![full-dark-gist](https://i.imgur.com/XkmWKYb.png)
or:
`semi-dark-gist`
![semi-dark-gist](https://i.imgur.com/OQNRBWO.png)