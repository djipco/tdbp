# TouchDesigner Best Practices

This is my own, **very personal**, list of best practices to apply when developing TouchDesigner projects. Hopefully, this can help people share projects with minimal friction. 

* If you have a suggestion to improve this list, simply submit a pull request.

* If you disagree about something, [create an issue](https://github.com/djipco/tdbp/issues/new) so we can discuss it further.

This list is a work in progress. I would love to hear about all the ways other practionners operate.

## NOMENCLATURE

### Naming Operators

* [Snake-case](https://en.wikipedia.org/wiki/Snake_case) should be used to name operators.
* To keep names short, the use of sensible abbreviations is welcome. I tend to favour the stripping of all vowels except the first one (e.g. `normalize` becomes `normlz`, `average` becomes `avrg`).
* The name should start with a 3-letter operator prefix (same as those shown when the viewer is disabled) (e.g. `mth_xxx` or `noi_xxx`).
* For generators, the prefix should be followed by a noun (e.g. `dmi_lighting` or `afi_music`)
* For filters, the prefix should be followed by a verb (`mth_multiply_color` or `ana_avrg_audio`)


### Naming Channels

* [Snake-case](https://en.wikipedia.org/wiki/Snake_case) should be used to name channels.
* Channels should explicitly be named after what they represent. 
* When the data in a channel changes meaning, the channel should be renamed accordingly.


## STRUCTURE & LAYOUT

