# Publish Public Plugins (Indesign Plugin)

_________________

## The point of this plugin is to
Demonstrate some of the UI capabilities of InDesign and also engage with the software in a way that we dont know yet.

## You install it by doing
Adobe have a pretty good tutorial which this is a summary of https://developer.adobe.com/indesign/uxp/plugins/getting-started/
1. You will need to have Adobe InDesign, Adobe UXP Developer and a code editor installed. UXP plugins use HTML and JavaScript.
2. Download or clone this repository.
3. In UXP Developer, click "Add Plugin" to make  a new plugin. Navigate to this folder and click the manifest.json to add it.
4. Open InDesign.
5. Go back to this tutorial.
5. Go back to UXP Developer and click "→ Load".
5. Go back to this tutorial.
6. Go Back to InDesign and open your plugin from Plugins > Plugin panel.
7. Edit the other files of this plugin in your code editor. index.html is a good place to start which is the panel of the plugin, or main.js where the plugin functions are described.

## Other funny things when you make plugins for this software
https://developer.adobe.com/indesign/uxp/
- Open source plugins for proprietary software is already funny? Why?
- Talking to workers in their workplace. Unionisation plugins?
- UXP API
- Spectrum UI widgets and Web Components: https://developer.adobe.com/indesign/uxp/reference/uxp-api/reference-spectrum/
- InDesign API


_________________

# Based on Adobe's quick start template included in their UXP Developer App.

## Introduction
Start by saying a simple Hello world within a UXP plugin or use this as a template to add your code. This plugin has a very basic setup for you to create a `command` and a `panel` within a UXP plugin.  See more at https://developer.adobe.com/indesign/uxp/plugins/getting-started/

### Compatibility
Since InDesign v18.5 and UXP v7.1.

### Documentation
Familiarize yourself with the following concepts to understand the plugins in more detail
- [Plugin entry-points](https://developer.adobe.com/indesign/uxp/plugins/concepts/entry-points/)
- [Plugin manifest](https://developer.adobe.com/indesign/uxp/plugins/concepts/manifest/)

### Getting started

Load plugin into the application via UXP Developer Tools (UDT)
1. Make sure your application is running and you can see it under 'Connected apps'
2. Click on 'Add Plugin' button and select the `manifest.json` of this plugin.
3. Click on the menu -> Load to view the plugin under the 'Plugins' menu inside your application.

