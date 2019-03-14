# Bull-s-Eye

This is the first app project in iOS Apprentice fully complete. It's a game called Bull's Eye where a random number is 
generated and you score points based on how close you position the slider to that value. Once the "Hit Me!" button is tapped 
an alert appears displaying your points for that round. When the alert is dismissed the score and round labels are updated, 
a new random number is generated, and the slider is positioned back to the center. There is also a start over button that 
resets score, round, and slider position with a fade animation, as well as an info button with a flip transition segue to 
another view controller that explains the rules of the game. Objects have constraints to accomidate all screen sizes. There 
are background images on both view controllers, the AboutViewController performs a URLRequest thats loads an HTML file. There 
are images on the "Start Over" and "Info" buttons, as well as the "Hit Me!" button which also contains a highlighted image so 
the user has feedback to confirm the button was pressed as well as to add visual appeal.
