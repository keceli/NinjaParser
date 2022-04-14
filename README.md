# ninja_log
Parse `.ninja_log` files and print statistics.

If you have been complaining about long build times you may have switched to `ninja` from `make`. If not you should give it a try. 
Along with being faster, `ninja` also provides a log file, `.ninja_log` containing timings for each built object. 
This information can be helpful to understand the bottlenecks in your building process. However, this file needs to be parsed to be comprehensible.
`ninja_log` is a Python script that provides a sorted list of built times with percentages.
