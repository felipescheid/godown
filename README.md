## GODOWN (WIP)

Godown is a markdown parser written in Go. I will use it to convert my blog posts from markdown to html.

### Project structure

`cmd` main application files


`internal` - packages that should not be imported by other projects

`pkg` - public API

### Project plan

- [ ] Implement a lexer to tokenize the input Markdown text and identify different Markdown elements

- [ ] Create an abstract syntax tree (AST) to define node types for different markdown elements and parse tokens into an AST structure

- [ ] Implement an HTML renderer to traverse the AST and genereate corresponding HTML for each node type

- [ ] Develop the main program to read input markdown files, coordinate lexing, parsing and rendering and output HTML files

- [ ] Implement error handling and edge cases

- [ ] Write tests

### Supported features

I will start first with basic markdown features:

- Headers
- Paragraphs
- Bold/italic text
- Links
- Lists

After this is implemented, I will move on to:

- Code blocks
- Blockquotes
- Tables
- Images
