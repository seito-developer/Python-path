#/bin/bashの場合  
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile  
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile  
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile  
source ~/.bash_profile  

#/bin/zshの場合  
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc  
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc  
echo 'eval "$(pyenv init -)"' >> ~/.zshrc  
source ~/.zshrc
