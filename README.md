# love.yml

Converts the [love-api](https://github.com/love2d-community/love-api) to a `love.yml` file for use with the [selene](https://github.com/Kampfkarren/selene) linter.

## Usage

If you're using VS Code the easiest way to use selene with your project it with the [extension.](https://marketplace.visualstudio.com/items?itemName=Kampfkarren.selene-vscode)

- Save the [`love.yml`](https://raw.githubusercontent.com/jacob-herrera/love.yml/main/love.yml) file into your LÖVE project's directory.
- In that same directory, modify or create the `selene.toml` file with the following: 
```toml
std="lua51+love"
```

## Building

Building a `love.yml` file for an older version of the LÖVE API is very simple.

- Clone the repo (or just copy [main.lua](https://raw.githubusercontent.com/jacob-herrera/love.yml/main/main.lua))
```
git clone https://github.com/jacob-herrera/love.yml
```

- Download an earlier version from the love-api [releases](https://github.com/love2d-community/love-api/releases)

- Place the `love_api.lua` and `modules` folder from the love-api into the repo

- Run the lua file with:

```
lua main.lua
```
