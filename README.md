##Resize Image Manager (RIM).
---
####This is a modification for ocStore(OpenCart) allows you to resize Image Manager and pictures.

Tested on ocStore version 1.5.5.1.2. 

Perhaps suitable for all versions of 1.5.x.

**Installation**

       - to work needed installed vqmod
       - download and extract archive
       - copy folders contents to your project
----
**Resize**

Edit a file admin/view/javascript/resize-image-manager.js
```
       ...
       imageResize: false,          // true - enable resize image, default false
       options: {
              heightBox: "550px",   // image manager height, default 400px
              widthBox: "97%",      // image manager wight, default 800px
              ...
              heightImage: "50px"   // image height, default 100x100px (ignore if imageResize is false)
       },
```
---
**Uninstall**

For a full removal you need remove files: 

       - admin/view/javascript/resize-image-manager.js
       - vqmod/xml/resize-image-manager.xml
