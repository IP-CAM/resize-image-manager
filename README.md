This is a vqmod for resize image manager in ocStore (OpenCart).

The module has been tested on ocStore version 1.5.5.1.2. 
Perhaps suitable for all versions of 1.5.x.

<strong>Installation</strong>:
- download and extract archive
- copy folder contents to your project
       
<strong>Resize</strong>:
<pre>
 - open a file admin/view/javascript/resize-image-manager.js
 - set values:
    ...
    imageResize: false,              // true - image resize, default false
    options: {
        heightBox: 550,              // image manager height, default 400px
        widthBox: "97%",             // image manager wight, default 800px
        widthLeftColumn: "12         // left column wight, default 20%
        widthRightColumn: "87%",     // right column wight, default 78%
        heightImage: 50              // image height, default 100x100px
    },                
</pre>
