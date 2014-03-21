Maven based Netbeans Platform Application with Groovy code
==============
(yeah, that's a mouthful)

Fully working Netbeans Platform Application with a module that utilizes compiled groovy code.
Groovy code is called from TopComponent.
The TopComponent can't use the @Messages annotation, however this is the only caveat found so far.

maven-compiler-plugin version is changed to 3.0 from the default of 2.5.1
Groovy version is 2.1.8, thus groovy-eclipse-batch is of version 2.1.8-01 (they must match)

groovy-all is included in a "library wrapper module"
