# ECE6780 Pre-Lab 1

## Questions

### What is a commit in the context of git?

A commit takes a snapshot of an updated github repository, giving it a hash map for segments of the repository and is able to use that map to retrieve older versions of the repository.

### How much memory and FLASH storage does the STM32F072R8 have?

Using the RM0091 Reference Manual, we can find information on the microcontroller for a variety of different types.

> STM32F07xS devices feature 16 Kbytes of static SRAM *(RM0091 Rev 10, Page 52)*.

The STM32F072R8 has 16 kilobytes of static SRAM. Using the same manual we can find the flash memory storage capacity

> The memory organization of STM32F07x and STM32F09x devices is based on a main flash
memory block containing up to 128 pages of 2 Kbytes or up to 64 sectors of 4 Kbytes. *(RM0091 Rev 10, Page 56)*.

The manual officially says microcontrollers with the -7x prefix has up to 256 kilobytes, however, when looking at the official datasheet for the STM32F072x8, it shows that this microcontroller has 128 kilobytes of FLASH storage.

> 64 to 128 Kbytes of Flash memory (DS9826 Rev 6, Page 1)

The STM32F072R8 has 128 kilobytes of FLASH memory.

### What does the acronym "HAL" stand for?

### What is the STM32CubeMX program used for?

### Why can't a "bare-metal" embedded application return from the main function?

### In the system's memory table, are the peripheral registers higher or lower in address than the SRAM?

### What information does each of the four main datasheets/manuals used in the labs provide?

### Why do STM32F0 devices not recognize inputs/outputs on a chip by physical pin numbering?

### What is the name of ST's header file that defines names for the peripheral registers?

### What bitwise operator would you use to set a bit in a register?

You would use the bitwise "OR" operator to set a given bit in a register to 1.  

### What peripheral enables the system clock to other peripherals?

### What peripheral do the HAL library delay functions use?

### Why should you avoid floating-point values on an STM32F0?