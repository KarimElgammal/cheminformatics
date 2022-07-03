# cheminformatics
 
Generate xyz files from smiles and fetch some experimental properties
---------------------------------------------------------------------
In the folder: "process_smiles" [process smiles] (https://github.com/KarimElgammal/cheminformatics/blob/main/process_smiles/smiles2xyz.ipynb)
, I wrote simple code with different functionalities to convert a list of smiles stored in an excel sheet to xyz while storing multiple related details in the 2nd line of each of the xyz files
The scheme of the 2nd line works as follow:
* molecule name
* molecular formula 
* molecular weight (g/mol)
* experimental boiling point (degC)
* experimental melting point (degC)

###Used dependicies:
-------------------
Here, I used the awesome Leruli tool and rdkit <br>
for more about Leruli, please check https://www.leruli.com/ installable using: pip install leruli <br>
for more about rdkit, please check https://www.rdkit.org/   installable using: pip install rdkit
for more about plams, please check https://www.scm.com/doc/plams/index.html installable using: pip install plams

ofcourse, those functionalities are implemented in so many libraries, I just find those tools handy

What I like in Leruli is that it gives so many useful information in a efficient way and free of charge


###example:
--------
Aspirin.xyz
<br>14
<br>Aspirin C1COCCO1 88.05 101.605 -16.565
<br>C -0.731 1.16 0.225
<br>C 0.732 1.16 -0.225
<br>O 1.393 -0.0 0.236
<br>C 0.732 -1.16 -0.223
<br>C -0.733 -1.16 0.223
<br>O -1.393 0.001 -0.235
<br>H -0.774 1.202 1.324
<br>H -1.268 2.011 -0.196
<br>H 0.775 1.201 -1.324
<br>H 1.27 2.01 0.196
<br>H 1.268 -2.01 0.2
<br>H 0.777 -1.205 -1.322
<br>H -1.27 -2.009 -0.201
<br>H -0.778 -1.204 1.322

Please feel free to recommend other tools or corrections to this code!