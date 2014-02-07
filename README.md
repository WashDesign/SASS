SASS
====

SCSS Directory Structure and Files

* **Library (untouched)**
    * Reset
    * Base
    * Helpers
    * Print
    * Mixins
    * **Dependencies**   
        * Grid-System
        * MQ
        * Mixin-library
* **Objects** (OOCSS - possible could sit in library but i think warrants not doing for now - we arent mature enough in this area yet)
     * nav
     * button
     * icons
     * box
     * font-icons (possibly use true or false wrapper to not include sets)
* **Config** (project specific)
     * mq
     * colours
     * fonts/font-icon-set
     * defaults true:false (amy be nice to strip out or pull in relevant libraries e.g. grid = true/false)
* **Styles**
     * global (body, links, wrapper)?
     * header
     * navs
     * main
     * aside
     * footer
     * page-gallery (match template hierarchy?)
     * page-contact-us (match template hierarchy?)
     * **Modules**
          * slider
          * gallery
* **Extensions** (extensions to library or objects that aren't content related)
     * forms-ext (example)
     * button-ext (example)
     * font-icon-ext
* **Themes** (colour themes)
     * page-theme
     * module-theme
