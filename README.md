curry-interface
===============

This package contains libraries to represent and read interfaces of
Curry modules which are usually generated by the Curry front end and
stored in files with suffix `.icurry`.

The structure of these interfaces is defined in the module
`CurryInterface.Types`.
The module `CurryInterface.Files` contains operations to read `.icurry` files
and returns the structure of the interface.

The module `CurryInterface.Pretty` contains pretty-printing operations
for interfaces, parameterized with various options.
These are used in the tool `curry-showinterface`, generated when
installing this package, to print the interface of a Curry module.
This tool is used in Curry REPLs to implement the command `:interface`.

