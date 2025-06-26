#                                 COMMANDS
useful terminal, Python, Node (npm) rare commands you may be need some where
-------
---
## LINUX TERMINAL
---
## PYTHON

### PIP/Virtual Environment
#### Upgarde setup tool
 ```terminal
pip install --upgrade pip setuptools
```  
#### Clean virtual env without deleting it
 ```terminal
 pip freeze | xargs pip uninstall -y
 ```
 ```terminal
 python -m venv --clear
```

---
## NODE and NPM

## CUDA

### Life Hacks
#### To remove the ambiguous metapackage
`sudo apt-get autoremove cuda`
#### Install specific version
`sudo apt-get install -y cuda-toolkit-12-1`

