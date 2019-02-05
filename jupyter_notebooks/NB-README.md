This directory contains the Python Jupyter notebooks which accompany the review.

More information can be found on [https://physics.bu.edu/~pankajm/MLnotebooks.html](https://physics.bu.edu/~pankajm/MLnotebooks.html).

### to run jupyter notebooks from a custom conda environment called 'myenv' below, do

source activate myenv

conda install ipykernel
python -m ipykernel install --user --name myenv --display-name "Python myenv"

### load this package to enable spell check in jupyter. Notethat the spell check is available in the edit mode of the cell.

https://github.com/ipython-contrib/jupyter_contrib_nbextensions

1) First, install the library using pip. From the command line, run the following command:

pip install jupyter_contrib_nbextensions

2) Second, configure the library with your jupter. Run the following command:

jupyter contrib nbextension install --user

3) Third, enable the extension. Run the following command:

jupyter nbextension enable spellchecker/main

4) If the extension is installed properly, you will see this message in the command line: 

Enabling notebook extension spellchecker/main...
      - Validating: OK

5) Now, in the browser, after opening a jupyter notebook, you will see the button labeled with "abc" beside the keyboard button. Click to enable spell check. 

The library has many other cool modules that are very useful. To name few, code folding, and table of content.

