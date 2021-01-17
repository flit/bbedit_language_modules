BBEdit Language Module Collection
====

This repository contains various language modules and packages for BBEdit. Some are ones I created or
extended, plus there is a folder containing a large number of third-party modules.



My language modules
-------------------

- [Arm ASL](modules/ArmASL.plist)
    - `.asl` extension
    - The Arm Architecture Specification Language is the pseudocode used in the Arm Architecture Reference Manuals.
    - See [Alastair Reid's blog](https://alastairreid.github.io) for more information about ASL.
- [GNU assembler](modules/GnuAssemblerCLM.plist)
    - `.s` extension
    - Includes keywords for all common directive, plus Arm and AArch64.
- [Bash shell script](modules/BashShellScriptCLM.plist)
    - Superceded by BBEdit's built-in Unix Shell Script.
- [CMake](modules/cmake.plist)
    - Modified version of the third-party module below.
- [cpptemplate](modules/cpptemplate.plist)
    - For templates used by the [cpptemplate](https://github.com/flit/cpptemplate) C++ templating library.
- [elftosb `.bd` file](modules/ElftosbBDFileCLM.plist)
    - For the config files used by the NXP elftosb tool that is part of their MCUBoot middleware.
- [eRPC IDL](modules/eRPC_IDL_CLM.plist)
    - For the [eRPC](https://github.com/embeddedrpc/erpc) project's IDL files.
- [GNU linker script](modules/GnuLinkerScriptCLM.plist)
- [Lark parser](modules/LarkParserCLM.plist)
    - For the Lark parser package for Python.
- [Make](modules/Make.plist)
    - Modified version of the third-party Make module below.
- [INI files](modules/MyINIFileCLM.plist)
    - Another INI file module
- [Patchfile](modules/PathfileCLM.plist)
    - For `.patch` and `.diff` files as produced by git.
- [Scala](modules/Scala.plist)
    - Modified version of the two third-party Scala modules below.
- [Windows or DOS batch file](modules/WindowsBatchFile.plist)
    - The ever-present `.bat` files on Windows and MS-DOS.

The language modules are released under a Creative Commons Attribution-ShareAlike License:
<http://creativecommons.org/licenses/by-sa/4.0/>


Third party language module sources
-----------------------------------

These are the lanaguage modules in the [third_party](third_party) directory. They were largely
sourced from the [bbeditextra.org
wiki](http://bbeditextras.org/wiki/index.php?title=Codeless_Language_Modules) and [BBEdit Language
Module Library](http://www.barebones.com/support/bbedit/plugin_library.html). Some were found just
by Google or GitHub searches.

- [Ada.plist](https://blady.pagesperso-orange.fr/Ressources/Ada.plist)
- [Apache Configuration.plist](https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/a7cbd58b0e64c6b6cd5ec579306ef953b87b83ef/bbedit/Apache%20Configuration.plist)
- [AppleScript.plist](https://raw.githubusercontent.com/Angles/AppleScript-CLM-for-TW/master/AppleScript.plist)
- [AvroAVDL.plist](https://github.com/rwilcox/apache_avro.bbpackage/tree/master/Contents/Language%20Modules)
- [AwkLanguage.plist](http://blog.csdn.net/jznsmail)
- [BBEditTextWranger-julia.plist](https://github.com/JuliaEditorSupport/julia-textwrangler-bbedit)
- [coffescript.plist](https://gist.github.com/sgss/1739174/)
- [csharp.plist](https://github.com/zarinfam/textwrangler-csharp-swift-syntax-highlighting/)
- [DCodelessLanguageModule.plist](https://github.com/jniehus/Dlang-for-BBEditTextWrangler)
- [Diff.plist](https://github.com/ascarter/BBEdit-ApplicationSupport/blob/master/Language%20Modules/Diff.plist)
- [dockerfile.plist](https://raw.githubusercontent.com/whoughton/BBEdit-LMs/master/dockerfile.plist)
- [Elixir.bbpackage](https://github.com/chipotle/elixir_bbedit)
- [ErlangBBLM-1.4](https://github.com/pguyot/erlang-bblm)
- [GAS Assembly.plist](https://github.com/FrankBot1000/GAS-Assembly-Language-Module)
- [GitBlame.plist](https://raw.githubusercontent.com/ascarter/BBEdit-ApplicationSupport/master/Language%20Modules/GitBlame.plist)
- [Go.bbpackage](https://github.com/ascarter/Go-bbpackage)
- [groovy.plist](https://raw.githubusercontent.com/rhydlewis/text-editing/master/bbedit/groovy.plist)
- [HAML.plist](https://raw.githubusercontent.com/mattmartini/BBEdit-Codeless-Language-Module-for-HAML-SASS/master/HAML.plist)
- [haskell-syntax.plist](https://code.google.com/archive/p/bbedit-haskell/)
- [java-properties.plist](https://raw.githubusercontent.com/signed8bit/bbedit-clm/master/java-properties/java-properties.plist)
- [LESS.plist](https://raw.githubusercontent.com/mcguffin/bbedit-lesscss-language-module/master/LESS.plist)
- [Make.plist](https://github.com/EricFromCanada/byte-bucket/blob/master/bbedit/Make.plist)
- [Mathematica.plist](http://www.skidmore.edu/~flip/)
- [Nim.plist](https://gist.github.com/ytomino/4c9d186d78a27ad202ac)
- [OCaml.plist](https://gist.github.com/GPHemsley/1848824)
- [Perl6.plist](https://github.com/briandfoy/Perl6_BBEdit_CLM)
- [PostScript.plist](http://ancientgroove.co.uk/freebies/PostScript.plist)
- [PowerShell.plist](https://github.com/doug-baer/BBEdit-PowerShell/)
- [R.plist](https://stat.ethz.ch/pipermail/r-sig-mac/2017-January/012189.html)
- [reStructuredText.plist](https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/default/bbedit/reStructuredText.plist)
- [SASS.plist](https://github.com/mattmartini/BBEdit-Codeless-Language-Module-for-HAML-SASS/)
- [Scala.plist](https://github.com/dclements/scala_bbedit)
- [Scala1.plist](https://raw.githubusercontent.com/zenmumbler/ScalaBBLM/master/Scala.plist)
- [StandardML.plist](https://www.cl.cam.ac.uk/teaching/0910/FoundsCS/StandardML.plist)
- [TypeScript.plist](https://gist.githubusercontent.com/isao/5f6fbe89a438086c36d8/raw/91c66fa3e470ccfb8baa9e71a2779003bbdd778a/TypeScript.plist)
- [VisualBasic.plist](https://github.com/bluecat76/TW_Lang_VisualBasic)

Check each module for comments indicating the license. Unfortunately, many modules don't have a declared
license.

### Other language module lists

The canonical list of third party modules is Bare Bones' [BBEdit Language Module
Library](http://www.barebones.com/support/bbedit/plugin_library.html) page.

The [bbeditextras.org](https://bbeditextras.org/) site also has [large list of BBEdit language
modules](https://bbeditextras.org/wiki/index.php?title=Codeless_Language_Modules).


### Outdated modules

The modules under `third_party/outdated` have either been superceded by modules built-in to BBEdit,
or no longer work with recent BBEdit versions and have no updated release.

- [cmake.plist](http://tadpol.org/projects/bbclm_for_cmake.html)
- [Lasso.plist](https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/default/bbedit/Lasso.plist)
- [swift.plist](https://github.com/EricFromCanada/bbedit-swift-clm/blob/master/swift.plist)


