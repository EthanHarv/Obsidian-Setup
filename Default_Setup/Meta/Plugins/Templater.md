---

tags: meta plugins

---

# Templater

Templates!

The easiest way to add templates is with the keybind, `Alt+E`. Get used to this one!

## Making a template

If you're making a basic, text-only template, you can just chuck a note into the `_Templates` folder and it'll add it to the list.

There are many advanced options, which I will point you to [the github](https://github.com/SilentVoid13/Templater) to learn most of, but some of the basic ones are:

- Get Current Date
    - `<% tp.date.now("YYYY-MM-DD") %>`
- File Title
    -  `<% tp.file.title %>`
- Place Cursor (Where it'll select/put your caret after it inserts the template)
    - `<% tp.file.cursor(1) %>`