##Enabling a High Throughput Real Time Data Pipeline for a Large Radio Telescope Array with GPUs

####R. G. Edgar, M. A. Clark, K. Dale, D. A. Mitchell, S. M. Ord, R. B. Wayth, H. Pfister, L. J. Greenhill

*(Submitted on 29 Mar 2010 (v1), last revised 14 Jun 2010 (this version, v3))*

The Murchison Widefield Array (MWA) is a next-generation radio telescope currently under construction in the remote Western Australia Outback. Raw data will be generated continuously at 5GiB/s, grouped into 8s cadences. This high throughput motivates the development of on-site, real time processing and reduction in preference to archiving, transport and off-line processing. Each batch of 8s data must be completely reduced before the next batch arrives. Maintaining real time operation will require a sustained performance of around 2.5TFLOP/s (including convolutions, FFTs, interpolations and matrix multiplications). We describe a scalable heterogeneous computing pipeline implementation, exploiting both the high computing density and FLOP-per-Watt ratio of modern GPUs. The architecture is highly parallel within and across nodes, with all major processing elements performed by GPUs. Necessary scatter-gather operations along the pipeline are loosely synchronized between the nodes hosting the GPUs. The MWA will be a frontier scientific instrument and a pathfinder for planned peta- and exascale facilities.

**arXiv link:** http://arxiv.org/abs/1003.5575

**CPC link:** http://www.sciencedirect.com/science/article/pii/S0010465510001967


