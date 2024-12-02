# Programming-Mobile-Devices-Project

This is Programming Mobile Devices Module from the BSc(Hons) in Software Development Module at MTU. 

Requirements:
1. Create a learning app for kids.
2. You can choose any of the following themes:
• Wild Animals
• Farm Animals
• Musical Instruments
• Vehicles
3. Your main activity should display a recyclerview list of at least 10 rows.
4. Each row should have an image of the item and its name in a textview placed next to
the image. Store images in drawable folder in resources with appropriate names.
5. When user clicks on any row, use intent to start the second activity.
6. Pass useful data of the chosen item through intent to second activity.
7. The second activity layout should have one mandatory textview and one mandatory
button.
8. The textview on second activity should display a fun fact about chosen item. Use
strings in resource folder to store fun facts for second activity
9. The button on clicking should open a Wikipedia page for chosen item.
10. You can add additional features including images, buttons etc
Some bonus features can be:
• Set background image of second activity based on chosen item
• Add a sound button which should play a sound of chosen item

• Java codes for :


i. Item_class.java (including variables for name, imageurl etc)


ii. MainActivity.java


iii. Secondactivity.java


iv. MyRecyclerViewApapter.java


• Xml codes for:


i. activity_main.xml


ii. activity_second.xml


iii. recyclerview_row.xml


Grading Scheme:
1. Correct display of items on main activity (40)
• Layout(activity_main,recyclerview_row )
• Java (item_class , MainActivity , myRecyclerViewadapter )
2. Correct implementation of onclick method to start second activity (20)
• (Onclick method, intent )
3. Correct display of second activity with appropriate data (20)
• (Layout ,SecondActivity)
4. Bonus Features (20)

Final Grade Achieved: 39/40 
