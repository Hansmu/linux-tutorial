# Shortcuts and history

Clear screen - ``CTRL + L``

Go to the start of a line - ``CTRL + A``

Go to the end of a line - ``CTRL + E``

Move forward (like using the right arrow key) - ``CTRL + F``

To jump words - ``ALT + F``

Move back (like using the left arrow key) - ``CTRL + B``

To jump words - ``ALT + B``

To swap characters in text where your cursor is - ``CTRL + T``

To swap words where your cursor is - ``ALT + T``

To remove from your cursor to the end - ``CTRL + K``

To remove from your cursor to the start - ``CTRL + U``

To delete from your cursor to the end of the word - ``ALT + D``

To delete a letter - `CTRL + D`

To delete from your cursor to the start of the word - `CTRL + W`

When deleting text, then it goes into the kill ring, you can retrieve things from it using `CTRL + Y`

## History

The `history` command can be used to see the previous commands that you've run.

To rerun a command from the history, you can use `!<lineNumber>`. So for example:
```
!74
```

To search through the history - ``CTRL + R``.
Keep pressing ``CTRL + R`` to cycle through the commands that match your search term.

History itself is stored in the home directory. `~/.bash_history`.

There are some properties to modify the stored amount of commands:
* ``$HISTFILESIZE`` - how many commands are stored in the history file. Default being 2000 commands.
* ``$HISTSIZE`` - how many are stored in working memory. Shows the most recent commands that fit into that range. So default the latest 1000 commands.