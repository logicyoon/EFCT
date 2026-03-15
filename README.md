# FractionalCompositionTable

This repository provides **Fractional Composition Tables** introduced by Yoon & Kwak (2026, in progress).

All tables in FCT_csv contain this data:

* Ratio between hydrogen ($n_X$) and helium nuclei ($n_Y$)
* $n_{tot}$: total density
* $T$: temperature
* Equilibrium abundances as fraction ($A_i$ for chemical species $i$)

Each column in the .csv tables stands for:
```csv
n_X	n_Y	n_tot	T	A_H	A_H+	A_H2	A_H-	A_H2+	A_He	A_He+	A_He++
```

Here is the link to the FCT for each radiation profile:

|Blackbody|Constant|Power-law|
|:---:|:---:|:---:|
|[B_weak](./FCT_csv/eqtable_b_weak.csv)|[C_weak](./FCT_csv/eqtable_c_weak.csv)|[P_weak](./FCT_csv/eqtable_p_weak.csv)|
|[B_strong](./FCT_csv/eqtable_b_strong.csv)|[C_strong](./FCT_csv/eqtable_c_strong.csv)|[P_strong](./FCT_csv/eqtable_p_strong.csv)|
