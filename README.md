```javascript
+++++++++++++++++
++++  TEXTS  ++++
+++++++++++++++++
```

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

~~this~~ will appear crossed out.

It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)
```javascript
++++++++++++++++++++++++++++
++++  HORIZONTAL RULES  ++++
++++++++++++++++++++++++++++
```
You could add horizontal rules with 3 characters or more;

Aterisks, `***` becomes:

***

Underscores, `____` becomes:

____

Dashes, `----` becomes:

----
Equals sign, `====` becomes:

====

Also with dash and equals sign, if you don't put space between characters and upper line:

It becomes dashed title
---

```javascript
+++++++++++++++++
++++  LISTS  ++++
+++++++++++++++++
```
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
    - And maybe this?
    - Yes it works.
      - But no more?
      - Yessss it still works.
        - Is it still working?
          - Yes
            - But I'm bored of squares...
  
```javascript
++++++++++++++++++++++
++++  TASK LISTS  ++++
++++++++++++++++++++++
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

```javascript
++++++++++++++++++
++++  TABLES  ++++
++++++++++++++++++
```
You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
a | b

```javascript
++++++++++++++++++
++++  IMAGES  ++++
++++++++++++++++++
```
If you want to embed images, this is how you do it:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```javascript
++++++++++++++++++++++++++++
++++  HEADERS & QUOTAS  ++++
++++++++++++++++++++++++++++
```
```-----------------------------------------------------------------------------------------------```

# Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

```javascript
++++++++++++++++++
++++  CODE<3  ++++
++++++++++++++++++
```

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
```

```javascript
++++++++++++++++++
++++  EXTRAS  ++++
++++++++++++++++++
```
 
GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

And, of course emoji! :sparkles: :camel: :boom: :kissing_heart: :sweat_smile: :sunglasses: :earth_africa: :earth_americas: :earth_asia:

:waxing_crescent_moon:  :first_quarter_moon:  :waxing_gibbous_moon:  :sunglasses:  :waning_gibbous_moon:  :last_quarter_moon:  :waning_crescent_moon:
