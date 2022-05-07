# QSAR-bioconcentration-paper

This paper work is under © Raj Gupta (2022).

<h1> Problem Description </h1> 
A dataset of manually-curated BCF for 779 chemicals was used to determine the mechanisms of bioconcentration, i.e. to predict whether a chemical: <br>
 (1) is mainly stored within lipid tissues. <br>
 (2) has additional storage sites (e.g. proteins).<br>
 (3) is metabolized/eliminated.

<br>
<h1> Attribute Information: </h1> 
3 Compound identifiers:<br>
-> CAS number<br>
-> Molecular SMILES<br>
-> Train/test splitting<br><br>
9 molecular descriptors (independent variables)<br>
-> nHM<br>
-> piPC09<br>
-> PCD<br>
-> X2Av<br>
-> MLOGP<br>
-> ON1V<br>
-> N-072<br>
-> B02[C-N]<br>
-> F04[C-O]<br><br>
1 experimental responses:<br>
-> Bioaccumulation class (three classes)

<br><br>

<h1> Previous Work on dataset </h1><br>
-> Data were randomly split into a training set of 584 compounds (75%) and a test set of 195 compounds (25%), preserving the proportion between the classes.<br> 
-> Two QSAR classification trees were developed using CART (Classification and Regression Trees) machine learning technique coupled with Genetic Algorithms.<br>
->  The file contains the selected Dragon descriptors (9) along with CAS, SMILES, experimental BCF, experimental/predicted KOW and mechanistic class (1, 2, 3). <br>
-> Further details on model development and performance along with descriptor definitions and interpretation are provided in the original manuscript (Grisoni et al., 2016).
