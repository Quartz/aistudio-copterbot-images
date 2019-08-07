# Process Notes

This is my scratchpad for things I want to remember about coding this project. Definitely not documentation, but may be helpful (at least for me). John Keefe

## Environment management

Trying out some environment management tricks to help make this work for everyone.

using venv:

`python3 -m venv env`

then storing requirements with: 

`pip freeze > requirements.txt.`

---

or with Conda: 

```
# create env named my_proj
conda create -n my_proj

# activate env
# (Using 'copters' for this project)
source activate copters

# install pip
conda install pip
```

Now, do the real work, writing your code. You can use `pip install` or `conda install` to install your packages.

(from https://medium.com/small-things-about-python/a-simple-python-workflow-for-devops-85536d514682)

Then ... if you choose the pip route to install packages, just do pip `freeze > requirements.txt` and `pip install -r requirements.txt`

