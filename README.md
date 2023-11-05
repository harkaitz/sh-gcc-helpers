GCC HELPERS
===========

## Help

gcc-h-flycheck

    Usage: hflycheck SOURCE-FILES...
    
    This program helps managing your flycheckers and code parsers.
    
        -v  : Show configuration.
        -s  : Skip execution, simply show the command.
    
        -lP : List prefixes.
        -lI : List includes.
        -lD : List defines in
    
        -i  : Update ~/.hflycheck.sh
    
        -xE : Print semantic header search code.
        -eE : Print flycheck installation code.

gcc-h-query

    Usage: gcc-h-query -C (use g++) ...
    
    -V                  : Show configuration.
    -1 INCLUDE          : Include with <>.
    -2 INCLUDE          : Include with "".
    -d                  : List default defines.
    -m MACRO=RESULT ... : If MACRO defined print RESULT. 
    -c MACRO ...        : Return success if MACRO defined.
    -s TYPE ...         : Get the size of a type.

gcc-h-test-code

    Usage: gcc-h-test-code ...
    
    Print some useful C program for testing compilers.
    
    ... c-funcall : main() executes hello().

gcc-h-test-cross

    Usage: gcc-h-test-cross ...
    
    Test cross compilation with gcc.
    
      -b     : Build example program.
      -l     : Execute program locally.
      -r SSH : Execute program in remote machine.
    
    Environment variables: CC,CXX,CFLAGS,CXXFLAGS

gcc-h-wrap

    Usage: gcc-h-wrap ...
    
    ... show            : Show configuration.
    ... c/cxx   ARGS... : Execute compilers.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
