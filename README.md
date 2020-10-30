# Metabarcoding_Blacklists
This project contains the blacklists that can be used in combination with the https://github.com/Y-Lammers/MergeAndFilter R code in order to filter OBITools metabarcoding datasets.

#### Format
The blacklists are in a `.tsv` format and look like:

```
sequence  description
```

There can be multiple description columns if required.

#### Files

The GH_* files contain blacklisted p6-loop barcodes, either regional or synthetic, produced by the G-H primers (Taberlet et al. 2007).


#### References

Taberlet P, Coissac E, Pompanon F, Gielly L, Miquel C, Valentini A, Vermat T, Corthier G, Brochmann C, Willerslev E. 2007. Power and limitations of the chloroplast trnL (UAA) intron for plant DNA barcoding. Nucleic acids research 35: e14.
