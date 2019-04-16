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
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

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
Multi line code is enclosed by ```
~~~
```language name
code
``` 
~~~
for syntax highlighting

![code](https://github.com/ieeecscet/Markdown/blob/master/Screenshot%202019-04-16%20at%2010.40.04%20PM.png)

Markdown and `print('code')` go hand in hand

```
x=[a for a in x if a>1]
for i in x:
    if i<1:
        print("Python doesn't work")
```

```python
x=[a for a in x if a>1]
for i in x:
    if i<1:
        print("Python doesn't work")
```

#### Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

![code](https://github.com/psycholoony/Markdown/blob/master/Screenshot%202019-04-16%20at%2010.58.58%20PM.png)

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

#### Images

We can get cool images like this one using the syntax
`![alternate txt](url)`

![cool](https://www.indiewire.com/wp-content/uploads/2017/10/matrix-code.jpg?w=780)

#### Links

We can have inline links like this-> `hello this is an [example link](http://example.com)`

## hello this is an [example link](http://example.com)

We can also have images as links as we can see from this example where the illuminati symbol leads us to the wiki page of the illuminati.
The syntax is:
`[![alt txt](url)](link url)`

[![ill](https://static.thenounproject.com/png/499640-200.png)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwjLvpLWl9XhAhWBOI8KHfkFBs8QFjAAegQIABAB&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FIlluminati&usg=AOvVaw2dwWxpMAucEncxEfzti0Qb)

#### EXTRAS

GitHub supports emoji so go crazy
### :+1: :sparkles: :camel: :tada:
### :rocket: :metal: :octocat:

[THIS IS THE EMOJI CHEAT SHEET](www.emoji-cheat-sheet.com)

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization

#### Task Lists

This is how you make task lists

![code](https://github.com/psycholoony/Markdown/blob/master/Screenshot%202019-04-16%20at%2011.38.18%20PM.png)


- [x] This is a complete item
- [ ] This is an incomplete item

### Well hopefully you have been convinced that learning Markdown is useful and you have got a good idea as to how to use it.The mentioned resources are more comprehensive and are a great reference while working with Markdown.Happy coding!
