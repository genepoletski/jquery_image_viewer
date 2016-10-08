# jQuery plugin "jquery_image_viewer"
jQuery plugin for viewing images collection

## Usage
1. Load plugin ( with &lt;script&gt;, require() e.t.c.)
2. To add plugin functionality to a DOM structure simply use:
```javascript
$( 'container' )
  .imageViewer(
    img_paths: [ /* paths in string format */ ], // i.e. [ 'imgs/image01.jpg', 'imgs/image02.jpg' ]         
    main_img_height: 500                         // main image placeholder height in pixels 
  );
```

Edit plugin inner object configMap to setup plugin options or pass them on viewer initialization (see example above).

## Git pages
https://web-developer-poletski.github.io/jquery_image_viewer/

## Releases
1.0.0 https://github.com/web-developer-poletski/jquery_image_viewer/releases/tag/v1.0.0
