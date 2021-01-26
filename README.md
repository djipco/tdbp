# TouchDesigner Best Practices
This is my own, very personal, list of best practices to apply when developing TouchDesigner projects. Hopefully, this can be useful to others beginning with TouchDesigner. 

* If you have a suggestion to improve this list, simply submit a pull request.

* If you disagree about something, [create an issue](https://github.com/djipco/tdbp/issues/new) so we can discuss it further.

This list of best practices is only beginning... I would love to hear about all the ways other practionners operate. It would be awesome if this became a coimmunity effort.

## NOMENCLATURE

### Naming Operators

* [Snake-case](https://en.wikipedia.org/wiki/Snake_case) should be used to name operators.
* I suggest the use of a 3-letter operator prefix, followed by one or more keywords (e.g. `mth_add_freq`.
* To keep name lengths short, the use of sensible abbreviations is welcome.

### Naming Channels

* [Snake-case](https://en.wikipedia.org/wiki/Snake_case) should be used to name channels.
* Channels should explicitly be named after what they represent. 
* When the data in a channel changes meaning, the channel should be renamed accordingly.


## STRUCTURE & LAYOUT

