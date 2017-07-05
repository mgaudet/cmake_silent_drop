# Silent dropping of source files

Note that in CMakeLists.txt, there is a reference to A.asm, but CMake simply 
ignores this and moves on. 

**Update**: [Discussion on StackOverflow][1] indicates that this is working as designed, but there's a potential work around. 

[1]: https://stackoverflow.com/q/44930408/1074413
