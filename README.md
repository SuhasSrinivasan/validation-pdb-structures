# Diverse PDB structures to validate structural prediction methods

These structures were collected from PDB to validate [Apple Silicon GPU inference support for AlphaFold 3](https://github.com/google-deepmind/alphafold3/pull/699).
Apple Silicon GPU support for AlphaFold 3 was released in [v3.0.4](https://github.com/google-deepmind/alphafold3/releases/tag/v3.0.4).

All the collected structures from PDB are documented in this [manifest](https://github.com/SuhasSrinivasan/validation-pdb-structures/blob/main/af3_input_json/manifest.json).

There are 4 structures in each of the 12 categories and an additional 4 structures to measure inference for large token sizes.

| Type | n |
|---|--:|
| monomer | 4 |
| hetero-trimer | 4 |
| protein-DNA-ligand | 4 |
| polymer-ligand | 4 |
| protein-RNA | 4 |
| hetero-dimer | 4 |
| protein-protein-ligand-ion | 4 |
| monomer-ligand | 4 |
| homo-polymer | 4 |
| protein-RNA-ligand | 4 |
| hetero-tetramer | 4 |
| protein-DNA | 4 |
| large (1.5–2.2k tokens) | 4 |

