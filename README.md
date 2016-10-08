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

## Plugin options
Edit plugin inner object configMap to setup plugin options or pass them on viewer initialization (see example above).

|           Option         |  Type  |      Description        |              Example              |
|--------------------------|--------|-------------------------|-----------------------------------|
| main_img_height          | number | main image height in px | 300 |
| main_img_loading_content | string | path to 'loading'\* image in CSS style | 'url(js/libs/jquery/loading.gif)' |
| thumb_img_height         | number | thumbnail image height in px | 100 |
| thumb_img_opacity        | number | thumbnail image opacity | 0.3 |
_(*) 'loading' image is being displayed during fetching main image from URI_

## Git pages
https://web-developer-poletski.github.io/jquery_image_viewer/

## Releases
1.0.0 https://github.com/web-developer-poletski/jquery_image_viewer/releases/tag/v1.0.0
