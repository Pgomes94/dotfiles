# ZSH SETUP

1) brew install zsh zsh-completions

2) Move the 4 files in this directory to the ~/ directory and change the files names from 'file' to '.file'

3) Move the directory 'zprezto' to the ~/ directory and change the directory name to '.zprezto'

# Updating

Update command: 
	git pull && git submodule update --init --recursive

Before updating, the git repo .zprezto must be reverted.
Before reverting, move the file zprezto/modules/prompt/functions/prompt_jerome_setup outside of the git repo.
Replace the file once updating is complete.
