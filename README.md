# TouchDesigner Best Practices

This is my own, **very personal**, list of best practices to apply when developing TouchDesigner projects. Hopefully, this can help people share projects with minimal friction. 

* If you have a suggestion to improve this list, simply submit a pull request.

* If you disagree about something, [create an issue](https://github.com/djipco/tdbp/issues/new) so we can discuss it further.

This is a work in progress. I would love to hear about all the ways other practionners operate.

## NOMENCLATURE

* As a general rule, [Snake-case](https://en.wikipedia.org/wiki/Snake_case) should be used to name stuff (channels, operators, variables, etc.).

* To keep names short, the use of sensible abbreviations is encouraged. I tend to favour the stripping of all vowels except the first one (e.g. `normalize` becomes `normlz`, `average` becomes `avrg`).

### Naming Operators

* The name should start with a 3-letter operator prefix (same as those shown when the viewer is disabled) (e.g. `mth_xxx` or `noi_xxx`).

* For generators, the prefix should generaly be followed by a noun (e.g. `dmi_lighting` or `afi_music`). An extra noun or adjective (optionnally numbered) can be added for clarification (e.g. `afi_musc_scen1` or `dmi_unvrs1`).

* For filters, the prefix should generaly be followed by a verb (`mth_multpl` or `ana_avrg`). An extra noun or adjective (optionnally numbered) can be added for clarification (e.g. `mth_multpl_color` or `ana_avrg_levl`).


### Naming Channels

* Channels should explicitly be named after what they represent (avoid `chan1` as much as possible).

* When the data in a channel changes meaning, the channel should be renamed accordingly.

## COLOURING

* I colour my operators red when they are being referenced elsewhere. This reminds me to be careful when renaming.


## STRUCTURE & LAYOUT

* Try to limit the number of operators in a component and favour modules.
