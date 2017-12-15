# Aaron's Simple C Makefile

Simple Makefile for use with small C projects. To use this Makefile, make a
Makefile for your project that looks like this:

    SRCDIRS := <source directories>
    INCDIRS := <include paths>
    CFLAGS  := <desired compiler flags>
    LDLIBS  := <desired linker flags>
    
    include Makefile.generic

Please read `Makefile.generic` for more detailed information.
