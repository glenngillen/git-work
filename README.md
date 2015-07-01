# Git Work

Use git to remember what you've been working on.

## Usage

```bash
$ git-work

/git-work
================================
+---------+--------------+--------------------+--------------------------------+
| 36ccfb5 | 01-Jul 16:21 | me@glenngillen.com | Add the most basic of READMEs. |
| 47d70cf | 01-Jul 16:19 | me@glenngillen.com | Initial attempt at script.     |
| 683137a | 01-Jul 16:18 | me@glenngillen.com | Initial commit                 |
+---------+--------------+--------------------+--------------------------------+
```

It currently assumes all of your projects live in `~/dev`
like mine do.

## Dependencies

You'll need the following gems installed:

* git
* terminal-table

```bash
bundle install git terminal-table
```
