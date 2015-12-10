homebrew-fastcommands
---------------------

_homebrew-fastcommands_ is an experimental tap for implementing a select
number of homebrew commands in pure [~~bash~~ shell command language](http://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html) to improve performance.

Contributions are welcome, but note:

- If your command replaces an existing implementation, it should at very least:
  - never be slower that the corresponding ruby implementation
  - not significantly increase code complexity or add significant new features
  - not use anything non-portable "bashisms" or "kshisms"

