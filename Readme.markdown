# Corona Plugin Submission Template

This is a template for plugin submission.

Please read the [Plugin Submission Guidelines](http://docs.coronalabs.com/daily/native/plugin/submission.html) for more information.

This template provides stubs for two of the top level directories that are needed in your plugin submission:

* `docs/` All instances of the string 'PLUGIN_NAME' should be renamed in all files
    + `PLUGIN_NAME/` This folder should correspond to the name of , e.g. 'openudid'
        - `index.markdown` This is the top level page for your plugin's documentation
        - `FUNCTION.markdown` This is a stub for a library function offered your plugin
        - `PROPERTY.markdown` This is a stub for a library property offered by your plugin
* `samples/`
    + `build.settings` You should modify this so that the build server knows what plugins are needed. See instructions inside the file
    + `main.lua` You should modify this to demonstrate how to use the plugin.

Please note that this template does __not__ provide stubs for the plugin binaries themselves. The directory structure for that is explained in the [Plugin Submission Guidelines](http://docs.coronalabs.com/daily/native/plugin/submission.html)

## Markdown guidelines

Our documentation uses markdown. In particular, [Pandoc markdown](http://johnmacfarlane.net/pandoc/README.html)

### Reference links

Our internal documentation system inserts Markdown-style reference links. You can refer to other pages in your documentation or even other pages in the documentation site in this manner.

The reference links are subpaths where directory delimiters are replaced with '.'. We also remove the root path from the link. Here are some examples:

* `[Main Plugin Documentation page][plugin]`
* `[openudid documentation page][plugin.openudid]`
* `[display library page under SDK APIs][api.library.display]`

