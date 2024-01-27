A dataset of manually-curated BCF for 779 chemicals was used to determine the mechanisms of bioconcentration, i.e. to predict whether a chemical: (1) is mainly stored within lipid tissues, (2) has additional storage sites (e.g. proteins), or (3) is metabolized/eliminated. 
Data definition:
1-CAS: Chemical Abstracts Service registry number.
2-SMILES: Simplified Molecular Input Line Entry System, a notation that allows a user to represent a chemical structure in a way that can be used by the computer.
3-nHM: Number of heavy atoms.
4-piPC09: Molecular path index based on the 09u path matrix.
5-PCD: Petitjean shape index.
6-X2Av: Average molecular information index.
7-MLOGP: Molecular LogP (partition coefficient).
8-ON1V: Onizuka's shape index.
9-N-072: Number of rotatable bonds.
10-B02[C-N]: Presence or absence of the SMARTS pattern B02[C-N].
11-F04[C-O]: Presence or absence of the SMARTS pattern F04[C-O].
12-logBCF: Logarithm of the bioconcentration factor (BCF), which is the ratio of a chemical's concentration in an organism to its concentration in the surrounding environment.
13-Class: The target variable, representing the mechanism of bioconcentration. It can take one of three classes: (1) mainly stored within lipid tissues, (2) has additional storage sites (e.g., proteins), or (3) is metabolized/eliminated.

We build this model only with Machine learning model
