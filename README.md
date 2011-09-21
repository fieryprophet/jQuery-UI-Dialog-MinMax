#	Description
jQuery UI Dialog w/ Minimize and Maximize Support

http://www.fieryprophet.com/demo/jqui-dialog-minmax/

#	Usage

$("#dialog").dialog({minimize: true, maximize: true});

#	Notes
 - May not be used with the modal dialog option
 - The minimize option can be either a boolean value or a selector string of an element to "minimize" the dialog to
 Example:
 
	$("#dialog").dialog({minimize:"#toolbar"});
	
	An <a> element link will be created in the #toolbar element that unminimizes the dialog when clicked.
	If the minimize option is a boolean value of true, it will simply hide the dialog content and leave a floating titlebar that can be unminimized.
	
- Adds "minimize" "unminimize" "maximize" "unmaximize" events
- Adds "beforeMinimize" "beforeUnminimize" "beforeMaximize" "beforeUnmaximize" optional triggers

# License

This plugin is licensed under the MIT and GPL2 licenses, same as jQuery and the jQuery UI projects.