# Development Log for Zotero-Viewer [demo project]
## What is this project?
Eventually this will be a working react.js app for viewing websites stored in a zotero library, designed to help staff and students of Newcastle Digital Cultures explore sample projects. The full idea is explained [below](#an-idea). 

The whole project is a walk through of how I went from having a half-baked idea to a functional prototype. It is meant to both provide step-by-step instructions for working with live data and building a simple react app, but more as a journal of how the process works and as, hopefully, inspiration.

## What is this file? 
As the project develops, I will keep a log here of what I did and why. I will document what worked, what didn't and how I got around the problems or reframed the project.

It will also be a place to show off and explore some of github's project management features.


# The Development Log:

## An Idea
We have been building a Digital Cultures library in Zotero. Zotero works great for academic work, with its focus on metadata, but is a little clunky for websites. It stores the information well, but I want something that allows me to more quickly see all of the web projects stored in the library and have access to their links. This will also al

At the same time, I've been looking for an excuse to teach myself the basics of react.js. I did one quick tutorial at a workshop -- less than an hour-- and have been seeing it everywhere over the past few years. I know there are probably more lightweight and cutting-edge libraries, but react feels like a usable and well documented industry standard, so I'm going to start with that.

## Step 0 | Think this through a bit
The first thing I do when starting a project is think about it for hours while doing mundane tasks, then chat with friends and collaborators about the idea, then think about it for a few more hours. Eventually I will try to get the idea out of my head and onto paper so I can start to see what I want to achieve and *show* it to other people, rather than just describe what I'm doing.

Depending where I am, I might do this on paper (I am not "good" at drawing and have terrible handwriting, so this is not always ideal, but helps me focus and is fun), or use a program like "Freeform" on the Mac or "Visio" on Microsoft, or any other number of free, collaborative whiteboard platforms.

For this project, I made this:
![prototype design](/images/zotero_viewer_map.jpg)

> The sticky notes were faster than erasing when I realized I wanted to change how I was structuring the project.

## Step 1 | Get Set Up
I know this is going to be a start-and-stop process, so I want to get set up at the very beginning with organize files, this github repo, and readme.md document for keeping notes and chronicling as I go. 

## Step 2 | Zotero, or do I have the data?
I have a sense that zotero has RSS feeds or an API, or some way to get access to a live update of zotero library. But I'm not really sure what it is. So I start, of course, with google.

` Google: Zotero group library RSS feed `

Hmm, this mostly turns up how to **dd* RSS feeds to Zotero. Which is cool! And seems to mostly be about seeing the latest updates from journals, but not quite what I'm looking for here. New search.

` Google: Zotero API `

Aha! There is a well documented Api here:
[Zotero API Documentation](https://www.zotero.org/support/dev/web_api/v3/basics#general_parameters)

Some of this is above my head still, but looks like there is a way to get a JSON back, which I'm familiar with enough and guess will work with react, so will move on for now.

## Step 3 | Get React.JS set up

[Learn react](https://react.dev/learn) seems like a good place to start.

Apparently to get react.js working, I will need to have a basic grasp of node.js first, and maybe need to eventually learn some basics of next.js as well. 

### Step 3.a | detour to node
It seems like a lot of react documentation assumes that the coder is using **npm** the javascript project manager. 

I installed node.js and npm on my computer. Then started watching this tutorial on node.js after trying a few, since an hour seemed about the level of information I need at this point:
[Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://www.youtube.com/watch?v=TlB_eWDSMt4&t=2433s)

## Step 4 | TBC