# VailResortsCodeTest
This is the Responsive Email Coding Test for Vail Resorts.
Email HTML Test

Overview
Create a responsive email leveraging the Cerberus email framework.  The overall layout of the email should be as the following:
WIREFRAME BLUEPRINT IMAGE - see email.
 
 

Requirements<br>
•	Logo should be left aligned while on desktop and shift to a center aligned while on tablet/mobile. 

This element should be linked.

•	The Hero image needs to be dynamic using conditional statements with Ampscript. If the resortDescription is “Vail Resort” display Image 1, otherwise display image 2. 

These elements should be linked.

•	The two column images need to stack on tablet/mobile. The right image (Image 4) should be on top of the left (Image 3) while displaying on tablet/mobile. While on the desktop the images should be side by side reflected in the wireframe above. 

These elements should be linked.

•	Copy writing section needs to contain one link to an external page. Additionally, the first name needs to be dynamic to address the guest by their first name. Assume the field to be called from the data extension is “firstName”. Further, the first name should be aligned left while the remainder of the copy is aligned center, as reflected in the wireframe.

•	Footer background color has to span entirely across the email as reflected in the wireframe. Background color can be of your selection.

•	Phone number in the footer should have a click to call link.  USE “tel:”

•	All outbound links in the email can be of your selection.

Assets for Build

Logo URL Image<br>
http://image.email.snow.com/lib/fea1157075670d7c75/m/6/af97139c-1339-40ef-8285-f0c3ed8e922a.png

Hero URL Image 1<br>
http://image.email.snow.com/lib/fea1157075670d7c75/m/4/092217_Hero_Default.jpg
Hero URL Image 2
http://image.email.snow.com/lib/fea1157075670d7c75/m/6/SnowAlertKicker.jpg
Image 3 URL
http://image.email.snow.com/lib/fea1157075670d7c75/m/11/1435a18b-edec-4a0b-b4bd-f3a9f1ef6def.jpg
Image 4 URL
http://image.email.snow.com/lib/fea1157075670d7c75/m/11/947c1955-6051-45d0-9dfa-fc9e8aa2b0b5.jpg

Follow Up Questions

•	What is the main difference between developing for email rather than a website?  As a developer, the fact that you use inline CSS coding for an email development environment to avoid the various preprocessors that may change the coded styling.  With that being said, with the Cerberus Wireframe, the styling is not all inline, rather it is included within the head of the html as to avoid the preprocessor issues.

•	An image went out with the wrong pricing on it, how can you correct this issue? Be prepared to act quickly but not foolishly, use humor, apologize, change the url linked image, if that is time consuming, you can use an “alt” tag and place simple language that corrects this while you are amending the image narrative in the event that the pricing is hard coded within the image.
	
•	Whoops a URL went out incorrect, could you potentially fix this issue?  There are a few ways to deal 1) Send a follow-up communication to the recipients, use humor and apologize, with the new URL.  2) If it is not contained in the email, you can update the repo with the coded URL immediately.  Regardless of form, I'm a believer in telling those affected by this error immediately for any further direction or historic protocal in this area.

•	Are background images supported in Outlook? Yes.  In the past, to see background images in Outlook, the image had to be a table image, but no longer is that a requirement.

•	Why is the !important declaration useful?  It gives importance or precedence to the property value.  It, in effect, moves the property up in the cascade.  This is also used in inline coding to override the current style.

•	What is a media query?  This denotes how the. UI should appear given different devices or apps being used.  For example, this is the code that allows your document to be responsive to the device being used by the user.  
	
•	What is a high level process for working with a file using GIT version control?  1) Creating a repo with a README file 2) Clone or copy the repo link 3) go to terminal/bash and within the working file, “git clone COPIED REPO FILE”  4) Go to your text editor, code, save, view in browser, if the code is tested accurate in all browsers, then 5) go to your terminal/bash 6) make sure you are in the working directory 7) in the command line, “git add .”, check for errors, "git status" make sure working changed files were added/edited 8) in the command line, “git commit -m “MESSAGE THAT SIMPLY EXPLAINS WHAT THIS COMMIT IS ABOUT/DOING” 8) make sure no errors, "git status"  and that the working tree is clean 9) in the command line, “git push origin master (or other location specified)” 10) make sure there are no errors, "git status", working tree clean 11) if you are working collaboratively with a team, and you want to get existing code, go to the github repo 12) you may either fork, or clone from that repo, depending on what you are going to do with the code
