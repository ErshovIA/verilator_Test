# verilator_Test
from verilator.org

Simple example from VERILATOR official website.

1. export VERILATOR_ROOT=DIR WITH VERILATOR
2. export PATH=$VERILATOR_ROOT/bin:$PATH

BELOW for 'test_our' workig dir

3. verilator --cc --exe --build -j 0 -Wall sim_main.cpp our.v
4. ./obj_dir/Vour

