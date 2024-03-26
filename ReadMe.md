# ULookUp
### aka Useful Lookup with Language Models
Select text on any website, right click and select 'ULookUp' and get realtime explainations. You know, like Apple's LookUp feature, but, Useful.

![](uLookup_demo.gif)

## What is this?
This is a search-with-language models tool. Instead of having to open a new tab, navigate to google.com, search press enter, read, come back to the original page -> Just right click selected text and select uLookup, and voila! you have your generated definition right there! Click anywhere else on the page to get rid of the floating pop-up.

What's more cool is that you get definitions and explanations depending on the context of the page you're reading! For example - if you're reading about movies, searching for 'matrix' will bring up the matrix movie franchise versus when reading about a maths concept searching for the same word with define a collection of numbers.

## How does it work?
This is a chromimum based extension written in Javascript, HTML and CSS. The definition/explanation is generated by Athropic's Haiku model. The extension calls the API with the word you want explained along with the context it occurs in.

## Cool! Can I use this too?
Yes! As long as you have an Anthropic API key!
- git clone this repo
- open your favourite chromimum browser (chrome, brave, edge etc)
- navigate to extension settings by typing "chrome://extensions" in the url bar
- on the top right corner turn on "Developer Tools"
- on the top left corner, select "Load Unpacked"
- select the folder in which you cloned this repo, and you're done!

PS - once the extension is loaded, click on the extension icon the extension menu and add your anthropic API key in the input field
