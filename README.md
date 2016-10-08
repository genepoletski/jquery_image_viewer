# jQuery plugin "jquery_image_viewer"
jQuery plugin for viewing images collection

## Usage
1. Load plugin ( with &lt;script&gt;, require() e.t.c.)
2. To add plugin functionality to a DOM structure simply use:
```javascript
$( 'container' )
  .tabbedImages({
    img_list : [ /* paths in string format */ ] // i.e. [ 'imgs/image01.jpg', 'imgs/image02.jpg' ]  
  });
```

## Plugin options
Edit plugin inner object configMap to setup plugin options or pass them on viewer initialization (see example above).

|           Option         |  Type  |            Description            |              Example              |
|--------------------------|--------|-----------------------------------|-----------------------------------|
| img_list                 | array  | images paths the array of strings | [ 'imgs/image01.jpg', 'imgs/image02.jpg' ] |

## Git pages

## Releases
1.0.0
