# commands
useful terminal, Python, Node (npm) rare commands you may be need some where

---
# LINUX TERMINAL
---
# PYTHON

## PIP/Virtual Environment
* Upgarde setup tool
 ```terminal
pip install --upgrade pip setuptools
```  
### Clean virtual env without deleting it
 ```terminal
 pip freeze | xargs pip uninstall -y
 ```
 ```
 python -m venv --clear
```

---
# NODE and NPM

# CUDA
* To remove the ambiguous metapackage
`sudo apt-get autoremove cuda`
* Install specific version
`sudo apt-get install -y cuda-toolkit-12-1`

<details>
<summary>👉 Click here to see the Advanced Configuration Details</summary>

This is a hidden section that only appears when you click the summary text.

You can put any markdown inside here, like:
* A list item
* Another list item

```javascript
// even a code block
console.log("Hello from a details block!");
