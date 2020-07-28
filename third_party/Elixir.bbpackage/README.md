# Elixir Package for BBEdit #

BBEdit Language support for [Elixir](http://elixir-lang.org):

* Codeless Language Module for syntax highlighting and function folding
* Clippings for common Elixir structures (using 2-space indents, per common Elixir coding style)

## Installation ##


1. Clone this  repository to `Elixir.bbpackage`:

        git clone https://github.com/chipotle/elixir_bbedit.git Elixir.bbpackage

2. Open the Application Support directory. This will be `~/Library/Application Support/BBEdit` or, if you're using BBEdit's Dropbox support, `~Dropbox/Application Support/BBEdit`.

3. If the `Packages` directory doesn't exist in `Application Support`, create it.

4. Copy `Elixir.bbpackage` to `Packages`.

You can also clone the repository (step 1) directly to `Packages` if you prefer.

## Provided Clippings ##

* case
* def
* defmacro
* defmodule
* defp
* do
* fn
* function
* test

## Credits ##

Originally written by David H. Clements ([@dclements](https://github.com/dclements)).

Updated for Elixir 1.6 and BBEdit 11+ by Watts Martin ([@chipotle](https://github.com/chipotle)).
