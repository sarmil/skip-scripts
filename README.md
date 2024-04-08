# skip-scripts
Helper Scripts for the SKIP team. Can be added to PATH after cloning


## kubesu
Script for changing user context in kubernetes. Make sure you install fzf
and login with `gcloud auth login` on any accounts you'd like to use before using this script.
The script can be used by typing `kubesu` in the terminal.
To use add the following to your .bashrc or .zshrc file:
```bash
source /path/to/kubesu.sh
```
If you use fish, the same result can be achieved with:
```bash
alias kubesu='bash -c "source /path/to/kubesu.sh; kubesu"'
```
