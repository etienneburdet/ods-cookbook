# ODS Chrome extension

A simple extension to increase productivity for every day users of the platform. It provides quick access to main tools like pages, monitoring, publish etc... 

It activates automatically when browsing Opendatasoft URLs (ie. `*.opendatasoft.com/*`)

## Install guide

- Copy-paste **Chrome extensions menu URL** in a new tab, and open it : `chrome://extensions`
- Activate developer mode (top right corner)
- Drag and drop [ODS extension zip](https://github.com/opendatasoft/ods-cookbook/raw/master/chrome-extension/ods-chrome-extension.zip) onto the extension screen

and that's it !

## Available links

When browsing ODS content pages `/pages/*` :

- direct link to content edition
- direct link to usage statistics

When browsing any ODS pages `/*` :

- direct link to create a new page
- direct link to create a new dataset

- from the frontoffice -> direct link to the backoffice
- from the backoffice -> direct link to the frontoffice 



## Changelog

V0.3
- direct link to usage statistics
- from the frontoffice -> direct link to the backoffice
- from the backoffice -> direct link to the frontoffice

V0.4
- Introspect the page to see which datasets are used in a page

V0.5
- Add a toggle on/off by clicking on ODS icons (usefull for screenshots

V0.6 
- Add a 1500 millisec timer before checking for contexts to let enough time to angularjs digest process