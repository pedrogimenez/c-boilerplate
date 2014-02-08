This repository contains the code I need to start writing some C software.

I use TDD, so I need a test framework, I like [clar](http://github.com/vmg/clar).

##### Run your own test suite:

```bash
$ cd tests
$ $CLAR_PATH/generate.py . 
$ gcc -I. framework/clar.c framework/main.c boilerplate.c -o test
$ ./test
```

Just change the *boilerplate.c* part.
