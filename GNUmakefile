# =========================================================================
#     This makefile was generated by
#     Bakefile 0.2.11 (http://www.bakefile.org)
#     Do not modify, all changes will be overwritten!
# =========================================================================



# -------------------------------------------------------------------------
# These are configurable options:
# -------------------------------------------------------------------------

# C compiler 
CC = gcc

# Standard flags for CC 
CFLAGS ?= 

# Standard preprocessor flags (common for CC and CXX) 
CPPFLAGS ?= 

# Standard linker flags 
LDFLAGS ?= 



# -------------------------------------------------------------------------
# Do not modify the rest of this file!
# -------------------------------------------------------------------------

### Variables: ###

CPPDEPS = -MT$@ -MF`echo $@ | sed -e 's,\.o$$,.d,'` -MD -MP
GTK_HELLO_WORLD_CFLAGS = `pkg-config --cflags gtk+-3.0` $(CPPFLAGS) $(CFLAGS)
GTK_HELLO_WORLD_OBJECTS =  \
	gtk_hello_world_main.o

### Conditionally set variables: ###



### Targets: ###

all: gtk_hello_world

install: 

uninstall: 

clean: 
	rm -f ./*.o
	rm -f ./*.d
	rm -f gtk_hello_world

gtk_hello_world: $(GTK_HELLO_WORLD_OBJECTS)
	$(CC) -o $@ $(GTK_HELLO_WORLD_OBJECTS)  `pkg-config --libs gtk+-3.0` $(LDFLAGS)

gtk_hello_world_main.o: ./main.c
	$(CC) -c -o $@ $(GTK_HELLO_WORLD_CFLAGS) $(CPPDEPS) $<

.PHONY: all install uninstall clean


# Dependencies tracking:
-include ./*.d
