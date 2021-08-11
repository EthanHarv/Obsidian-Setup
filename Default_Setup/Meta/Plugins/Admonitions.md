---

tags: meta plugins

---

# Admonitions

They're little blocks!

```ad-abstract
title: Definition
collapse: open

Hi! This is an admonition.

Try closing me!

$$e=mc^2\ \text{(Nested }\LaTeX\text{!)}$$

!!! ad-note
    title: Nested!
    collapse: closed
    You can also have nested ones, but it can be funky, so I don't usually do this. 
    
    Oh yeah also you can have them closed by default, like this one.
    
😎

```

## Creating one

I recommend, for any common admonition types you find yourself using, to create a [[Templater|template]] for it.
I've created an example template, [[Definition]], which I do actually use (and quite often!).

This makes it an incredibly easy, hands-off process, so you don't have to remember all the syntax and you can just press `Ctrl+E`, type "definition", and boom you have one.

If you want to learn more about how to actually make different types, reference the [github page](https://github.com/valentine195/obsidian-admonition).