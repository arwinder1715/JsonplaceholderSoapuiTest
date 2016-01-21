![alt tag](https://media.licdn.com/media/p/3/005/083/306/0f1119a.png)
# JasonplaceholderSoapuiTest
http://jsonplaceholder.typicode.com/ is used as a free REST API for SoapUI project.
This project demonstates the main steps and transitions in SoapUI for beginners.

# Precondition
* SoapUI 5.2.1 and higher is required http://www.soapui.org/downloads/soapui.html

# How to use
* Get "Jsonplaceholder soapui tests.xml" file from github and place it to any local folder
* Open SoapUI and Import Packet Project
* Navigate to Jsonplaceholder Test Suite
* Right-click on it and select Launch TestRunner

# What is under test
* Get list of "todos" having "completed" = true
* Creating some simple tests for "posts" (create, read, update, delete).
* Get list of users and then get some user's posts
* Get list of users, determine a nonexistent user ID and get it. Check response.
* Get photo #25 from album #50 and check its "url", "thumbnailUrl"
