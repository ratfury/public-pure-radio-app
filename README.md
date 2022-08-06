# public-pure-radio-app

## Description 

This project is for easy implementing a radio audio player for the famous pure ibiza radio into your own website. This project is done using Angular 14 and Webcomponents. All images and fonts are contained with Base64. The layouting is inspired by shadow-dom and element queries. But shadow-dom is only emulated.

It is possible to include it to your own site with two ways:

### 1. implement using div

Because this app is done using webcomponents it is possible to implement it using two essential lines:

<code>
 <player-widget></player-widget>
 <script type="text/javascript" src="app-player.js"></script>
</code>
Please see also the file widget.html and included.html for details. 

### 2. implement using iframe

Sometimes you need more flexibility. Therefore it is easy possible to include this project to your site with the iframe-tag.

<code>
    <body>
        <iframe src="widget.html" style="width:100vw; height:100vh border: none;">
        </iframe>
    </body>
</code>

Please see also the file index.html for details.



