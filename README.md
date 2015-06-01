
===============================================================================
                             CSE134B THE END USERS
                               COINFLIP - HW4
===============================================================================

Backend Service - Firebase
	We decided to use one of the tools the professor mentioned called Firebase. 
	Firebase handles both our user management and persistence of our data, mainly
	a users stack of gold/silver/platinum. We implemented the user management part
	by following a tutorial on firebase and using oauth to authenticate a user. 
	Mainly, we had to setup a new application on facebook and google to create an 
	APP ID and SECRET ACCESS KEY so that any user who wishes to register with our 
	application using facebook or google can do so. The CRUD operations were handles
	using Firebase's API methods, mainly push and update.

Gold/Silver/Platinum Dataset - Quandl
	We used Quandl to get realtime data for the current prices of gold, silver, and platinium. Data for the graphs was taken from the Quandl databases for Gold American 
	Eagle, Silver Engelhard industrial bullion, and Platinum Engelhard fabricated 
	products. The prices of the past 30 days are displayed from these sources.

Obstacles - After implementing authentication some of our members had trouble getting logged in to view changes to the app. We also had some problems with the graphs not appearing for some users.
