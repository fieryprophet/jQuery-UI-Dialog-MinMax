#	Description
jQuery UI Dialog w/ Minimize and Maximize Support

http://www.fieryprophet.com/demo/jqui-dialog-minmax/

#	Installation

1. Replace all jQuery UI dialog code in your jQuery UI javascript file with the contents of the included Javascript file.
2. Replace all jQuery UI dialog CSS in your jQuery UI theme CSS file with the contents of the included CSS file.

It is recommended to do this with an uncompressed version of the base jQuery package so you can reminify the contents to fit your needs.

#	Usage

$("#dialog").dialog({minimize: true, maximize: true});

<b>NOTE: minimize and maximize are enabled by default, so the above example is purely for demonstration</b>

#	Notes
 - May not be used with the modal dialog option
 - The minimize option can be either a boolean value or a selector string of an element to "minimize" the dialog to

<b>Example</b>
 
	$("#dialog").dialog({minimize:"#toolbar"});
	
	An &lt;a&gt; element link will be created in the #toolbar element that unminimizes the dialog when clicked.
	If the minimize option is a boolean value of true, it will simply hide the dialog content and leave a floating titlebar that can be unminimized.
	
- Adds "minimize" "unminimize" "maximize" "unmaximize" events
- Adds "beforeMinimize" "beforeUnminimize" "beforeMaximize" "beforeUnmaximize" optional triggers

# License

This plugin is licensed under the MIT and GPL2 licenses, same as jQuery and the jQuery UI projects.