PHP-Facebook-Search
===================

Small PHP Facebook Graph API Search.
Demo Available: Codebreach.in/demo/fb.php

This is a small demo showing "How to use facebook graph API" without using any of the SDK by facebook.

Before beginning, Here's the two things that you will need:

	-Facebook Access Token
	-A Web server which supports PHP

**Getting Facebook Access Token**

Goto Facebook Developer page to generate your access token. Be sure that you never share this token with anyone else unless you dont want your facebook account getting hijacked.


The access token is basically a long string identifying yourself with facebook, so access tokens are as secret as your password. Once you have the access token, then we are good to go.



**A Web server which supports PHP**

Here, I Will be using a Simple PHP Script for pulling the data from facebook. So we require a webserver which supports PHP scripts (Preferably Apache or nginx).

So lets start by creating a Simple HTML form which will be having 2 Input fields for:

	-Access Token
	-Search Term

So the script is very simple, which will take the access token and then use it for searching the "Search term" in facebook. The result will be basically in json format and the PHP script will parse the json document and then filter out the Link to the Post, Message of the Post and then the Name of the Page/Person who posted the Post.
