# Unix ASCII games

[![Build Status](https://travis-ci.org/ligurio/ttygames.svg?branch=master)](https://travis-ci.org/ligurio/ttygames)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a source of [https://bronevichok.ru/ttygames/](https://bronevichok.ru/ttygames/).
Feel free to submit pull requests to add new games and improve information about
those already in the database.

## How to contribute

Check `games.yaml` out. All information is inside, and you should more or less
understand what's going on by reading it. Sorting is alphabetical.

Simplest way to contribute: edit [games.yaml](/games.yaml), and then
your changes will be submitted as a pull request.

Use this template:

```
- name: hangman
  url: http://www.openbsd.org/cgi-bin/man.cgi/OpenBSD-current/man6/hangman.6?query=hangman&sec=6&arch=i386
  info: computer version of the game hangman
  screencast:
  play:
```

- `name`: Name of the game
- `url`: URL of main page
- `info`: free text with game description
- `screencast`: link to screencast (for example on asciinema)
- `play`: server hostname where game is available via telnet or ssh

## License

[![CC0 Public Domain](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sergey Bronnikov](https://bronevichok.ru) has
waived all copyright and related or neighboring rights to this work.
