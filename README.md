# man2html

Convert manpages to HTML documents.

## Usage

`man2html` takes the name of a manpage as an argument, so you do not need to specify the manroff file directly.

```
$ man2html ls
```

`man2html` always outputs to stdout. You can save the generated html page using output redirection in your shell, like this:
```
$ manhtml ls > ls_manpage.html
```

## Installation

Copy the script somewhere in your $PATH.

```
git clone "https://github.com/spitemim/man2html"
cd man2html
cp man2html ~/.local/bin/
```

## License

This project is licensed under the GNU General Public License, version 3.
