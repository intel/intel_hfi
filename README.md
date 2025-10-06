# PROJECT NOT UNDER ACTIVE MANAGEMENT #  
This project will no longer be maintained by Intel.  
Intel will not provide or guarantee development of or support for this project, including but not limited to, maintenance, bug fixes, new releases or updates.  
Patches to this project are no longer accepted by Intel.  
 If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the community, please create your own fork of the project.  
  

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
