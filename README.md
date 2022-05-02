# Quickstart Using the Alien RPG CSS and Markdown in Roll20

## Part 1 - Install the API Scripts on Roll20
You will need to either have an exisiting game on Roll20, or create a new game.

Visit this link https://app.roll20.net/forum/post/8028597/script-markdown-handouts-and-bios/?pagenum=1 and install the three API scripts to the game you wish to use them with:
- markdown.js https://gist.github.com/BaldarSilveraxe/0eaaf6fafe8cef89c73fb89c6f37d563
- markdownNotesBio.js https://gist.github.com/BaldarSilveraxe/1002a65dd6e2613c8d38edc1f6005990
- markdownDocumentation.js https://gist.github.com/BaldarSilveraxe/5a1db1db88890ff2de0b94b57557f8c3

Installing API scripts on Roll20 is beyond the scope of this documentation, please visit https://help.roll20.net/hc/en-us/articles/360037256714-API#API-HowdoIinstallanAPIscriptifIwanttowritemyowncodeorIwanttousecodefromanexternalsource?

## Part 2 - Using the Markdown in a Roll20 Game
Once you have installed the API scripts, launch the game on Roll20. Follow the steps below to start using the markdown styling in-game.

### Getting Started
Create a new **"Handout"** named **"Style Sheet"** and in the **"GM Notes"** place:
```
[css]
h1 {color: red;}
```
**Save changes.**
In the **"Description & Notes"** section you should see the processed **CSS**
```
[css](-LxpMeYSNUYwZIVXxguT)
h1 {color: red;}
```
> **NOTE:** The "-LxpMeYSNUYwZIVXxguT"` part is the object id for your handout. It will not be the same as you see in this example.
That is the "link" for this style sheet. ***Copy*** *it to the clipboard.*
Create a new **"Handout"** named **"Markdown Handout"** and in the **"GM Notes"** place:
```
[md]
[css](-LxpMeYSNUYwZIVXxguT)
# This Heading should be red.
```
(You should ***paste*** in what you *copied to the clipboard* to the second line.)
> **NOTE:** The "-LxpMeYSNUYwZIVXxguT"` part is the object id for your handout. It will not be the same as you see in this example.
**Save changes.**
In the **"Description & Notes"** section you should see the processed **Markdown.**
It should be large red text reading:
<span style="font-size: 2em; font-weight: bolder; color: red;">This Heading should be red.</span>
(if you tire of the "Getting Started" or "Example" handouts, delete this script or archive the handouts.)

### Switching to Alien RPG Styling
If all has worked correctly in the previous steps, do the following.


