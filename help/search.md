# Search

The search plugin provides easy searching for the word under cursor
or a selected text, with just one keystroke. Also it provides easy
searching for the word upon a mouse click on this word (this feature is
inspired by Acme editor).

Pressing `Alt-s` will search for the next occurrence of the word under
the cursor. If there is a text selection, it will search for the
selected text instead.

You can bind it to some other key instead of `Alt-s` if you like, by
modifying the default binding in your `bindings.json` file:

```json
{
    "Alt-g": "lua:search.searchWord"
}
```

Clicking the right mouse button on a word will search for the next
occurrence of this word. If there is no word under the mouse click,
it will unhighlight the current search.

You can bind it to some other mouse button instead of the right button,
by modifying the default binding in your `bindings.json` file:

```json
{
    "Alt-MouseLeft": "lua:search.searchClick"
}
```
