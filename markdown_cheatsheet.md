# Markdown Cheatsheet

[Headings](#headings)
<br>
[Horizontal Rules](#horizontal-rules)
<br>
[Ordered and Unordered Lists](#ordered-and-unordered-lists)
<br>
[Inline Code and Code Block](#inline-code-and-code-block)
<br>
[links](#links)
<br>
[Images](#images)
<br>
[Block Quotes](#block-quotes)
<br>
[Other Stuff](#other-stuff)
___
This cheatsheet is meant to be a quick reference to everyday Markdown. For a more detailed list I like [markdown-it demo](https://markdown-it.github.io)
<br><br>
## Headings
`#` Heading 1
<br>
`##` Heading 2
<br>
`###` Heading 3
<br>
`####` Heading 4
<br>
`#####` Heading 5
<br>
`######` Heading 6
<br><br>
Remember headings have semantic meaning. If you just are looking for **BOLD** text, use styling instead.

## Horizontal Rules
`---` or `___` or `***`
<br>
Those options will all look the same, like the one at the top of this sheet.

## Text Styles
**BOLD TEXT**
<br>
`**`This is BOLD Text`**`
<br>
`--`This is BOLD Text`--`
<br>
`__`This is BOLD Text`__`
<br><br>
*Italic Text*
<br>
`*`This is Italic Text`*`
<br>
`_`This is Italic Text`_`
<br><br>
~STRIKETHROUGH~
<br>
`~`This Is a Strikethrough`~`
<br>
## Ordered and Unordered Lists
&ensp;
`*` Use an asterisk to make an start an unordered list
<br>
&ensp;
`*` Then another one for another another bullet point
<br>
&emsp;&emsp;`*` Use **Two** spaces before your asterisk to create a sublist
<br>
&emsp;&emsp;`*`It would look the same with `*`, `-`, or `+`
<br>
&emsp;&emsp;&emsp;`*`Use **four** spaces to go one sublist deeper
<br>
```md
1. To make a ordered list use numbers like this
2. Use as many as you need
3. Just one more
```
**Let's see an example of a list in Markdown!**
- Here is what a Markdown list looks like
  - This is a sublist item
    - Another sublist
- This list was made with a `-`
1. Now an ordered Lists
2. You should use sequential numbers
3. It doesn't need to start at `1.`


## Inline Code and Code Block
For inline code wrap the code in \`back-ticks\`
<br><br>
\```
<br>
Wrap your code in three back-ticks before and after for code block
<br>
\```
<br>
If you'd like to use syntax highlighting specify the language after the first three back-ticks. Like this \```js or \```css
```js
var itWillLook = "Like this";
var dog = "cute";
```
```css
.or-like-this {
  color: blue;
  padding: 20px;
}
```
## Links
You can make an inline link like this [Your Link](https://github.com/)
```
[Your Link](https://github.com/)
```
## Images
If you'd like to include a image you can. It would look like this
```
![Strawberries](/jeremy-bezanger-unsplash.jpg)
```
![Strawberries](/jeremy-bezanger-unsplash.jpg)
<br>
*Jeremy Bezanger* Made This
<br>
Drag and drop an image into the comment section of a gist on GitHub to make a link to the image. The image used here is being linked with a directory path because the source is inside this directory.

## Block Quotes
For a block quote
<br>
&emsp;
`>` Use a greater-then sign
<br>
Your block quote will look like This
> Here is some stuff that someone said
>> And some more stuff using `>>`

### Other Stuff
* You can escape a character with a `\` for example `\*` looks like \*
* Need a line break? Use `<br>`
* Some HTML may be supported
