# SASS

This is the wash-pilot sass framework (pretty much a work in progress) but we have tried and tested inuit css and followed smacss. We found these great. As we develop sites in a particular way it seemed wholly approporiate to, whilst heavily influenced by the former, generate our own - based on our workflow.


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


## References

- https://github.com/csswizardry/inuit.css
- http://smacss.com/
