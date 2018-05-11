ghdl -s <file>: checks for syntax errors
ghdl -a <file>: compiles each file
ghdl -e <top entity>: compiles the entity (all files need to be compiled first)
ghdl -r <top entity> --vcd=<output file>.vcd: runs the simulation and dumps the result to a file to be rendered by gtkwave
gtkwave <output file>.vcd: opens the wave file
