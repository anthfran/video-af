# \<video-af\>

Custom Polymer HTML element that displays HTML5 Video with Material Design controls
by Anthony Francella

## Demo

https://www.webcomponents.org/element/anthfran/video-af/demo/demo/index.html

## Installation

`bower install --save anthfran/video-af`

## Usage

### Include this custom element
`<link rel="import" href="../bower_components/video-af/video-af.html">`

### Add to your app
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="video-af.html">
    <next-code-block></next-code-block>  
    </template>
</custom-element-demo>
```
-->
```html
<video-af
  video-url={
  "720p":"black_coffee_720p.mp4",
  "360p":"black_coffee_360p.mp4"}
  poster-url="black_coffee.jpg">
</video-af>
```
