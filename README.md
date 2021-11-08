#HTML/CSS 1: Page Structure 

Instructions: 

-- Download this repository and move the folder to your Desktop or JNL221 folder.

-- Locate a news story from a reputable online news source. It needs to have at least eight (8) paragraphs of written text and include at least two (2) high-resolution images with written photo captions.

-- Right-click on each image in the story and save it within this folder.

**It’s critical that all these files are within the same computer folder as you work.**

Just like in class, I’d recommend that you open “index.html” in your browser as well as in Sublime Text so that you can examine your work as you go. If you don't know what an element is, check W3Schools or stackoverflow.com. We are at a point in the semester where you should feel comfortable researching how to do an unfamiliar thing.

 
##Inside the <head> element:

1.	I’ve pre-written a CSS file (main.css) to style your HTML. Add a <link> element inside the <head> and set the rel attribute to “stylesheet” and the href attribute to “main.css”: <link rel=“stylesheet” href=“main.css”>

2.	Also in the <head>, use the <title> element to give your page an appropriate title.

Inside the <body> element:

3.	Add a <header> element. Inside, write “HTML/CSS Assignment #1” followed by a <br> element. Next, write “Source: ” followed by the URL of the news story you’ve chosen. Make that URL into a working hyperlink to the original news story.

4.	Add a <div> element to hold the main image and caption for your story. Set its class attribute to “mainimg”. Inside the <div>:

	a.	Add an <img> element, setting the src attribute to the name of your first image file. Give it appropriate alt text.

	b.	Add a paragraph element (<p>) for the caption. Set its class element to “caption”. Use the appropriate HTML element to italicize the image credit (i.e. the name of the photographer or company source of the image from the written caption).

5.	Add an <h1> element that contains the story headline.

6.	Add an <h2> element that contains the story deck (usually an expansion of the headline with some more detail or a story summary in one or two sentences). If the story you chose doesn’t have a deck, write a brief one. You can find plenty of examples and styles out there.

7.	Add a paragraph element with the byline(s) of the reporters, and use the appropriate HTML element to make it bold.

8.	Add the first half of the story’s text content using the appropriate HTML elements. Remember, the story you choose needs to contain a minimum of eight (8) written paragraphs. If the story has hyperlinks included in the story text, make sure that you add them to your version as well. 

9.	Add a <div> for the second image and caption. Set its class attribute to “otherimg”. Follow the same instructions underneath step 4 to add an <img> and caption paragraph — just make sure the src attribute is for the second image file that you’ve saved.

10.	Add the remaining paragraphs of the story.

 

To turn in:

-- Login to your Github account and go to your repositories page.
-- Click on the green 'New' button to create a new repository. Call it HTML_assignment_YourLastName. Make sure it's public and add a README. Click 'Create repository'.
-- Click 'Add file' and then, 'Upload files'. Upload all of the files in this folder.
10. Make your commit message 'Completed 11/10 HTML assignment' and click 'Commit changes'.
