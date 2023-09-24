GCC HELPERS
===========

## Help

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
    
    ... show                  : Show configuration.
    ... install [ssh MACHINE] : Install "c" and "cxx" wrappers.
    ... c/cxx   ARGS...       : Execute compilers.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
