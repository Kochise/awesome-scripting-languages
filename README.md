# awesome-scripting-languages
List of awesome scripting languages of relevant interest, innovative and disruptive, mostly targeted for embedded usage.

Not included are common scripting languages (Lua, Python, ...) or esoteric languages (Befunge, Piet, ...).

WIP : this list will evolve with time as it is mostly a scratchpad for me.

Main focuses are :
* language expressivity (conceptualization power)
* ease of programming (not too complex)
* cross develoment (ranging from desktop to iot)
* lightweightness (<1MB, thus embeddable)

The languages might be unpopular, in a working state or still in WIP, the purpose here is to list scripting languages that have innovative ideas and concepts that might help getting things done fair and square without the need of a huge IDE+SDK. Ideally it should be self "compilable", but this one might be a bit far-fetched for a scripting language.

# Scripting languages

Here is the list of features that might or might not present in the scripting language listed below:

*Fam*: Family of language, mimick an already existing programming language
*Src*: Source language, in which is the scripting language programmed
*Use*: Overall usability, is the language an exploration or ready for production
*Syn*: Syntax simplicity, scarcity of the scripting syntax to get the job done
*Typ*: Type system, dynamic or static
*Bin*: Binary operators, like or xor and nand shift
*Int*: Integer operators, like add sub mul div, constants like enum
*Flt*: Float operators, like add sub mul div, constants like pi, units like deg grad rad
*Str*: String functions, like ascii ansi unicode ucs utf widechar codepoint codepage
*Dat*: Data structures, like array list tuple struct hash map tree edge
*Mem*: Memory allocator, like dl jl gc
*Ffi*: Foreign function interface, can interface to other programming language
*Dll*: Dynamic loadable library, can load other modules dynamically (self or bin)
*Dbi*: Database interface, can interface with database, or have one integrated
*Snd*: Sound interface, like synth sfx openal
*Gfx*: Graphic interface, like sdl gl vulkan
*Net*: Network interface, like tcp udp ftp
*Plus*: Additional features, like make caffee webcam robot
*Size*: Typical compiled size in kB (stripped tcc-win32 release)
*Perf*: Typical performance in % (compared to tcc-win32 equivalent)

Numbers given in cells are subjective quality (0-poor to 5-great).
Missing number means the given feature is not present.

| Name    | Fam | Src | Use | Syn | Typ | Bin | Int | Flt | Str | Dat | Mem | Ffi | Dll | Dbi | Snd | Gfx | Net | Plus | Size | Perf |
| :--     | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-:  | :-:  | :-:  |
| [berry] | C-  | C   |
| [eel]   | C-  | C   | | 3
| [gml]   | C-  | C   | | 3
| [rubi]  | Ruby | C  | | 5

[berry]: https://github.com/Skiars/berry
[eel]: https://github.com/olofson/eel/blob/master/test/heapsort.eel
[gml]: https://github.com/graphitemaster/gml
[rubi]: https://github.com/sysprog21/rubi

# Languages of interest

You can also be interested into these similar related language lists as well :
* [dbohdan/embedded-scripting-languages](https://github.com/dbohdan/embedded-scripting-languages)
* [r-lyeh-archived/scriptorium](https://github.com/r-lyeh-archived/scriptorium)
* [List of programming languages by type](https://en.wikipedia.org/wiki/List_of_programming_languages_by_type)
