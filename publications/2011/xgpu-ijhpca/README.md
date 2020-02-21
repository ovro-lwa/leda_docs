##Accelerating Radio Astronomy Cross-Correlation with Graphics Processing Units

####M. A. Clark, P. C. La Plante, L. J. Greenhill

*(Submitted on 21 Jul 2011 (v1), last revised 1 Aug 2011 (this version, v2))*

We present a highly parallel implementation of the cross-correlation of time-series data using graphics processing units (GPUs), which is scalable to hundreds of independent inputs and suitable for the processing of signals from "Large-N" arrays of many radio antennas. The computational part of the algorithm, the X-engine, is implementated efficiently on Nvidia's Fermi architecture, sustaining up to 79% of the peak single precision floating-point throughput. We compare performance obtained for hardware- and software-managed caches, observing significantly better performance for the latter. The high performance reported involves use of a multi-level data tiling strategy in memory and use of a pipelined algorithm with simultaneous computation and transfer of data from host to device memory. The speed of code development, flexibility, and low cost of the GPU implementations compared to ASIC and FPGA implementations have the potential to greatly shorten the cycle of correlator development and deployment, for cases where some power consumption penalty can be tolerated.

**arXiv link:** http://arxiv.org/abs/1107.4264