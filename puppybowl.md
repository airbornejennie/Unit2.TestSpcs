The Puppy Bowl is a mini-game that allows users to add and remove cute puppies to a game roster. Some of this application has already been finished, but it is important to test "complete" functionality as well, to make sure everything is working for your clients.

Unit Test
Main Page should show a nicely formatted list of all players. 
Each player on the roster should be shown with two buttons:
A "See details" button that lets us view the details for that player. This should show at least:
The player's name, breed, and assigned team (or "unassigned" if they do not have a team)
A larger version of the picture
A button to go back to the main list
See the "Stretch Goals" section for more possible features
A "Remove" button that takes that player off the roster
--Expect "See details" button click to show player's name, larger picture, breed, and assigned/"unassigned" team. 
--Expect each player's name on the roster to show two buttons: "See details" and "Remove"
--Expect "Remove" button click to remove the player's name immediately from the roster list. 
--Expect an optional field in the Add New Player form that lets a user input an image URL and when submitted, will show as the player's portrait.

Functional Test
--When a user fills out all required fields of the Add New Player form and clicks submit, they should see the name of the new player pop up in the roster list without a page refresh. 
--If a user misses a required field in the Add New Player form and clicks submit, they should receive an error message explaining which field is missing. 
--When a user clicks on the "Remove" button next to a player's name, they should see it disappear from the roster list without a page refresh.
--When a user fills out the image URL field (and all required fields) in the Add New Player form and clicks submit, they should see the linked image show up as the player's portrait.
--When a user is in the single player view, they should see a dropdown menu that allows them to change the team assignment of the current player. 
--When a user changes the team assignment of a player using the dropdown menu, they should see a change in the player's profile view and in the roster, without a page refresh.

