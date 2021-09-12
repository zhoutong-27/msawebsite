```shell
$ python jemdoc
Usage: jemdoc [OPTIONS] [SOURCEFILE]
  Produces html markup from a jemdoc SOURCEFILE.

  Most of the time you can use jemdoc without any additional flags.
  For example, typing

jemdoc index

  will produce an index.html from index.jemdoc, using a default
  configuration.

  Some configuration options can be overridden by specifying a
  configuration file.  You can use

jemdoc --show-config

  to print a sample configuration file (which includes all of the
  default options). Any or all of the configuration [blocks] can be
  overwritten by including them in a configuration file, and running,
  for example,

jemdoc -c mywebsite.conf index.jemdoc

  You can view version and installation details with

jemdoc --version

  See http://jemdoc.jaboc.net/ for many more details.

$ python jemdoc -c mysite.conf *.jemdoc
```