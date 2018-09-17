# Random Email Content Generator
##Introduction
#This script has been put together to enable random email content to be generated from Open Source content
#and then to relay that mail through a local SMTP relay. Once this content is generated a PST file can be 
#exported and then imported into a live mailbox account on Office 365 for testing purposes. All content referenced
#here can be downloaded in a seperate zip file from my blog site. https://www.leeejeffries.com/
#The file paths will need to be changed to reflect the location you extract them to.
#
#The text content and subject lines of emails are generated from a public domain ebook
#The images, video and audio are all public domain open license so should be okay to use
#without incurring any copyright infringement
#
#Script to be run in powershell 2.0 or newer
#Just place in the smtpserver (Assuming unauthenticated) and the To and From address of the sender
#Amend the content locations and you are good to go
#Note: The script is infinite so a CTRL+C will exit it when you require it to stop
##