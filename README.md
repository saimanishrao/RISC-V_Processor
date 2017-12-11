# RISC-V Processor Design

## Project_Code/

These codes are provided in our Project_Code folder, contains the BSV code for all the modules used in the RISC-V processor design for both One cycle and Two stage . These files are briefly explained below,

**DMemory.bsv** Implementation of the data memory using Bram. 

**Decode.bsv** Implementation of the instruction decoding. 

**Ehr.bsv** Implementation of EHRs.

**Exec.bsv** Implementation of the instruction execution. 

**Fetch.bsv** Implementation of instruction fetching from Bram.

**Fifo.bsv** Implementation of a variety of FIFOs using EHRs . 

**Interfaces.bsv** Contains interface types used in different modules. 

**ProcTypes.bsv** Common types relating to the processor. 

**RFile.bsv** Implementation of the register file. 

**Types.bsv** Common types. 

**OneCycle.bsv**  Implementation of one-cycle processor.

**TwoStage.bsv** Implementation of two stage pipeline processor.


## Constrain_Files_Vivado/

This constarin file is added to project files in vivado and it hepls us to perform timing analysis and to generate bitstream in order to program the FPGA.

**zedboard_master_XDC_RevC_D_v3.xdc** Constrain file used in Vivado.
