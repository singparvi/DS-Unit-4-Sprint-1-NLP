### Getting Conda and setting up virtual environment

1. Making new environment

```bash
conda create -n U4-S1-NLP python==3.7
source activate U4-S1-NLP

pip install -r requirements.txt
python -m ipykernel install --user --name U4-S1-NLP --display-name "U4-S1-NLP (Python3)"  # add an Ipython Kernel reference to your conda environment, so we can use it from JupyterLab.  => This will add a json object to an ipython file, so JupterLab will know that it can use this isolated instance of Python when running interactive notebooks.
python -m spacy download en_core_web_md
jupyter lab
/Users/rob/opt/anaconda3/bin/activate && conda activate /Users/rob/opt/anaconda3/envs/U4-S1-NLP; # activate conda environment with prebuilt requirements




```