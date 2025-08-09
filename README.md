# codex

Codex is a static site generator and blog template powered by 
[letdown](https://github.com/goneal26/letdown).

## Setup

All you need is Lua and Bash.

First, clone the repo:

```bash
git clone --recurse-submodules https://github.com/goneal26/codex.git
cd codex
```

Verify the submodule is set up:

```bash
git submodule status
```

You should see a commit hash.

## Usage

Just start writing letdown files in the `src` directory!

All `.let` files and media attachments go in the `src` folder. Running 
`source build.sh` will convert all of the `.let` files into HTML, using the 
base `template.html` file and `style.css` file in the repository root folder.

All output HTML files can be found in an `html` directory, which gets ignored by
the repository's `.gitignore`. If you're hosting this site using something like
Neocities, this `html` directory is what you'll want to upload.
