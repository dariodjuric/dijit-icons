# Dojo/Dijit Icons

I haven't been able to find a list of available Dojo/Dijit button icon images with their respective classes, so I've compiled [this list](http://htmlpreview.github.io/?https://github.com/dariodjuric/dijit-icons/blob/master/icons.html). Regular icons are used as shown below:

    <button data-dojo-type="dijit/form/Button" data-dojo-props="iconClass: 'NAME_OF_CLASS'" type="button"></button>

Editor icons need to have one additional class, `dijitEditorIcon`:

    <button data-dojo-type="dijit/form/Button" data-dojo-props="iconClass: 'dijitEditorIcon NAME_OF_CLASS'" type="button"></button>