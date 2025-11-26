# sf-portalgroup
Strategic Factory portal functions.

## Setting up a new portal
1. Add the necessary scripts to the "Other Metadata" section of the Site Header settings. At a minimum, you will need jQuery and the initialize.js file. Note: make sure you use a numbered version of each script!!! If you do not do this, any changes that are made to the scripts will break your site.
```
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/jstjames-sf/sf-portalgroup/src/initialize.js"></script>
```
2. **Favicon:** Choose an image to serve as the favicon (browser tab icon). If larger than 192x192, scale it down to those dimensions, and save as PNG. Upload to the File Uploader (in the /con directory).

## Future code improvements
* Overhaul for the shipping page; items table is very difficult to read on mobile. Would probably benefit from being laid out as something other than a table.