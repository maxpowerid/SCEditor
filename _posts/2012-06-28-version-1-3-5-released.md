---
layout: release
title: Version 1.3.5 released
excerpt: Details of the 1.3.5 release
tags: [releases, 1.3.5]
categories:
    - releases
---
## Version 1.3.5

The biggest change in this update is the themes. All the themes now live in their own directory and [3 news ones have been added](/posts/themes-demo/).

Some extra options have also been added like readOnly, autofocus, trl and id.

There are also quite a few small changes in this update like the addition of sourceMode, val, insertText and insert methods.

### Full 1.3.4 changelog:
 * Fixed bug in FF making pasting via right click difficult when empty - Thanks to Nibogo2 for reporting
 * Added readonly method and option
 * Added expandToContent method
 * Reorgernised themes to their own directory.
 * hanged themes to be in .less format and added to build file
 * Added modern, office-toolbar and office themes
 * Added autofocus option
 * Added a roadmap to the GitHub wiki
 * Added height and width methods
 * Added method to check for WYSIWYG support
 * Changed so that by default the editor won't start in browsers that do not support WYSIWYG editing (old mobile browsers)
 * Added rtl option along with rtl & ltr commands
 * Added id option
 * Added sourceMode, val, insertText and insert methods
 * Fixed quote bug where author from nested quotes would be removed
 * Added Estonian language file - Thanks to Rivo for translating
 * Fixed bug with dom.fixNesting when fixing certain tags
 * Improve adding/updating/removing of commands and BBCodes
 * Fixed bug causing elements that are styled with diplay: block to be treated as block level elements - Thanks to Rene for reporting
 * Added Brazilian Portuguese language file - Thanks to Martec for translating
