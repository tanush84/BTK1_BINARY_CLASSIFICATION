END to END ML model for the binary prediction of BTK-1 inhibitors using python script. 

*****

After installing the requirements in an Virtual Environment
or creating a new environment using conda by using "environment_dependencies.yml" file
just open the command prompt or Terminal in the above created virtual environment
run the command given below
### Using Random Forest Algorithm based prediction
python predict_rf_rdkit.py test.smi

### OR 
### Using MLP Algorithm based prediction
python predict_mlp_rdkit.py test.smi

similarly, for any unknown molecule when just use the command by specifying the path
of "*.smi" file.

python predict_name_of_algorithm.py [specify_path]*.smi


The result will be displayed in the terminal as Molecule to be active or Inactive

If you want to know more about the work kindly read our publication
Combining structure-based pharmacophore modeling and machine learning for the identification of novel BTK1 inhibitors

you can cite it using below citation:
Sharma T, Saralamma VVG, Lee DC, Imran MA, Choi J, Baig MH, Dong JJ. Combining structure-based pharmacophore modeling and machine learning for the identification of novel BTK inhibitors. Int J Biol Macromol. 2022 Dec 1;222(Pt A):239-250. doi: 10.1016/j.ijbiomac.2022.09.151. Epub 2022 Sep 18. PMID: 36130643.

The image in repository indicate the ROC curve of the top models.




 
