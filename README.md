
# Reference implementation to use the Intel Hardware Feedback Interface

This repository contains a reference implementation to use the Intel
Feedback Interface (HFI). It shows how to enable it, handle the
thermal interrupt it generates, and read the HFI table that hardware
provides. Full details on the operation of HFI can be found in the
Intel Software Developer's Manual [1].

This reference code is based on the implementation in the Linux
kernel[2]. This code does not compile on its own.


[1]. https://www.intel.com/sdm
[2]. https://www.kernel.org
