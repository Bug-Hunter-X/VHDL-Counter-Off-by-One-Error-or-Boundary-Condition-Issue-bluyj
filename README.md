# VHDL Counter Bug
This repository demonstrates a common off-by-one error or boundary condition problem in VHDL counters.  The `buggy_counter.vhdl` file contains a counter that might exhibit unexpected behavior when reaching its maximum value. The corrected version is in `fixed_counter.vhdl`.

## Bug Description
The `buggy_counter` entity uses a simple process to increment a counter. However, the condition for resetting the counter to zero might be incorrectly handled leading to incorrect values or simulation failures. 

## Solution
The `fixed_counter.vhdl` addresses this by ensuring the reset condition is handled accurately.  The solution may involve clarifying the reset condition to ensure proper counter behavior.

## How to reproduce
1.  Simulate buggy_counter.vhdl and observe the counter behavior when it reaches its maximum count (15).
2. Compare with fixed_counter.vhdl to observe correct behavior.

## License
MIT License