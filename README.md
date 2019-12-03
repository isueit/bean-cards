This module creates the skeleton for a block type that is to be used to recreate the functionality of Bean Cards. The Block is called Content Cards and contains four fields; body, title, images, and urls. 
<br/>
<br/>
The best way to recreate the Bean Functionality is to use the Content Card block type and create your own blocks.
<br/>
<br/>
Then those blocks can be displayed using a custom view with the following steps,
<br/>
<br/>
	Add View -> View Settings
	<br/>
		- Show "Custom Block" of type: "Content Card"
	<br/>
	Block Settings -> Create a block
	<br/>
		-Display Format: "Unformatted List" of "Fields"
	<br/>
	<br/>
These settings will allow you to customize the view to display whatever fields from the Content Card that you wish to display. In addition to you can then filter the view to only use a Block with a specific description.
<br/>
<br/>
This is done with the following steps:
<br/>
<br/>
	Under Filter Criteria Select Add -> Block Description then click "Add and configure filter criteria" -> Select "Is Equal To" and set the "Value" equal to the desired Block's description
<br/>
		- Doing this will cause this view to only display the data from the Content Card you wish to use
<br/>
		- This is the best way to use these Content Cards for display with the Panel System enabled on the Human Sciences Site
<br/>
<br/>
This module was built for the intention of following the above steps and using the custom blocks to create views displayed with Panel and Page Manager.
