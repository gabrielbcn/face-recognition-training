
## Learning Moments
# Face recognition with inception

![Inception](meme.png)

### To install in a mac:

* Become admin
* With privileges, open a terminal and install brew: 
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
* Note the commands from brew installation that you need to cut and paste to make brew work.
* Install miniconda: 
```
brew install miniconda
```
* Install vscode: 
```
brew install visual-studio-code
```
* Install graphviz (without zscaler... library to visualise models): 
```
brew install graphviz
```
* Clone this repo: 
```
git clone https://github.com/gabrielbcn/face-recognition-training.git
```
* Go to the cloned folder: 
```
cd face-recognition-training
```

And follow the instructions in the notebook which are the following:

* If new to conda:
```
conda init zsh
```
* Create a virtual environment for this experiment: 
```
conda create --name TDF_face python=3.12
```
* Activate the environment: 
```
conda activate TDF_face
```
* Install interactive python: 
```
pip install ipykernel
```

Now you can open VSCode, open the notebook and follow there.
```
code .
```
