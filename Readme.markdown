# Corona Plugin Submission Template

This is a template for [plugin submission](https://store.coronalabs.com/corona-store-application).

Please read the [Plugin Submission Guidelines](http://docs.coronalabs.com/daily/native/plugin/submission.html) for more information.

This template provides stubs for two of the top level directories that are needed in your plugin submission:

* `metadata.json` You should modify this with information about your company and plugin
* `plugins/`
    + `VERSION/`
        - `android/`
            - `metadata.lua` This is a stub for the metadata describing the binary
        - `iphone/`
            - `metadata.lua` This is a stub for the metadata describing the binary
        - `iphone-sim/`
            - `metadata.lua` This is a stub for the metadata describing the binary
        - `mac-sim/`
            - `plugin_PLUGIN_NAME.lua` This is a stub Lua file to be used by the Corona Simulator
        - `win32-sim/`
            - `plugin_PLUGIN_NAME.lua` This is a stub Lua file to be used by the Corona Simulator

The complete directory structure is explained in the [Plugin Submission Guidelines](http://docs.coronalabs.com/daily/native/plugin/submission.html)

## Docs and Sample Code

In order for your plugin to be used successfully, you should provide API documentation _and_ sample code for your plugin online. 

For API docs, we recommend using our [Plugin Docs Template](https://github.com/coronalabs/plugins-template-library-docs/blob/master/Instructions.markdown).


## Replacing strings in ALL CAPS

In each file there are strings in ALL CAPS that should be replaced with information specific to your plugin. You should 'grep' for the following strings and replace them appropriately:

* `PLUGIN_NAME` This should be the name of the plugin. 
    + You should preserve any prefix such as `plugin.` or `plugin_`. 
    + Note the trailing '.' and '_', respectively.
    + Don't forget to rename any file __and__ directory with `PLUGIN_NAME` in it, e.g. `plugin_PLUGIN_NAME.lua` => `plugin_openudid.lua`.
* `VERSION`
    + This is a directory
    + You should rename this to the daily build version of Corona in which the plugin is available, e.g. 2013.1076.
* `PUBLISHER_CONTACT` The e-mail of the main contact person for support.
* `PUBLISHER_NAME` The brand name of the publisher.
* `PUBLISHER_URL` The url of the publisher
* `REVERSE_PUBLISHER_URL` The reverse domain that uniquely identifies the publisher, e.g. `com.mycompany`.
* `SERVICE_NAME` The name of the service provided by the publisher (if applicable)
* `CORONA_REFERRAL_URL` The referral link if the service requires a separate account registration.

