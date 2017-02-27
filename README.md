# jfast-tools
Tools for the jFAST application.

For more information about jFAST see http://www.gtt-online.de/de/fast-entwicklungswerkzeuge/

## jlog
`jlog` is a Windows PowerShell command line tool to examine a jFAST user logfile. It outputs relevant information as database connections, user login, exceptions etc.

By default `jlog` uses the logfile written by the newest instance (if several applications are active at the same time). This behaviour may be modified with the options `-w` (Last Write Time) or `-l` (provides an explicit logfile name).

A special function is available via the option `-ls`. This option lists all jfast logfiles from the users current TEMP directory. It may be combined with the options `-w` and `-t` (or `-Tail`).

The option `-h` (or `-Help`) lists all available commands as a man page.
