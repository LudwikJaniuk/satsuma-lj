This project is a fork of [Satsuma](http://satsumagraph.sourceforge.net/doc/html/), a C# graph library I found on sourceforge. I created this fork because:

 * Satsuma is easy to use and setup so I want it to be available
 * I found some bugs in satsuma, but there was no way to contribute fixes
 * I want future users to benefit from my bug fixes.

Currently the only bug I've fixed is in src/src/Utils.cs, where the method RemoveAll wouldn't actually remove all elements that satisfied the predicate. This method is used all over the place, so...

Also, I'm only ever using src directly, so I say nothing about the state of the stuff in the other folders.
