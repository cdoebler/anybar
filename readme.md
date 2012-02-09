anybar
========

### A very flxible toolbar plugin for jQuery

2012 by Christian Doebler <info@christian-doebler.net> http://christian-doebler.net/<br>
sponsored by Pfeiffer Medienhaus http://pfeiffer-medienhaus.de/


#### Examples

<pre>
$("#toolbar").anybar();

$("#toolbar").anybar("close");

$("#toolbar")
	.anybar({
		duration_open: 500,
		dimensions_open: {
			height: 400
		}
	});
</pre>


#### Settings and defaults
<pre>
tab_selector_attribute    "href"
tab_content_selector:     ".toolBarContent"
tab_button_selector       ".tabAnchorList ul li a"
close_button_selector     "#closeFooterToolBar"
duration_open             300
duration_close            300
dimensions_open           {height: 370}
dimensions_close          {height: 115}
</pre>


#### Methods
<pre>
show     anybar("show", "#contentSelector")     show tab content by content selector
                                                (opens toolbar if closed)
open     anybar("open")                         open toolbar
close    anybar("close")                        closes toolbar
hide     anybar("hide")                         calls "close"
</pre>


#### Events
<pre>
show     triggered when tab content is shown
         second parameter is content selector to area that is shown
open     triggered when toolbar is opened
close    triggered when toolbar is closed
hide     triggered when toolbar is closed (as well)
</pre>

