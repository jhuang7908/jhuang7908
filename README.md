# Jing Huang

**Co-founder of InSynBio.** Immunology and translational research: vaccine studies, humanized immune-system models, and computational antibody workflows.

Core code and databases stay in private repositories. This page states what those repositories currently contain, and links only to pages that were reachable without a login on 2 October 2026.

[InSynBio](https://insynbio.com/) · [US Life Hub](https://www.uslifehub.org/) · [LinkedIn](https://www.linkedin.com/in/jhuang77) · [Genomab](https://www.genomab.com/)

## Counted scope

These rows are separate tables. They are not a deduplicated union, and they are not the “1,142 sequences” or “138 ADA records” figures on the public website. A local file named for 1,142 antibodies contains 70 records.

| Measure | Count | Date | Basis |
|---|---:|---|---|
| Engineered therapeutic antibodies with VH and VL | 458 | 2026-10-02 | Private atlas table; every row has both chains, each at least 80 amino acids |
| Fully human therapeutic antibodies with VH and VL | 384 | 2026-10-02 | Separate private atlas table; same length rule |
| Clinical parent-to-humanized pairs with VH and VL on both the parent and the clinical sequence | 52 | 2026-10-01 | Audit `CLINICAL-52`; all 52 passed QC. Tier A 34, tier B 18. Reference set, not a finished model validation |
| ADA catalog, one row per INN | 170 | Index generated 2026-03-31 | 169 have a reported incidence. Evidence tiers A/B/C = 113/46/11 |
| ADA table rows that also have VH and VL | 128 of 299 | 2026-10-02 | All 299 rows have an ADA percent. 171 rows have no evidence tier filled in |

Definitions, the other format tables, and literature benchmark pairs are in [Clinical antibody evidence](projects/clinical-antibody-evidence.md).

## Projects

| Project | What exists now | Public page |
|---|---|---|
| [AbEngineCore](projects/abenginecore.md) | Private humanization comparison and example reports. A multi-factor framework ranking model is in development and is not frozen. | [muMAb4D5 humanization example](https://insynbio.com/case_mumab4d5_humanization_en.html) |
| [Clinical antibody evidence](projects/clinical-antibody-evidence.md) | Sequence tables, parent-to-humanized pairs, and ADA catalogs, with the gaps noted above. | [ADA browser](https://insynbio.com/ada_database.html) |
| [CMC Atlas](projects/cmc-atlas.md) | Computed sequence proxies (pI, GRAVY, charge, instability) on the therapeutic tables. Not measured CMC results. | [muMAb4D5 CMC example](https://insynbio.com/case_mumab4d5_cmc.html) |
| [CAR-T and ADC materials](projects/cart-adc.md) | A public component browser and design examples. Not a system that issues a development decision. | [CAR component browser](https://insynbio.com/component-browser.html) |

The console Atlas URL asks for a sign-in, so it is not listed here.

## Papers

These are papers that list Jing Huang at the Aaron Diamond AIDS Research Center. The 2022 paper also lists Columbia University Irving Medical Center.

- Huang J, et al. An AAV vector-mediated gene delivery approach facilitates reconstitution of functional human CD8+ T cells in mice. *PLoS ONE*. 2014. [doi:10.1371/journal.pone.0088205](https://doi.org/10.1371/journal.pone.0088205)
- Kotraiah V, et al. Novel peptide-based PD1 immunomodulators demonstrate efficacy in infectious disease vaccines and therapeutics. *Frontiers in Immunology*. 2020. [doi:10.3389/fimmu.2020.00264](https://doi.org/10.3389/fimmu.2020.00264)
- Phares TW, et al. A peptide-based PD1 antagonist enhances T-cell priming and efficacy of a prophylactic malaria vaccine. *Frontiers in Immunology*. 2020. [doi:10.3389/fimmu.2020.01377](https://doi.org/10.3389/fimmu.2020.01377)
- Phares TW, Huang J, et al. Viral delivery of a peptide-based immunomodulator enhances T cell priming during vaccination. *Frontiers in Pharmacology*. 2022. Co-first author. [doi:10.3389/fphar.2022.1029636](https://doi.org/10.3389/fphar.2022.1029636)

The 2020 PD-1 papers include Leidos coauthors. Her affiliation on those papers is the Aaron Diamond AIDS Research Center.

## Experimental biology

[Genomab](https://www.genomab.com/) describes humanized immune-system mouse models, including NVGT mice with lymph-node development. An NIH SBIR Phase I application for this platform was prepared; this page does not claim an award.

I am interested in collaborations in antibody engineering, translational immunology, and preclinical model work.
