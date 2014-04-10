yt_radio_cubes
==============

IPython notebooks and scripts for `yt` and radio data for the 2014 ALMA
Software Workshop.

These can be viewed with the ipynb viewer:

 * [NGC 253](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jzuhone/yt_radio_cubes/master/ngc_253_evaluated.ipynb)
 * [M33 HI](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jzuhone/yt_radio_cubes/master/m33_hi_evaluated.ipynb)
 * [NGC 253 two files](http://nbviewer.ipython.org/urls/raw.githubusercontent.com/jzuhone/yt_radio_cubes/master/ngc253_two_files_evaluated.ipynb)

To use these notebooks, you will need a working installation of `yt`
and you will need [AstroPy](http://www.astropy.org) installed in the
same Python stack as `yt`. To install the stable version of `yt`, you
may install from the installation script:

```bash
wget http://hg.yt-project.org/yt/raw/stable/doc/install_script.sh
bash install_script.sh
pip install astropy
```

Or if you are using
[Anaconda](https://store.continuum.io/cshop/anaconda/) Python, you can
install via:

```bash
conda install yt astropy mercurial
```

Next, to install the development version of `yt` which includes the latest
changes necessary to read FITS files:

```bash
hg clone http://bitbucket.org/jzuhone/yt-3.x
cd yt-3.x
python setup.py develop
```

To check for updates to the repository, and to check them in:

```bash
hg incoming
hg pull -r tip
hg update
```

