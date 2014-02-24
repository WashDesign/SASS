# SASS
====

## SCSS Directory Structure and Files

* **Library (untouched)**
    * Defaults
    * **Base**
        * Forms
        * Tables
        * Headings
	      * Paragraphs
    * Helpers
    * Print 
    * Mixins
    * **Dependencies**   
        * Normalise
        * Grid-System
        * MQ
        * Mixin-library
        * Flex-slider
* **Objects** 
     * nav
     * media
     * button
     * icons
     * box
     * fonts
     * font-icons (possibly use true or false wrapper to not include sets)
* **Config** (project specific)
     * mq
     * colours
     * fonts/font-icon-set
     * defaults true:false
     * variables
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
