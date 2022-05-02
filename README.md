# melecule_solubility_app
![solubility-logo](https://user-images.githubusercontent.com/91341004/166319326-a10e6703-a670-4445-bc0b-3aa9d3b01e5f.jpg)

In this repository there is the surce code for the application `molecule_solubility_app` which allows the user to input a SMILE formula, e.g. the aspirin  CC(=O)OC1=CC=CC=C1C(=O)O, and it predicts its solubility (in log scale). We've trained a simple linear model to predict the solubility value from some features. The dataset we used for the training process is the following: *John S. Delaney. ESOL:  Estimating Aqueous Solubility Directly from Molecular Structure. J. Chem. Inf. Comput. Sci. 2004, 44, 3, 1000-1005.*

Here is the link at the app: https://share.streamlit.io/leonardolavagna/melecule_solubility_app/main/solubility-app.py. On the left hend side it is possible to input one ore more SMILE formula (divided by a newline) and then the system will provide the solubility prediction based on some molecular descriptors. Notice that at the beginning some default SMILE formula are provided.
