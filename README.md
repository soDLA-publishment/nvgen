# nvgen(Exploring)

NVDLA generator is a subproject of soDLA.

Different from soDLA, this repo is to explore the design agility between hardware performance within the NVDLA itself. For example, in a long signal chain of ValidIO, if what is the difference of a specialized retiming module and a parallel of ShiftRegisters? Using a specialized retiming module may impose more hardware performance, but less design agility.

# What's new

12/2/2019
1. Support retiming.
2. Remove ready signal.
