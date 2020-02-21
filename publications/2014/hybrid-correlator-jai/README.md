##A Scalable Hybrid FPGA/GPU FX Correlator

####J. Kocz, L.J. Greenhill, B.R. Barsdell, G. Bernardi, A. Jameson, M.A. Clark, J. Craig, D. Price, G.B. Taylor, F. Schinzel, D. Werthimer

*(Submitted on 31 Jan 2014 (v1), last revised 18 Feb 2014 (this version, v2))*

Radio astronomical imaging arrays comprising large numbers of antennas, O(10^2-10^3) have posed a signal processing challenge because of the required O(N^2) cross correlation of signals from each antenna and requisite signal routing. This motivated the implementation of a Packetized Correlator architecture that applies Field Programmable Gate Arrays (FPGAs) to the O(N) "F-stage" transforming time domain to frequency domain data, and Graphics Processing Units (GPUs) to the O(N^2) "X-stage" performing an outer product among spectra for each antenna. The design is readily scalable to at least O(10^3) antennas. Fringes, visibility amplitudes and sky image results obtained during field testing are presented.

**Arxiv link:** http://arxiv.org/abs/1401.8288

**JAI Link:** http://www.worldscientific.com/doi/abs/10.1142/S2251171714500020?src=recsys

