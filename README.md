LeapJS Plugins
==============

This repository holds a collection of independent plugins which extend the functionality of LeapJS itself.

Here is an example showing the usage of the plugin hand-entry, which emits an event when a hand enters or leaves
the view.  Include a new version of leapjs and the plugin.  Then configure your controller to use the plugins, and
additional functionality will be available to you.  See [hand-entry](hand-entry) for details.

```html
<!-- your index.html -->
<script type="text/javascript" src="js/leap-0.4.0.js"></script>
<script type="text/javascript" src="js/lib/leap.hand-entry.js"></script>
<script type="text/javascript">
  var controller = new Leap.Controller();
  controller.use('handEntry')
</script>
```


 - Each plugin is individually documented, with demo, on the [gh-pages](gh-pages).
 - See [making plugins](making plugins) on the leapjs wiki.



Contributing
===============

 - Contact [@LeapmotionDev](https://twitter.com/LeapMotionDev) for help
 - [SDK License](SDK License)