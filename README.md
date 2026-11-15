# Adaptive ReSTIR Thesis Report
<img src="Teaser.png" alt="Comparison image showing performance difference between ReSTIR PT and Adaptive ReSTIR PT">

Repository to host my Adaptive ReSTIR thesis report as git LFS cannot be used on forks of other repositories.

The thesis focuses on exploring how ReSTIR behaves when sampling at lower than 1 s.p.p. rates at fixed rates and using smarter adaptive sampling heuristics. Factors to keep in mind when designing adaptive sampling heuristics for ReSTIR are also discussed.

The results show sampling rates can naively be reduced to 0.75 and 0.5 s.p.p. with minimal visual quality loss. Using the adaptive sampling schemes it is possible to reduce the sampling rate down to 0.15 depending on scene content while maintaining image quality. The implementation is built upon Lin et al.'s ReSTIR PT [implementation](https://github.com/DQLin/ReSTIR_PT).

Implementation of the thesis can be found [here](https://github.com/XiaoyiHu1998/Adaptive_ReSTIR).
