## Basics
In Node requiring a file is requiring the module it defines. All modules have a reference to an implicit module object whose property module.exports is what is returned when you call require. A reference to module.exports is also available as exports.

Imagine a line at the beginning of each module:

`var exports = module.exports = {};`
