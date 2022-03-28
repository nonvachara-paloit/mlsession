## Environments

- (optional) Install pycharm community https://www.jetbrains.com/pycharm/download/#section=mac
- Install miniconda https://repo.anaconda.com/miniconda/Miniconda3-py39_4.11.0-MacOSX-x86_64.pkg
- conda create -n mlsession python==3.7.11
- conda activate mlsession
- mkdir mlsession && cd mlsession
- mkdir titanic && cd titanic
- pip install kaggle
- Go to https://www.kaggle.com/
- Create an account if you don't have one
- Go to account page
- Click 'Create new API token', this will download kaggle.json
- move kaggle.json to ~/.kaggle/kaggle.json
- chmod 600 ~/.kaggle/kaggle.json
- Go to https://www.kaggle.com/c/titanic/data
  - This is the first dataset that we're going to play with
  - Make sure you've joined the competition (I'm not sure if you can download data without joining)
- kaggle competitions download -c titanic
- unzip titanic.zip

## Conda packages

conda install pandas numpy matplotlib seaborn scikit-learn jupyter

