#Remarkable
###Change Log (written using Remarkable!)

[Remarkable homepage](http://remarkableapp.github.io)

[Remarkable repository](http://github.com/jamiemcg/remarkable) 

**Version 1.95 (21/09/2024)**

- Updated dependencies for 2024
- Tested on Ubuntu 24.04 LTS
- Rewrote/fixed remarkable markdown extensions to work with newer version of python-markdown
- Synchronised scrolling is still broken!

**Version 1.9**

Not packaged.

**Version 1.87**

- **New**: Syntax Highlighting for markdown in editor pane
- **New**: Horizontal Layout
- **New**: Display line numbers
- **New**: Join and Sort lines
- **New**: Paste Images (thanks to **@pkorpine**)
- **New**: Built in markdown tutorial (Help -> Markdown Tutorial)
- **Improved**: Now launches new Remarkable process when opening/creating files
- **Improved**: Styles (syntax highlighting in darker themes)
- **Fix**: Settings file bug

**Version 1.75**

- **Fix**: Fix startup crash error on Ubuntu 16.04 and other distros
- **New**: Local path image support (buggy)
- **New**: Change GitHub repository https://github.com/jamiemcg/Remarkable
- **Misc**: Bug fixes


**Version 1.62**

- **New**: Update to reflect domain change -> remarkableapp.github.io

**Version 1.61 (29/06/15)**

- **Fix**: scrolling bug (finally!) ->oldest bug!
- **Fix**: tooltip error
- **Fix**: icon compatibility (this time!)
- **New**: now remembers and applies the last chosen style on launch
- **Improved**: much quicker (especially on startup)
- **Improved**: generally more stable
- **Fix**: misc fixes

**Version 1.41 (19/04/15)**

- **Fix**: fixed PDF export (again)
- **Fix**: fixes errors regarding python-markdown
- **Fix**: general stability/compatibility improvements
- **New**: now shows if a file has been saved or not
- **ERR**: ~~icon now compatibile with icon themes~~
- **New**: changed versioning scheme

**Version 1.25 (08/02/15)**

- **New**: added ability to change editor font
- **New**: added TOC feature
- **Improved**: improved compatibility
- **Fix**: added some code to prevent simple crashes

**Version 1.025 (04/02/15)**

- **New**: added MathJax support (slightly buggy)
- **New**: added support for local images
- **New**: export PDF without CSS
- **New**: export HTML without CSS
- **New**: preview externally


**Version 0.975 (05/09/14)**

- **Improved**: loading of user settings
- **New**: convert selected text to lowercase, titlecase, uppercase
- **New**: copy selection to clipboard as HTML
- **New**: copy all to clipboard as HTML
- **Fix**: Python-Markdown issue is now fixed. Should work on all most all machines, issue was due to a Python-Markdown update that wasn't backward compatible with current third-party extensions
- **Fix**: Javascript output from the Preview Window is now suppressed [there used to be error messages when offline]
- **Break**: PDF export seems to be broken now on some machines

**Version 0.965 (17/8/14)**

- [**2/9/14** - Updated .deb file, should now be handled better]
 - Now saves the user's preferences (layout/night mode)
 - Saves and autoloads the custom css that was last defined
 - Improved PDF export
 - Numerous minor improvements

**Version 0.955 (13/8/14)**

 - PDF export fix (supporting extended ASCII character set)
 - HTML export fix (supporting extended ASCII character set)
 - Fix regarding PDF titles (temporary)
 - RPM updated dependencies

**Version 0.950 (11/8/14)**

- Added styles
- Previous styles improved
- Better table support
- Bug fixes
- Packaging fixes for some distributions
- Some improvments (after converting to Python 3)

**Version 0.900 (7/8/14)**

- Markdown support greatly improved thanks to python-markdown extensions (default extra version). **Syntax is now very similar to Github Flavoured Markdown**
- Highlighting is now possible. ==text== becomes <mark>text</mark>
- Simpler link syntax with URL auto-linking like Github Flavoured Markdown (GFM). For example http://example.com and example.com will be recognized without the need for the usual syntax. This was achieved using [this](https://github.com/r0wb0t/markdown-urlize)
- Exported .pdf files will have a table of contents (using the headers)
- Stikethrough is now possible. Like GFM, ~~mistake~~ becomes <del>mistake</del>
- Superscript is now enabled. The syntax is like so: X^2^ + Y^2^ = Z^2^. This was achieved using [this](https://github.com/sgraber/markdown.superscript)
- Subscript is now enabled. The syntax is like so: H~2~O. This was achieved using [this](https://github.com/sgraber/markdown.subscript)
- Better new line support using [this extension](https://pythonhosted.org/Markdown/extensions/nl2br.html). It overrides default markdown. This is similar to Stackoverflow and Github flavours of markdown.
* [x] Check boxes are now implemented using [this](https://github.com/FND/markdown-checklist). The syntax is as shown in this list item.
- Fenced and in-line code-blocks are now possible. Just wrap the code with three ticks on both sides of the code
- Additional options for _italic_, __bold__ and ___both___.
- Added a file association so the system knows that remarkable can open files when supplied arguments
- Tables are now supported using syntax similar to Github. You can even use markdown within the table!

One  |Two
-------- | ------
Three | *Four*
==Five==  | Six

 
**Version 0.875 (6/8/14)**

- Another packaging fix
- Added spell checking (via gtkspellcheck)
- Can now supply command line arguments to open/edit files
- rpm file should behave better after installing

**Version 0.85 (4/8/14)**

- Packaging Fix
- Added zoom buttons for the live preview
- Enabled option to report bugs
- Better scrolling (again)
- Bug Fixes

**Version 0.80 (2/8/14)**

- Scrolling improved (not perfect)
- Better packaging
- Improved links
- Altered Version System
- Bug fixes

**Version 0.700**

- Syntax highlighting is enabled.
- Styles are better.
- Improved code, bullet and numbered lists.

**Version 0.650**

- Entire app completely rewritten with Ubuntu Quickly for publishing
- Now checks for updates on startup [as a background thread]
- Icons improved

**Version 0.625**

- Added a completly new icon set
- Enabled keyboard shortcuts
- Changed name to Remarkable
- Updated information
- Added verion checker
- Bug fixes
- Improved link addition
- Improved image addition
- Added the option to choose styles
- Implemented "night-mode"
- Enabled notifications
- Strikethrough supported
- Minor bug fixes
- Various other improvements
***
