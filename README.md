#egypt - a tool for making call graphs

Egypt is a simple tool for creating call graphs of C programs. Egypt neither analyzes source code nor lays out graphs. Instead, it leaves the source code analysis to GCC and the graph layout to Graphviz, both of which are better at their respective jobs than egypt itself could ever hope to be. Egypt is simply a very small Perl script that glues these existing tools together.

The most recent release of egypt is version 1.10, which can be downloaded here. Online documentation is here. You will also need gcc, Perl, and Graphviz.

To install, extract the compressed tar file, cd to the egypt directory, and type

    perl Makefile.PL
    make
    make install
Then type

    man egypt
or
    perldoc egypt
for additional information.

#http://www.gson.org/egypt/
