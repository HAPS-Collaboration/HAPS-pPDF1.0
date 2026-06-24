# HAPS-pPDF1.0

**HAPS-pPDF1.0** is a polarized parton distribution function set developed within the **HAPS Collaboration** (*Hadron and Partonic Structure Collaboration*).

<p align="left">
  <img src="https://img.shields.io/badge/HAPS--pPDF1.0-Polarized%20Proton%20PDF%20Set-0A66C2?style=for-the-badge" alt="HAPS-pPDF1.0">
</p>

# HAPS-pPDF1.0

**HAPS-pPDF1.0** is a polarized proton parton distribution function set developed within the **HAPS Collaboration**.

The grids accompany the analysis:

> **Toward Precision Helicity PDFs from Global DIS and SIDIS Fits with Projected EIC Measurements**
> Hamzeh Khanpour, Maryam Soleymaninia, Majid Azizi, Michael Klasen, Hadi Hashamipour, Maral Salajegheh, and Ulf-G. Meißner

## Paper

* **Title:** Toward Precision Helicity PDFs from Global DIS and SIDIS Fits with Projected EIC Measurements
* **Authors:** Hamzeh Khanpour, Maryam Soleymaninia, Majid Azizi, Michael Klasen, Hadi Hashamipour, Maral Salajegheh, and Ulf-G. Meißner
* **Collaboration:** HAPS Collaboration
* **Journal:** Physical Review D 113 (2026) 114010
* **arXiv:** https://arxiv.org/abs/2602.17298
* **INSPIRE:** https://inspirehep.net/literature/3121626
* **DOI:** https://doi.org/10.1103/wc54-mnfh
* **LHAPDF grids:** https://github.com/HAPS-Collaboration/HAPS-pPDF1.0

## Physics scope

HAPS-pPDF1.0 provides helicity-dependent parton distribution functions of the proton extracted from a global QCD analysis of longitudinally polarized inclusive deep-inelastic-scattering and charge-separated semi-inclusive deep-inelastic-scattering measurements.

The analysis is performed consistently at next-to-leading order in perturbative QCD using leading-twist collinear factorization and NLO DGLAP evolution. The polarized PDFs are parametrized using neural networks, while experimental uncertainties are propagated through a Monte Carlo replica methodology. Theoretical constraints, including positivity, are imposed during the fit.

In addition to the existing world polarized DIS and SIDIS measurements, the analysis investigates simulated SIDIS pseudodata for the future Electron-Ion Collider using two representative beam-energy configurations:

* $E_e \times E_p = 5 \times 41~\mathrm{GeV}^2$
* $E_e \times E_p = 18 \times 275~\mathrm{GeV}^2$

The EIC projections include longitudinal double-spin asymmetries for charge-separated pion and kaon production from a longitudinally polarized proton target. These measurements extend the kinematic coverage down to approximately $x \sim 10^{-5}$.

The projected EIC measurements substantially improve the flavor separation of the polarized sea, particularly for $\Delta\bar{u}$, $\Delta\bar{d}$, and the strange-helicity sector. They also reduce the uncertainties of both quark and gluon helicity distributions, with the strongest impact in the poorly constrained small-(x) region.

The resulting HAPS-pPDF1.0 Monte Carlo replica set is provided in standard LHAPDF format.

## Available LHAPDF grid

This repository contains the following polarized proton PDF set:

| Grid directory | PDF content           | Perturbative order | Members |
| -------------- | --------------------- | -----------------: | ------: |
| `HAPS-pPDF1.0` | Polarized proton PDFs |                NLO |     201 |

The member convention is:

* **Member 0:** average over the Monte Carlo replicas
* **Members 1–200:** individual Monte Carlo replicas

The grid covers:

* $10^{-5} \leq x \leq 1$
* $1~\mathrm{GeV} \leq Q \leq 1000~\mathrm{GeV}$

## Repository structure

```text
HAPS-pPDF1.0/
├── HAPS-pPDF1.0/
│   ├── HAPS-pPDF1.0.info
│   ├── HAPS-pPDF1.0_0000.dat
│   ├── HAPS-pPDF1.0_0001.dat
│   ├── ...
│   └── HAPS-pPDF1.0_0200.dat
└── README.md
```

The grid directory contains the LHAPDF `.info` file, the replica-average member, and the full Monte Carlo replica ensemble.

## Download

Clone the repository using:

```bash
git clone https://github.com/HAPS-Collaboration/HAPS-pPDF1.0.git
cd HAPS-pPDF1.0
```

## Citation

When using these grids, please cite:

```bibtex
%\cite{Khanpour:2026erj}
\bibitem{Khanpour:2026erj}
H.~Khanpour \textit{et al.} [HAPS],
%``Toward precision helicity PDFs from global DIS and SIDIS fits with projected EIC measurements,''
Phys. Rev. D \textbf{113}, no.11, 114010 (2026)
doi:10.1103/wc54-mnfh
[arXiv:2602.17298 [hep-ph]].
%2 citations counted in INSPIRE as of 24 Jun 2026
```

## Related HAPS fragmentation-function grids

The HAPS Collaboration also provides the following fragmentation-function sets:

* **HAPS-hFF1.0:** https://github.com/HAPS-Collaboration/HAPS-hFF1.0
* **HAPS-PiFF1.0:** https://github.com/HAPS-Collaboration/HAPS-PiFF1.0
* **HAPS-KaFF1.0:** https://github.com/HAPS-Collaboration/HAPS-KaFF1.0

## Related resources

* HAPS Collaboration: https://github.com/HAPS-Collaboration
* HAPS-pPDF1.0 repository: https://github.com/HAPS-Collaboration/HAPS-pPDF1.0
* arXiv: https://arxiv.org/abs/2602.17298
* INSPIRE: https://inspirehep.net/literature/3121626
* Journal article: https://doi.org/10.1103/wc54-mnfh
