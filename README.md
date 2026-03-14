# FrameworkLoader
Add a specific CSS framework to your ProcessWire site. This module is especially designed for testing purposes with different frameworks to switch between them in an easy way.

## Supported frameworks

The following frameworks are supported by the module at the moment:

* Bootstrap 4
* Bootstrap 5
* Uikit 2
* Uikit 3
* Pico 1
* Pico 2
* Bulma 1

## How does it work?

Select the preferred framework inside the select inputfield and all necessary stylesheets and Javascript files will be added to the frontend of your ProcessWire site.

### Sync with FrontendForms

This modules offers a checkbox to sync the framework settings with the FrontendForms framework configuration settings. This means, that if the framework will be changend inside this module configuration (for example Uikit 3 will be selected), then the same framework will be saved inside the module configuration of FrontendForms too. This also works inside the opposite way.

This only happens if the checkbox for the synchronization is checked inside the module configuration.
