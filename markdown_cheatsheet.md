# Markdown Cheatsheet
___
This cheatsheet is meant to be a quick reference to everyday Markdown. For a more detailed list I like [markdown-it demo](https://markdown-it.github.io/).
## Headings
\# Heading 1
<br>
\## Heading 2
<br>
\### Heading 3
<br>
\#### Heading 4
<br>
\##### Heading 5
<br>
\###### Heading 6
<br><br>
Remember headings have semantic meaning. If you just are looking for **BOLD** text, use styling instead.
## Text Styles
**BOLD TEXT**
<br>
\*\*This is BOLD Text\*\*
<br>
\-\-This is BOLD Text\-\-
<br>
\_\_This is BOLD Text\_\_
<br><br>
*Italic Text*
<br>
\*This is Italic Text\*
<br>
\_This is Italic Text\_
<br><br>
How to Make a ~STRIKETHROUGH~
<br>
\~This Is a Strikethrough\~
<br>
## Ordered and Unordered Lists
&ensp;
\* Use an asterisk to make an start an unordered list
<br>
&ensp;
\* Then another one for another another bullet point
<br>
&emsp;&emsp;\* Use **Two** spaces before your asterisk to create a sublist
<br>
```md
1. To make a ordered list use numbers like this
2. Use as many as you need
3. Just one more
```
Let's see an example of a list in Markdown!
- Here is what a Markdown list looks like
  - This is a sublist item
    - Another sublist
- This list was made with a `-`
1. Now an ordered Lists
2. You can use sequential numbers
3. Use sequential numbers


## Inline and Code Block
For inline code wrap the code in  \`backticks\`
<br><br>
\```
<br>
Wrap your code like this for code block
<br>
\```
<br>
If you'd like to use syntax highlighting specify the language specify the language after the first three backticks. Like this \```js or \```css
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
![Strawberries](/jeremy-bezanger-unsplash.jpg)Jeremy Bezanger Made This
## Block Quotes
For a block quote
<br>
&emsp;
\> Use a greater-then sign
<br>
Your block quote will look like This
> Here is some stuff that someone said
>> And some more stuff using `>>`

### Other Stuff
* You can escape a character with a `\` for example `\*`
* Need a line break? Use `<br>`
* Some HTML may be supported
