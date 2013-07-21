Created by Michael Arnold on February 20rd 2013
Last updated: February 23rd 2013

Guide created: Sunday June 21st 2013

Guide last updated: Sunday June 21st 2013



General About:
  I made this when I encountered a problem, that problem was
	"I want to do something productive with my time on the internet, but I don't know where to go.."

	So I made this simple program; What it does is it allows you to is create a list of websites you enjoy
	and then bookmark this program, and every time you click the bookmark the program will automatically send
	you to one of the websites you have specified. 

How To Run:
	• 	Save this file as "AnyNameYouWant.html" to any location of your preference
	•	Go to "Create New Bookmark" in your web browser of choice
	•	Change the name at the top from "New Bookmark" to "Random Bookmark" or whatever your preferred name is.	
	•	For location list the file path to your "AnyNameYouWant.html"
			EX: Something along the lines of "FILE:///C:\Users\YourUserName\Desktop\RandomBookmark.html"
	

Customization guide:
	• To change the website list: Simply replace the "http://CurrentWebsiteListed.org" with your website's URL.
	• To change the amount of websites on the list you must do two things:
		1. Delete or add "randomurl[##]=''" until the amount you want is displayed.
		2. Change the number "51" to the number of "randomurl"s you have in your list. As you can see
			I have the number 51 for a randomurl up to #50, that is because the first is #0, please do not
			forget that. A few more examples to be perfectly clear would be starting at randomurl[0] and
			ending at randomurl[95] resulting in needing to change the Math.random()*51 to 
			Math.random()*52 
		
Closing notes: I hope this is useful for someone other than myself, if you have any questions or requests
then please email me at: marnold904@gmail.com and I would be happy to answer and help. :)
