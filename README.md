# __Learning Markdown__
[![logo](https://appstore.home.mendix.com/logo/image?id=13359&changeddate=1415798995770)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwiLloKi3dThAhXadn0KHeAMC7YQFjACegQIDRAK&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FMarkdown&usg=AOvVaw29vUwtb3gVG6rhYhCaDfbr)
## Understanding of a concept begins from the definition of that concept
>Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML)..
                                                            ![](http://d3g9pb5nvr3u7.cloudfront.net/authors/530f8d77a968b97107b613f5/1383334665/256.png)
                                                            As said by John Gruber
                                                            Co-Founder of Markdown.
Markdown can be written in a basic text editor (don't use Word) like TextEdit for Mac (save as plain-text) or Notepad on Windows. It's an easy way to write text that easily translates into HTML. The web is written in HTML, so think of it like quick-start web development tool for content editors. When you write in Markdown, you save the document with the file extension .md. More often than not, you'll never need to save a Markdown document, because you'll be using an online tool.

### Well that was pretty simple,but why do we really need markdown?
Writers and publishers know the value of “flow” and how writing without distractions can help put thoughts into words efficiently. Picking up the mouse, selecting the text, hovering the mouse over to the bold icon and coming back to the keyboard, all end up disrupting the creative flow and create a disjointed experience. When you are “in the zone,” small interruptions like these can put off your writing.

Markdown gets rid of all the distractions of a formatting toolbar and mouse clicks by helping you focus on your writing without lifting your fingers off of the keyboard. Advanced writers love this kind of seamless experience which allows them to stylize their text on the fly.

 You could argue that clicking on the “bold” button is easier than writing a bunch of special characters, and for the most part, you are right. For an average user, Markdown may not seem to be as useful as it claims to be. However, the real magic appears when you get a hold of it. When you get past the slight learning curve, writing becomes that much faster and easier. You might never want to see a toolbar ever again.
 
Since Markdown is just plain text, it can be exported to a variety of applications and can be converted into a bunch of formats like PDF, epub, Docx, HTML, etc. You don’t need to worry about formatting, just start writing and export your document once you are done.

## Tools you need or probably don't
Most of you are using VsCode and it has inbuilt markdown functionality.For more info on this go [here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwiuwsPp4dThAhUJvo8KHee7DqYQFjAAegQIAxAB&url=https%3A%2F%2Fcode.visualstudio.com%2Fdocs%2Flanguages%2Fmarkdown&usg=AOvVaw3NgA89NiPOyA3JKf7DYaxq)
And for those of you using Sublime Text there are 2 plugins which will be helpful-->MarkdownEditor and MarkdownLivePreview.

The easiest way to start learning markdown without anything is an online markdown editor called Dillinger.[GO HERE](https://dillinger.io/)

!!BELOW ARE SOME TOOLS FOR PURE MARKDOWN AND ARE NOT NECESSARY UNLESS YOU ARE WRITING CONTENT PURELY IN MARKDOWN!!

- ReText for linux users [get it here](http://sourceforge.net/p/retext/home/ReText/).
- Mou for Mac users but if you have updated to Mojave you gotta pay [get it here](http://mouapp.com/).
- Marked is a tool providing live preview as you write in any text editor.
 
## SYNTAX
We will be focusing mainly on GFM or Github Flavoured Markdown which is markdown but with added functionality from github.It's really all about looking it up multiple times in cheat sheets as and when you need it and eventually you'll be a pro at it
Some links to useful resources are:

  * [Main Documentation](https://daringfireball.net/projects/markdown/syntax)
  * [Github's syntax sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

### Text in markdown
`It's very easy to make some words **bold** and other words *italic* with Markdown.`
`**BOLD1** __BOLD2__ __*BOLD + ITALIC*__ `
~~~
# this is a h1 tag
## this is a h2 tag
### this is a h3 tag
#### this is a h4 tag
##### this is a h5 tag
###### this is a h6 tag
~~~


It's very easy to make some words **bold** and other words *italic* with Markdown.
**BOLD** __BOLD2__ __*BOLD + ITALIC*__ 
# this is a h1 tag
## this is a h2 tag
### this is a h3 tag
#### this is a h4 tag
##### this is a h5 tag
###### this is a h6 tag

#### Blockquotes
~~~
>Markdown is cool and you who is trying to master it is cooler
Begin the second level of blockquotes
>
>>Me
>
End the second level of blockquotes
~~~

>Markdown is cool and you who is trying to master it is cooler
>
>>Me
>

You can use an Horizontal line easily like this
`* * *` or `***` which will result in

***

#### LISTS

~~~
Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
~~~

Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

#### CODE IN MARKDOWN

This is where Github flavoured markdown really comes into play.Syntax highlighitng for multiple languages and is really easy to implement.

Inline code is written by enclosing in backticks.
Multi line code is enclosed in ``` code ```
```language name
code
``` 
for syntax highlighting

