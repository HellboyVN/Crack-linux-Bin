# Crack-linux-Bin
## ltrace ./test.bin password => easy show the code with keyword
## gdb test.bin
## (gdb) disassemble main
## (gdb) b *0xbfffe9ff (add breakpoint)
## run test
## info register
##  x/s $eax
## or gdb) x/s *(0 + (void**)$esp) (gdb) x/s *(1 + (void**)$esp) (gdb) x/d *(2 + (void**)$esp) for variable
## (gdb) x/4wx $eax => to show hex address and then x/s to read values from adress
