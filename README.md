# diskops

Parsimoniously, recursive delete, copy and others are not in core Clojure at the time of writing.  Furthermore it is kind of difficult to track down _the_ library to use without importing a load of baggage, so here, unceremoniously, without any dependencies Java based or otherwise, and forever to be minimal and simple are some functions we all need.

## Release information

* Latest stable release is 0.3.0


## Documentation

* delete-directory (including nested directories)
    * (delete-directory "a-poor-unwanted-directory")
* copy-recursive (its in the name)
    * (copy-recursive "src-directory" "target-directory"))
* and others

Enjoy!
