# AXI4_infra
# AXI4 compliant modules
This repository contains the AXI4 compliant modules' suite. 
At this point it contains following modules:
  1) AXI4 memory mapped Read/Write Master
  2) AXI4 memory mapped Read/Write Slave
  3) AXI4 interconnect(not yet completed)
The modules are ARM AMBA 4 compliant. 

Each module also supports a native interface in addition to AXI4 and another AXI4 lite interface for register configuration.
Configurable parameters include
 1) Data Width - default 32
 2) Address Width - default 32
 3) Burst Length - default 256
 4) Burst type - as of now supports only incremental
 
