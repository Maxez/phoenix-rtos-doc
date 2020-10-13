# Table of Contents

1. [Introduction](introduction.md)
2. [Building](building/README.md)
   1. [Building toolchain](building/toolchain.md)
   2. [Building project](building/project.md)
3. [Running system on targets](quickstart/README.md)
   1. [Running system on `armv7m4-stm32l4x6` (ST STM32L4x)](quickstart/armv7m4-stm32l4x6.md)
   2. [Running system on `armv7m7-imxrt105x` (NXP i.MX RT105x)](quickstart/armv7m7-imxrt105x.md)
   3. [Running system on `armv7m7-imxrt106x` (NXP i.MX RT106x)](quickstart/armv7m7-imxrt106x.md)
   4. [Running system on `armv7m7-imxrt117x` (NXP i.MX RT117x)](quickstart/armv7m7-imxrt117x.md)
   5. [Running system on `armv7a7-imx6ull` (NXP i.MX 6ULL)](quickstart/armv7a7-imx6ull.md)
   6. [Running system on `ia32-generic`](quickstart/ia32-generic.md)
   7. [Running system on `riscv64-virt`](quickstart/riscv64-virt.md)
   8. [Running system on `riscv64-spike`](quickstart/riscv64-spike.md)
4. [Architecture](architecture.md)
5. [Kernel](kernel/README.md)
   1. [HAL](kernel/hal/README.md)
      1. [HAL layer for ARMv7 Cortex-M based based targets](kernel/hal/armv7m.md)
      2. [HAL layer for ARMv7 Cortex-A based based targets](kernel/hal/armv7a.md)
      3. [HAL layer for IA32 based targets](kernel/hal/ia32.md)
      4. [HAL layer for RISC-V 64 based targets](kernel/hal/riscv64.md)
   1. [Memory management](kernel/mm/README.md)
      1. [Page allocator](kernel/mm/page.md)
      2. [Memory mapper](kernel/mm/mapper.md)
      3. [Zone allocator](kernel/mm/zalloc.md)
      4. [Fine-grained kernel allocator](kernel/mm/kmalloc.md)
      5. [Memory objects](kernel/mm/objects.md)
   3. [Processes and threads](kernel/proc/README.md)
6. Standard library
7. Device drivers
8. Filesystem servers
9. Network stack
10. USB stack
11. Utilities
    1. Core utilities
12. Host utilities
13. Loader
14. POSIX server
15. Ports
16. Tests and testing process
17. Coding convention


