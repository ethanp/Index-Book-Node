# Index-Book-Node

> Turn Gutenberg book into an index and provide access to user

This is a *Node.js/Express.js/Jade* project that downloads Alice in Wonderland from Project Gutenberg,
builds an index `{word: [line_numbers]}` and `[lines]` and allows you to interactively
use this index to see the lines containing the word you enter into the search box.

The meat is in [this JavaScript file][meat].

[meat]: https://github.com/ethanp/Index-Book-Node/blob/master/TextProc/public/javascripts/bookIndex.js
