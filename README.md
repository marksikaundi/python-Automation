# python-Automation
Easy work done with python to look for things either online or in your local storage.
check all commands and try to automate something either by sending a happy burthday to your girlfriend at the exactly time.

#Installation full process
This library can be installed by the pip command, open your command prompt and type in the following command...

pip install pywhatkit

Functions of this library
First import the library using the command import pywhatkit as kit and then proceed to call the functions

kit.sendwhatmsg()
This function can be used to send WhatsApp message at certain time

#The parameters are
phone_num (required) - Phone number of target with country code
message (required) - Message that you want to sendwhatmsg
time_hour (required) - Hours at which you want to send message in 24 hour format
time_min (required) - Minutes at which you want to send message
wait_time (optional, val=20) - Seconds after which the message will be sent after opening the web
print_waitTime (optional, val=True) - Will print the remaining time if set to true

Some common errors
CountryCodeException - Check if the phone number passed into the parameter has country code
Message not getting delivered - Check internet speed and increase wait_time to 30 or above CallTimeException - The web takes some time to load so some delay is required, make sure the seconds left is greater than the wait_time
SyntaxError - Make sure the first two parameters are string and the rest are int

kit.playonyt()
This function can be used to search and play a particular video on YouTube by using just the keyword, like "Shape of You song"

The parameters are
topic (required) - Topic or title that is related to the video

Some common errors
Video not opening - Make sure the topic exists or you have provided proper spelling

kit.search()
This function can be used to make a google search for any term
The parameters are
topic (required) - Topic or title that you want to search

kit.info()
This function can be used to fetch information about any topic
The parameters are
topic (required) - Topic or title that you want to get information about
lines (optional, val=3) - Number of lines that you want to print about it

Some common errors
Not returning paragraph - Make sure the topic exists and you are providing specific title

kit.image_to_ascii_art()
#This function can be used to convert any image to ASCII art

The parameters are
imgpath (required) - Path to the image that you want to convert
output_file (optional, val=pywhatkit_asciiart.txt") - File where you want to save the output characters

#Some common errors
File not found - Make sure that the path of the image is valid

kit.text_to_handwriting()
This function can be used to convert text to hand written characters, the character sets has been written by me

The parameters are
string (required) - String that you want to convert to handwritten text
save_to (optional, val = "pywhatkit.png") - Path where the image will be saved
rgb (optional, val = [0,0,138]) - Color of the handwritten character in rgb format

#Some other functions
pywhatkit.showHistory() # Will show information of all the messages sent using this library

pywhatkit.shutdown(time=100) # Will shutdown the system

pywhatkit.cancelShutdown() # Will cancel the scheduled shutdown

pywhatkit.tutorial_hindi/english() # Will open a tutorial on how to use this library on YouTube in respective language

pywhatkit.join_discord() #Will redirect you to our Discord server

pywhatkit.send_mail("test@gmail.com", "password", "Test Mail", "This is a test email", "testrecv@gmail.com")

pywhatkit.help.<function>() # For more information
#Contributing
happy 20201
