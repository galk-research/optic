# optic

OPTIC homepage: https://sourceforge.net/projects/tsgp/files/OPTIC/

Code revised to adhere with C++17/C++20. 

Steps to build and install (defaults to "/usr/local")

```bash
$ cmake -DCMAKE_BUILD_TYPE=Release -S src -B release
$ cd release
$ make -j 10 parser
$ make -j 10 optic-clp
$ sudo make install
```

Alternative builds possible by changing arguments of call to `cmake` above by suitable keywords.
