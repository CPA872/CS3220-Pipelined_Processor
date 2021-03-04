## Next up
- Implement stall

## Update 03/04
- Created and assigned necessary signals for stall to work.

## update 03/03 
- fixed branch. Now DE passes a signal to FE indicating a branch, and FE will stall if DE meets a branch instruction (PC doesn't change)
- Passed test 1 and 2
- branch works

## update 03/02
- Completed the ALU switch statement
- Finished register writeback in DE stage by routing signals from WB to DE stage where `regs` are. Check `from_WB_to_DE` in DE stage.
- LW now works
- SW should work, but haven't tested
- LW can read values from memory and write to `rd_val_MEM`

## update 03/01
- Code organization
- Completed Pipeline partially
