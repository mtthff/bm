## BM

  Simple bash CLI bookmarks with tag support
  This is a fork that removes everything unneccessary.
  Like DropBox, Previews.

  Also modified default behavior, replaced description with date field.


## Install

```
$ make install
$ make uninstall
```

## Example

  Add a bookmark:

    $ bm add http://subtlepatterns.com design textures

  Open it later:

    $ bm subtle

## Usage

```

Usage: bm [options] [cmd]

Commands:

  # add a bookmark with the given url and optional tags
  $ bm add <url> [tag...]

  # open the first bookmark matching <query>
  $ bm open <query>
  $ bm <query>

  # search the bookmarks via full-text <query>
  $ bm search <query>

  # list bookmarks available
  $ bm list
  $ bm ls
  $ bm

Options:

   -V, --version   output bm version
   -h, --help      output this help information

```

File Stucture

```
$ cat ~/.bookmarks
https://kippt.com|clean white design
http://subtlepatterns.com|design textures
http://www.uiparade.com|design ui
```
