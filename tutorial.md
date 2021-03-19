Open google colab
! git clone https://github.com/NewSoftwareCulture/Graph-CNN-in-3D-Point-Cloud-Classification.git
! cd Graph-CNN-in-3D-Point-Cloud-Classification/data && wget --no-check-certificate https://shapenet.cs.stanford.edu/media/modelnet40_ply_hdf5_2048.zip
! cd Graph-CNN-in-3D-Point-Cloud-Classification/data && unzip modelnet40_ply_hdf5_2048.zip
! cd Graph-CNN-in-3D-Point-Cloud-Classification && pip2 install -r requirements.txt
! pip2 install h5py
! cd Graph-CNN-in-3D-Point-Cloud-Classification/global_pooling_model && python2 main.py
