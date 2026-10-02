# Clinical antibody evidence

Counted from private tables on 2 October 2026, except where a file’s own timestamp is given. Tables overlap. Do not add the rows into one total.

The public site still says 1,142 clinical sequences and 138 ADA records. Those headlines were not reproduced by the counts below. The local JSON file whose name contains “1142” contains **70** antibody records (69 with both a heavy and a light chain; 69 with a numeric ADA percent). File date: 16 September 2026.

## Sequence tables

A complete chain here means at least 80 amino acids.

| Table | Rows | Complete sequences | Notes |
|---|---:|---|---|
| Engineered therapeutics | 458 | 458 with VH and VL | Folder name says 459 |
| Fully human therapeutics | 384 | 384 with VH and VL | Folder name says 380 |
| VHH clinical | 40 | 39 with a VHH sequence | Folder name says 39 |
| Bispecific | 78 | 73 with arm-1 VH and VL | This is arm 1 only, not both arms |
| scFv | 56 | 52 with VH and VL | Four rows lack both chains |

The chimeric, ADC, Fab-fusion, and “other” index tables in the same collection do not carry full sequences in the columns that were counted, so they are not included as sequence totals.

## Parent-to-humanized pairs

| Set | Count | What it is |
|---|---:|---|
| Clinical pairs | 52 | Audit `CLINICAL-52` on 1 October 2026. QC pass 52/52. Both parent and clinical VH/VL are present. Tier A 34, tier B 18 |
| Internal usable-pair union | 309 | Union of the 52 sequence-complete clinical pairs and a 291-pair reference table. 34 names sit in both, so 309 is not 52+291 |
| Hu-mAb / BioPhi benchmark | 25 | Literature benchmark pairs, kept separate from the clinical 52 |
| Humatch experimental pairs | 25 | Zenodo precursor/experimental sequences used for overlap audit. Separate from the clinical 52 |
| HuAbDiffusion Table S8 | 22 | External humanization pairs. Separate from the clinical 52 |

HuAb348-scale tables are external humanization-pair evidence. They are not counted here as clinical pairs.

## ADA coverage

Two catalogs, not one number:

| Catalog | Count | Date | Limit |
|---|---:|---|---|
| INN index | 170 | Generated 31 March 2026 | 169 with a reported incidence. Tiers A/B/C = 113/46/11 |
| Curated ADA table | 299 rows | Counted 2 October 2026 | Every row has an ADA percent. Only 128 also have VH and VL. Evidence tier is blank for 171 rows. The folder name says 245; the file has 299 rows |
| 70-record display cohort | 70 | File date 16 September 2026 | 69 numeric ADA values. This is the file named for 1,142 |

The public [ADA browser](https://insynbio.com/ada_database.html) was reachable on 2 October 2026. Its page headline is the older 138 figure, not the index above.

## What this is not

Clinical ADA percent mixes indication, assay, dose, and concomitant treatment. These tables do not by themselves show that a sequence feature predicts immunogenicity.
