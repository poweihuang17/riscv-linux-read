# Physical memory map initialization

## Related section in running man::
- section 2.1

## Questions in the book adapted to risc-v
- When system is booted, how does RISC-V linux kernel know the size of physical map of platform?

- In 32bit Linux, user space: kernel space is often set to 3:1, but could we modify it to 2:2? Could we do it in riscv-linux? How?

- How does physical map added to buddy system? Is it 1 by 1, or is it add by 2^n?

## Todo:
- Read through the section in book.
- Read the code of ARM
- Read the code of RISC-V
- Answer the Questions for RISC-V

## Log:

- 01-11-2018 First visit.
