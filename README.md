# TodoMVC with calendar in Elm - [Try It!](http://melvm-test.tk/elm/todo.html)

## Project Structure

All of the Elm code lives in `Todo.elm` and relies on the [elm-html][] library. 

[elm-html]: http://package.elm-lang.org/packages/evancz/elm-html/latest 

There also is a port handler set up in `index.html` to set the focus on
particular text fields when necessary.

## Build Instructions

Run the following command from the root of this project:

```bash
elm-make Todo.elm --output elm.js
```

Then open `index.html` in your browser!
