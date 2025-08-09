# codex

Codex is a static site generator and blog template powered by 
[letdown](https://github.com/goneal26/letdown).

## Requirements

All you need is Lua and Bash.

## Usage

All `.let` files and media attachments go in the `src` folder. Running 
`just build` (or simply `just`) will convert all of the `.let` files into HTML, 
using the base `template.html` file and `style.css` file in the repository root
directory.
