This module creates the skeleton for a block type that is to be used to recreate the functionality of Bean Cards. The Block is called Content Cards and contains four fields; body, title, images, and urls. 
<br/>
The best way to recreate the Bean Functionality is to use the Content Card block type and create your own blocks.
Then those blocks can be displayed using a custom view with the following steps,
	Add View -> View Settings
		- Show "Custom Block" of type: "Content Card"
	Block Settings -> Create a block
		-Display Format: "Unformatted List" of "Fields"
These settings will allow you to customize the view to display whatever fields from the Content Card that you wish to display. In addition to you can then filter the view to only use a Block with a specific description.
This is done with the following steps:
	Under Filter Criteria Select Add -> Block Description then click "Add and configure filter criteria" -> Select "Is Equal To" and set the "Value" equa		l to the desired Block's description
		- Doing this will cause this view to only display the data from the Content Card you wish to use
		- This is the best way to use these Content Cards for display with the Panel System enabled on the Human Sciences Site

<br/>
<br/>
This module was built for the intention of following the above steps and using the custom blocks with Panel and Page Manager, if those two modules are not enabled on the site when the Content Cards module is enabled then it will enable and install them.
