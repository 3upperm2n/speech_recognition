### Configure environment
Install tensorflow, tflearn using anaconda.

Create your conda env.
```bash
conda create -n speech_dpl python=2
source activate speech_dpl
conda install numpy pandas matplotlib jupyter notebook 
conda install -c anaconda scipy
```

I use pip to install both tensorflow and tflearn. Noted that they are both cpu version.
```
pip install tensorflow tflearn h5py
```
