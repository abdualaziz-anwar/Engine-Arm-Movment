This is task number 2 which will allow the user to choose a direction for an engine.
first of all, the "Main Page", this page contain two buttons, the first button for the arm movement , 
if the user press this button it will move him to the arm movement page 'Task 1', 
the second button the user will be able to choose direction for the robot.



first thing I did was the HTML file.
I started by adding a div so wil be in one pace and can be managed well.
this is simpe so there wont be any complex thing here.
then I added the form, so all the data be stored there and send directly to the database.

I created a database called RobotTable, it has 5 column all of type int: from 1 to 6 it belongs to the machines and the degree the user choice, 
the last column belongs to the status. it will store two values only, either 0 or 1.
0 to save and 1 to play.

then I made a css file which will contain the styling of my page, and I link the html page with the css styling page.
and I applied everything i need and added the photo.

after that I made a php page and link the user Interface with the database I created.
and also, I make sure that the data being inserted to the database, otherwise it will show a message that the data could not added to the database.



===================================================================================================================================================

DESCRIPTION FOR THE SECONDE TASK "ENGINE MOVMENT":
when the user presses the button in the home page it will move him to this page, in this page I made 5 buttons,
four of them is for picking the direction you want to move the robot, 
and the one in the middle to stop the robot from moving.

data will be sent to the database to the table called 'direction'.
this table consist of only one column for storing the direction only.
the data will be stored as numbers.
0 ==> stop
1 ==> forward
2 ==> Right
3 ==> Back
4 ==> Left


NOTES:
===================================================
you have to download XAMPP.
then you have to put this file in 'htdocs' inside the XAMPP folders.

also note that in the video i recorded, i show the user interface and i SAVE the data and show it to you after it is being 
inserted to the database and it has '0' in it's status.
And when i try again with diffrent data and push the PLAY buttoun, data will be stored also and the status will contain '1'.
