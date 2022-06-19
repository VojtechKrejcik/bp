# Analysis of approximate circuits created by evolutionary algorithm
The goal of this thesis is analyzing a large library of approximate circuits (EvoApproxLib)
which was created using an evolutionary algorithm and used as a source of genetic data for
the purposes of this thesis. More specifically it is a relatedness search in a file containing
24 912 8-bit approximate multipliers which were created by evolution from six different
fully functioning parent implementations of multiplication. Gate counts and existence of
16 specific subcircuits were used as relatedness indicators. Various classifiers for assigning
multipliers to one of six classes corresponding to parent implementations were trained based
on these indicators. A classification success rate of up to 77% was achieved using said
indicators. The results of this work show that combinations of specific subcircuits are a
strong indicator for identifying which parent circuit the given approximate circuit comes
from.

Results of classification
![](images/tabulky.png)
Visualization of seeked circuits
![](images/hlede_podobvody.png)
Number of occurrencies of seeked circuits
![](images/boxplot.png)
![](images/gates_bar.png)
Relation of number of occurrencies subcircuits and area of circuit
![](images/podobvodarea5.png)

