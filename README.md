# biopython_notebook
This is the list of small projects using Python for bio

pip install jupyterlab
pip install py3Dmol
(make sure your node version is 10+)
jupyter labextension install jupyterlab_3dmol
Run: 
you will see "http://localhost:8888/tree" in your browser
Click "New" > Python Notebook

paste the content below:
import py3Dmol
view = py3Dmol.view(query='pdb:1ubq')
view.setStyle({'cartoon':{'color':'spectrum'}})
view

click Run
