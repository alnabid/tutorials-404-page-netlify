# tutorials-404-page-netlify
code from the 404 tutorial

It won't work anywhere else except for netlify. It won't work in Live servers, Other hosting servers, Html viewer/code viewers etc. Only works after the file is deployed in netlify.

https://404-tutorial-alnabid.netlify.app/

The code you have to put in your netlify.toml file
--------------------------------------------------
```toml
[[redirects]]
  from = "/*"
  to = "/path/404.html" #change-the-name-and-the-path-here-and-delete-this-comment
  status = 404
```

Here's the script of the video - Might work as a step by step reading tutorial
------------------------------------------------------------------------------

Hello! You might be familiar with netlify. And you might be deploying your files into the web with it. But there's a problem that most people run into, when someone opens a link inside your website that does not exist, it shows the default netlify 4O4 page. I'll show you how to set a custom 4O4 page for your website that is already deployed via netlify. You need to make sure that your website is deployed correctly. You should have an index file which will show up as the home page when you enter the website. In order to make a custom 4O4 page, you must create an html file named anything. You can name it 4O4.html but it's all upto you. It also doesn't matter if it's in a folder. But you should have the file inside the folder you will deploy.

After you create an html file for your custom 4O4 page, you can edit the code about how the page is going to look. You can create a CSS file and a Javascript file for the 4O4 page and link them together. Designing and functioning the file is your part. After you design your 4O4 page, and deploy it to the net, it won’t work. As you can see, it still shows the default netlify 4O4 page. I’ll show you how to fix it.

In order to make the 4O4 page work, you need to create another file just beside the main index file. Name it netlify.toml

Don’t worry, you just need to write 2 lines of code. You can copy paste this code. I’ll also put it in the description so you can easily copy the code. You need to change only one line of code here. Make sure the path is correct. Put in the location of the 4O4 page correctly. Now, you can deploy the files via netlify and it will be working. 

Thanks for watching, consider subscribing if it helped you.

Here's the video - https://youtube.com/alnabid 

alnabid
-------
Website - https://alnabid.netlify.app
