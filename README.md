BBEdit Language Module Collection
====

This repository contains various language modules and packages for BBEdit. Some are ones I created or
extended, plus there is a folder containing a large number of third-party modules.



My language modules
-------------------

- [Arm ASL](ArmASL.plist)
    - `.asl` extension
    - The Arm Architecture Specification Language is the pseudocode used in the Arm Architecture Reference Manuals.
    - See [Alastair Reid's blog](https://alastairreid.github.io) for more information about ASL.
- [Arm assembler](ARMAssemblerCLM.plist)
    - `.arm` extension
- [Bash shell script](BashShellScriptCLM.plist)
    - Superceded by BBEdit's built-in Unix Shell Script.
- [CMake](cmake.plist)
    - Modified version of the third-party module below.
- [cpptemplate](cpptemplate.plist)
    - For templates used by the [cpptemplate](https://github.com/flit/cpptemplate) C++ templating library.
- [elftosb `.bd` file](ElftosbBDFileCLM.plist)
    - For the config files used by the NXP elftosb tool that is part of their MCUBoot middleware.
- [eRPC IDL](eRPC_IDL_CLM.plist)
    - For the [eRPC](https://github.com/embeddedrpc/erpc) project's IDL files.
- [GNU linker script](GnuLinkerScriptCLM.plist)
- [Lark parser](LarkParserCLM.plist)
    - For the Lark parser package for Python.
- [Make](Make.plist)
    - Modified version of the third-party Make module below.
- [INI files](MyINIFileCLM.plist)
    - Another INI file module
- [Patchfile](PathfileCLM.plist)
    - For `.patch` and `.diff` files as produced by git.
- [Scala](Scala.plist)
    - Modified version of the two third-party Scala modules below.
- [Windows or DOS batch file](WindowsBatchFile.plist)
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

- Apache Configuration.plist
    - https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/a7cbd58b0e64c6b6cd5ec579306ef953b87b83ef/bbedit/Apache%20Configuration.plist
- AppleScript.plist
    - https://raw.githubusercontent.com/Angles/AppleScript-CLM-for-TW/master/AppleScript.plist
- AwkLanguage.plist
    - http://blog.csdn.net/jznsmail
- GitBlame.plist
    - https://raw.githubusercontent.com/ascarter/BBEdit-ApplicationSupport/master/Language%20Modules/GitBlame.plist
- Go.plist
    - Go authors.
- HAML.plist
    - https://raw.githubusercontent.com/mattmartini/BBEdit-Codeless-Language-Module-for-HAML-SASS/master/HAML.plist
- LESS.plist
    - https://raw.githubusercontent.com/mcguffin/bbedit-lesscss-language-module/master/LESS.plist
- Lasso.plist
    - https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/default/bbedit/Lasso.plist
- Make.plist
    - https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/a7cbd58b0e64c6b6cd5ec579306ef953b87b83ef/bbedit/Make.plist
- Mathematica.plist
    - http://www.skidmore.edu/~flip/
- PostScript.plist
    - Unknown source.
- PowerShell.plist
    - https://raw.githubusercontent.com/doug-baer/BBEdit-PowerShell/master/PowerShell.plist
- SASS.plist
    - https://raw.githubusercontent.com/mattmartini/BBEdit-Codeless-Language-Module-for-HAML-SASS/master/SASS.plist
- Scala.plist
    - https://raw.githubusercontent.com/dclements/scala_bbedit/master/Language%20Modules/Scala.plist
- Scala1.plist
    - https://raw.githubusercontent.com/zenmumbler/ScalaBBLM/master/Scala.plist
- TypeScript.plist
    - https://gist.githubusercontent.com/isao/5f6fbe89a438086c36d8/raw/91c66fa3e470ccfb8baa9e71a2779003bbdd778a/TypeScript.plist
- cmake.plist
    - http://tadpol.org/projects/bbclm_for_cmake.html
- coffescript.plist
    - https://gist.githubusercontent.com/sgss/1739174/raw/0dace6d2a5fc9507fbce15d9ae694bca1780e175/Info.plist
- csharp.plist
    - https://raw.githubusercontent.com/zarinfam/textwrangler-csharp-swift-syntax-highlighting/master/csharp.plist
- dockerfile.plist
    - https://raw.githubusercontent.com/whoughton/BBEdit-LMs/master/dockerfile.plist
- groovy.plist
    - https://raw.githubusercontent.com/rhydlewis/text-editing/master/bbedit/groovy.plist
- haskell-syntax.plist
    - Unknown source.
- java-properties.plist
    - https://raw.githubusercontent.com/signed8bit/bbedit-clm/master/java-properties/java-properties.plist
- reStructuredText.plist
    - https://bitbucket.org/EricFromCanada/ericfromcanada.bitbucket.org/raw/default/bbedit/reStructuredText.plist
- swift.plist
    - Unknown source.

For those modules listed as "Unknown source", I've simply lost track of where they came from.

Check each module for comments indicating the license. Unfortunately, many modules don't have a declared
license.
