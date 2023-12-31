USRAMP stands for Ultrafast shape-recognition algorithm with mass ponderation. USRAMP is an easy-to-use program to discriminate similar molecules in a list. The USRAMP program requires a list of concatenated molecules in XYZ format and an optional tolerance parameter as input parameters. The input file name can be anything if it contains at least two joined molecules in XYZ format. If you don't have a valid xyz file, USRAMP can create a sample file as appropriate.

Installing USRAMP
===============

You can install and uninstall with:

```
# install
pip3 install usramp

# invoque as:
x.usramp.py

# uninstall
pip3 uninstall usramp
```

or

```
# install
git clone https://github.com/fortizchi/usramp
cd usramp/dist/
python3 -m pip install   usramp-0.1-py3-none-any.whl --upgrade --no-cache-dir

# invoque as:
x.usramp.py

# uninstall
python3 -m pip uninstall usramp-0.1-py3-none-any.whl
```

Running USRAMP
===============

```
x.usramp.py
```
