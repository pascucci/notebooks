# notebooks


# Windows 10 instructions

Download `https://www.python.org/ftp/python/3.8.0/python-3.8.0-amd64.exe` and custum-install for all (select all options)

Open a `Command Prompt` ad run:

```
python -m pip install --upgrade pip
python -m pip install notebook wheel
python -m pip install pillow urllib3 matplotlib mpl_interactions ipywidgets ipympl ipycanvas notebook jupyter_contrib_nbextensions pandas 
python -m pip install --upgrade OpenVisus
python -m OpenVisus configure 
python -m jupyter  contrib nbextension install
python -m jupyter nbextension enable --py widgetsnbextension
```
Download and install `https://github.com/git-for-windows/git/releases/download/v2.34.1.windows.1/Git-2.34.1-64-bit.exe`

```
cd /d C:\Users\user\Desktop
git clone https://github.com/nsdf-fabric/notebooks.git
```
