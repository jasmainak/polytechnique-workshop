A crash course in MEG and EEG analysis with Python
==================================================

What you will need?
-------------------

- A working [Anaconda installation](https://www.continuum.io/downloads)
- An editor. For example, [Sublime text](https://www.sublimetext.com/) or [Atom](https://atom.io/)
- MNE-Python [[How to install]](https://martinos.org/mne/stable/install_mne_python.html)
  Try running `python -c 'import mne'` to check if it installed correctly.
- The EEGBCI and MNE sample dataset (~xxx MB). To download, in ipython do:
  ```python
  from mne.datasets import eegbci, sample
  eegbci.load_data(1, [6, 10, 14])
  ```

What's next?
------------

Check out the Jupyter notebooks.