# Boot loader with ELF file parser application
 Customized Boot loader for STM 32(ARM Cortex).

### ELF file format parser application 
- Extracts the program data to be fed to the boot loader from .ELF file...

### Customized communication protocol over USART 
- A way of interaction between PC ELF parser application and STM32.

### Boot loader application
-  Responsible for flashing the data on the STM32 using a modified flash driver and executing it after a successful flashing.

### Notes
- There is a folder containing a full boot loader test using Eclipse IDE with STM32 connected to PC using ttl.
