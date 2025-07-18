---
title: "I Tried Every Text Editor So You Don't Have To"
excerpt: "A comprehensive review of 50+ text editors in 2025"
coverImage: "/assets/meme-text-editor.webp"
date: "2024-03-20T12:00:00.000Z"
author:
  name: Porter
  picture: "/assets/blog/authors/porter.jpeg"
ogImage:
  url: "/assets/blog/text-editors/cover.jpg"
---

# I Tried Every Text Editor So You Don't Have To

As a developer I am always looking for new ways to make my development process faster and easier to use. Recently I have been using the code editor you might of heard of it Cursor. Now cursor is great and all but... I actually as a engineer that has been developing for like 4+ years I haven't really even tried any other editors besides like vscode.

So in this blog post I will tell you my experience trying all the most popular editors. Starting from the lowest level to the highiest level of abstraction


## ed

Ed is an editor that was made a 1969 by Ken Thompson. I wanted to try this editor because I think it would give me some good perspective on how we used to develop software

I used ed for about 1 hour and I was able to pick up the basics of it somewhat quickly 

** Insert clip of creating hello world file with ed **


while it wasn't super inituive at first, had to inital watch a 10 minute video on how to edit stuff but after that it was all good

what I liked about ed is really made me think about my edits really hard lol 

atleast a lot more than I have ever had with vscode

When editing in the ed editor you actually can't see any text intially
In order to see stuff you need to type `,n` or `,p` to print the file with line numbers or just print without
I would usually do with line numbers
you can also print the line you are on by just doing `p` or `n`

I won't go into too much details on this editor if you want to 

But i did liek some things in it

Now I really wanted to test each editor by makng a piece of software so I wanted to make a blog site and the site you are
hi
,n
I am actually writing some of this blog in ed as we speak now one thing. Now how I made this blog is I just downlaoded a template for getting the blog and I initally got it and wanted to trtyeditng some of the text in the blog speciffally the data.ts file. In here we have feilds with this I replcaed thme with my name and it was somewhat easy it took me like 30 minutess to edit all the liens since was still learning how to save edit and quit. The most useful and coolest feature is the edit feature being able to selefct like 23s/no/yes was really really nice . I thoguhit was awesome it also made me use my command line more like greping for text to find contact me email to replcae i nthis tempalte. So I used this for about an hour and I was able to get pretty rfar so ed is reallyt far but there was a big problem i had which was formating 

when formating the text I couldn't really edit the things and I wuld have no dnationts

show edample of indation here

this kind of sucked and i had to first print lines to see them 


copy the indentaitons paste them and thne add my chagne

this wasn't a prohblenm though with the replcae funciton so I would usually replaec the text

another thing i liked was the delete doing like 10,25d and that deltes the lines isntnatly was sick

its super fast
not like vscode sometging where my eslint or something take like 3 secodns if big codebase lol 



## What I liked about ed
it's simple

when i open vscode there is soooo many features in there. I have been using it for years and I still find feature i am not using. While this is good I think it is really something in life to kind of have a tool just made for doing that thing. Want to edit a line and change the text of something in ed well in ed you can just do that in one line:

```zsh
$ ed hello.txt
5p
contact me at hello@world.com
5s/hello@world.com/portersmith.dev/
w
q
```


and bang you just edited that text pretty cool

now... besides replcaing is pretty nice but adding stuff with idnatiton is really hard.. 
this icause ed is really not made for text editing with fomating 


** instert formating of ed in 1969 * 

this si somse code in 1969 and as you fcan see there is no tabbing so editng my 
another thing i wanted to say is when editing it made me use more tools to counter act not having them for exmaple in vscode you have temrinal and and editor section so i started learning emacs and using ls and cd to move into diractiors and as talked before i started learning grep which I haven't used before to replace ctrl f find all basically so I bacilly had all the same things I had in other editor like vscode
hi
one big problem I havev found with ed is basically I can't really go back lol so if you make a mistake you have to either undo or just dlete like or replace thing you miss spelled can't go new go back with arrow keys according to a quick chatgpt response is it says "This limitation exists because ed was designed for teletypes and terminals that couldn't move the cursor backwards. It predates screen-based editors by decades." so ya thayt is that now we will go to the next editor and hoepfuilyl my formating is better lol. 
