# uv

```
uv python install --default # installs default so you can 'python whatever'
# create default?
mkdir uv
cd uv
uv venv
# install packages like this (uv pip much faster tbh so should use it)
uv pip install ipython
# on linux, .bashrc:
source ~/uv/.venv/bin/activate
# added this on windows to powershell profile:
# create profile file
New-Item $profile -Type File -Force
& "C:\Users\tman\uv\.venv\Scripts\Activate.ps1"
```