# VHDL Counter with Type Mismatch Bug

This repository demonstrates a common, subtle bug in VHDL code involving type mismatches.  The provided `counter_bug.vhdl` file contains a counter that, while seemingly functional in simple simulations, contains a potential source of problems when integrated into a larger design.

The bug is related to type conversions between integers and std_logic_vector types. If you attempted to convert `count` to std_logic_vector for use in other parts of the system, you will encounter an error.

The `counter_solution.vhdl` file provides a corrected version of the code.