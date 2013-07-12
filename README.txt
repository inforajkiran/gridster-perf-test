This is a performance test project using the gridster.js by Ducksboard (see www.gridster.net).

#### 2013 - 07 - 12 ####
The inlcuded html page shows the issue when using the gridster API for adding widgets.  On opening the grid is build with ~150 widgets and is pretty responsive.  To see the performance issue, insert a number into the input box, and click the "Create Widgets" button. It will delete all existing widgets, and create as many new ones as specified. The js in the head of the html calculates the time it took to do so, and the result will be displayed at the top. Note that the performance (seconds/widget) drops with every added widget, even though they are deleted.

The referenced jquery.gridster_dbg.js includes console logging, to get an idea of what functions cause the performance drop.