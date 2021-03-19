# Graph-CNN-in-3D-Point-Cloud-Classification (PointGCN) x Google Colab


## Prerequisites

```
Python 2.7 
```

***

### Cloning from repository

```console
  ! git clone https://github.com/NewSoftwareCulture/Graph-CNN-in-3D-Point-Cloud-Classification.git
```

###  Download data

```console
  ! cd Graph-CNN-in-3D-Point-Cloud-Classification/data && wget --no-check-certificate https://shapenet.cs.stanford.edu/media/modelnet40_ply_hdf5_2048.zip
```

###  Unzip data

```console
  ! cd Graph-CNN-in-3D-Point-Cloud-Classification/data && unzip modelnet40_ply_hdf5_2048.zip
```

###  Install requirements

```console
  ! cd Graph-CNN-in-3D-Point-Cloud-Classification && pip2 install -r requirements.txt
```

###  Install h5py (optional)

```console
  ! pip2 install h5py
```

###  Run GCNN

```console
  ! cd Graph-CNN-in-3D-Point-Cloud-Classification/global_pooling_model && python2 main.py
```