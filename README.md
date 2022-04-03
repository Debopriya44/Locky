# Locky

##Inspiration
My first inspiration was while looking for an inspiration my door bell rang 3-4 time and i have to get and move to the ground floor from the second floor just to open the door, thats really irritating for me as an tech lover. So i thought of implementing some smart techy things to it.

##What it does
It basically operates with the helpful of the internet and it is a basic iOT device that opens our door through the app built for out smartphone and also sends us the notification with the time-stamp when it is opened.

##How we built it
I had built it using some hardware part such as:- 1) Arduino pro mini 2)wifi module 3)heavy load servo 4)mobile adapter 5)some strong thread And the software parts:- 1) Arduino IDE 2)NODE-RED 3)IBM CLOUD 4)TWILIO API 5)MIT APP INVENTOR The total device is hosted inside the node-red over IBM cloud to take action and send command to our LAZY DOOR device, also the storing of data and sending of notification is done through the node-red. And I had built the UI in the low-code app buiding platform - MIT APP INVENTOR.

##Challenges we ran into
The main challenge I faced was to open the door lock through mechanical movement using the servo. Also while powering the device ON, the initial digitalRead() values were getting changed every time we turn ON the device. But at last I had resolved those issue and as far as of now the device is working totally fine!

##Accomplishments that we're proud of
1) I learnt about node-red module 2) built a app easily in the mit app inventory 3) Built a complete working hardware+software project in just 2 days 4) Though the project is very simple yet very helpful.

##What's next
I am thinking of implementing a CCTV technology outside the door so that we can also monitor the activity and who is standing outside of it.
