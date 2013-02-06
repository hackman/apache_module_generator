apache_module_generator
=======================

As I'm frequently creating Apache modules for fun or profit it happens that I need fast and easy way to create all the needed infrastructure before actually starting to write the module.

This is when the idea for Apache Module Generator hit me :)

Apache Module Generator should be a simple Perl tool to generate templates for building Apache modules.

My road plan is simple

1. Generate a Makefile for building the module
2. Create string templates for the base functions that comprise an Apache module.
3. Create a simple cmdline tool to ask you some simple questions and generate the new module.
4. Create web interface for the same thing.
5. Add option to build the templates compatible with Apache 1.3, 2.2, or 2.4 (with the added initial portability checks)


