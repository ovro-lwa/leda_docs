##Optimizing performance per watt on GPUs in High Performance Computing: temperature, frequency and voltage effects

####D. C. Price, M. A. Clark, B. R. Barsdell, R. Babich, L. J. Greenhill

(Submitted to Parallel Computing on 30 Jul 2014 (v1), last revised 14 Aug 2014 (this version, v2))

The magnitude of the real-time digital signal processing challenge attached to large radio astronomical antenna arrays motivates use of high performance computing (HPC) systems. The need for high power efficiency (performance per watt) at remote observatory sites parallels that in HPC broadly, where efficiency is an emerging critical metric. We investigate how the performance per watt of graphics processing units (GPUs) is affected by temperature, core clock frequency and voltage. Our results highlight how the underlying physical processes that govern transistor operation affect power efficiency. In particular, we show experimentally that GPU power consumption grows non-linearly with both temperature and supply voltage, as predicted by physical transistor models. We show lowering GPU supply voltage and increasing clock frequency while maintaining a low die temperature increases the power efficiency of an NVIDIA K20 GPU by up to 37-48% over default settings when running xGPU, a compute-bound code used in radio astronomy. We discuss how temperature-aware power models could be used to reduce power consumption for future HPC installations. Automatic temperature-aware and application-dependent voltage and frequency scaling (T-DVFS and A-DVFS) may provide a mechanism to achieve better power efficiency for a wider range of codes running on GPUs

**arXiv link:** http://arxiv.org/abs/1407.8116




