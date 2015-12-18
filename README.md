# the Zettelkasten Wiki Package #

This is a package for the Atom editor that enables wiki style links, `[[Like This]]`.  Right now there are only two thinks you can do with this:

1. `ctrl+enter` follows the link under the cursor to the note with that name in your note directory (which must be filled in under settings).
2. The package provides autocomplete suggestions for note titles to the autocomplete-plus package when you begin typing a link.

Right now, the link following only works if you have the proper wiki link scope and this requires my Academic Markdown syntax package.  It would be nice if there were an independent way to figure out whether the cursor is in a link or not.