iverilog *.v

vvp a.out

iverilog -o test_counter.vvp -s test_counter *.v
