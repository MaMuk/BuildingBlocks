# Package Listing
Each of these packages are ready to be built, zipped, uploaded and installed using [Module Loader](https://support.sugarcrm.com/Documentation/Sugar_Versions/7.6/Ent/Administration_Guide/Developer_Tools/Module_Loader/) into any existing Sugar 7 On-Demand or On-Site instance.

The `buildPackages.sh` script can be used to build all these packages easily on Unix based environments.

## [Canvas iFrame](CanvasIFrame)
This package displays an IFrame inside Sugar.

## [Contextual iFrame Dashlet](ContextualIFrameDashlet/)

iFrame dashlet that additionally will pass URL parameters with context information (record id and module name) that can be used to drive a lightweight UI integration with an external application.  Can be used as-is for a Proof of Concept or Demos and can be easily customized for additional capability.

## [Hello World Dashlet](HelloWorldDashlet/)

Good starting point for building any [Sugar Dashlet](http://support.sugarcrm.com/Documentation/Sugar_Developer/Sugar_Developer_Guide_7.6/UI_Model/Dashlets/Introduction/) based integration from scratch.  Easily customizable for additional capability.

## [Custom Record View Button](CustomRecordViewButton/)

Shows how [Extensions Framework](http://support.sugarcrm.com/Documentation/Sugar_Developer/Sugar_Developer_Guide_7.6/Extension_Framework/) can be used to implement a custom button on a Record View without overriding any core files such as Sidecar View controllers, etc.

**Install Note:**  You may need to clear your cache after install of this package to ensure that old JavaScript is cleared out of the page.

## [CssLoader](CssLoader/)
Utility package that provides a very simple API for loading CSS into the Sugar application for use in Dashlets or other custom UI components.

## [ScriptLoader](ScriptLoader/)
Utility package that provides a very simple API for loading JavaScript into the Sugar application for use in Dashlets or other custom UI components.

Includes [require.js](http://requirejs.org/) which is BSD / MIT licensed.

## [IFrameDrawerAction](IFrameDrawerAction/)

Starting point for adding a custom action to existing Sugar layouts that opens a drawer to present a custom UI within an IFrame. Currently it will pass URL parameters with context information (record id and module name) that can be used to drive a lightweight UI integration with an external application. Can be used as-is for a Proof of Concept or Demos and can be easily customized for additional capability.

## [FloatingDivAction](FloatingDivAction/)

Starting point for adding a custom action to footer that adds a floating DIV pane to the Sugar user interface. The advantage is that a floating pane does not re-render as the Sugar user navigates the application. This is a common use case for Telephony or Chat integrations.
