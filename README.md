### C-GEM DOI Citations

Converts a sheet containing DOIs to a list of citations to Title, Authors, Date, and Journal.

Outputs the citations to a file called `data_with_citations.csv`.

### Usage

Run doi.ipynb

### TODO

SMILES CONVERSION
-   automatically convert shortname to longname using Hana's

-   remove (R/S) or (S/R) in the beginning
    (R/S)-4-amino-3-hydroxy butyric acid
    ^^^^^
    4-amino-3-hydroxy butyric acid

-   remove periods and everything to the left for SMILES
    [Cl-].C(CCC=C)(=O)SCC1=CC=C(C(=O)NCC[NH3+])C=C1
    ^^^^^^
    C(CCC=C)(=O)SCC1=CC=C(C(=O)NCC[NH3+])C=C1

-   add pipeline for auto extracting the supplemental pdfs
