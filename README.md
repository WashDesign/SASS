# SASS
====

## SCSS Directory Structure and Files

* **Library (untouched)**
    * Defaults
    * **Base**
        * Global
        * Headings
        * Paragraphs
	* Blockquotes
	* Images
	* Forms
	* Lists
	* Tables
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
     * font-icons
* **Config** (project specific)
     * setup true:false
     * mq
     * variables (colours, fonts/font-icon-set)
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
     * ext-forms (example)
     * ext-button (example)
     * ext-font-icon
* **Themes** (colour themes)
     * site-themes 
     * page-themes
     * module-themes
* **Overrides**
     * make use of the cascade  
