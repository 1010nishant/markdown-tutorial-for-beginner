# Ultimate Guide For Markdown
- Markdown is a lightweight markup language with plain text formatting syntax. 
- It is designed to be easy to read and write, and to convert to HTML and other formats. 
- Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.
### We can create a file with different extensions for markdown files

- **.markdown**
- .md
- .mkd
- .mkdown
- .text
- .mdown
  
GitHub uses the standard file extension as **.md**
### Comment in Markdown
`<!--- Wrap text --->`
### Code Blocks
To write longer or more detailed snippets of code, it is often better to place them inside a code block.
To achieve this, start your block with a line of three backticks. This signals to markdown that you are creating a code block. You will need to finish with another line of three backticks. For example:

<img width="453" alt="Screenshot 2023-05-01 at 11 20 49 PM" src="https://user-images.githubusercontent.com/88904952/235500547-98e52522-31a4-4e73-8661-d85c942f3a72.png">

will render in markdown as:
```
var add2 = function(number) {
  return number + 2;
}
```
### Syntax highlighting
While not supported natively by markdown, many markdown engines, including the one used by GitHub, will support syntax highlighting. This means that by telling markdown what language you're using inside the code block, it will add colors like an IDE would. For example:

<img width="345" alt="Screenshot 2023-05-01 at 11 24 15 PM" src="https://user-images.githubusercontent.com/88904952/235501118-3c6f5fa7-416a-4f63-946b-45581fbb417a.png">

will render in markdown as:
```js
var add2 = function(number) {
  return number + 2;
}
```

