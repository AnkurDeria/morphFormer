# Learning Spectral-Spatial Morphological Attention Transformer for Hyperspectral Image Classification
[Swalpa Kumar Roy](https://swalpa.github.io), [Ankur Deria](https://ankurderia.github.io), [Chiranjibi Shah]()

<strong>:fire:New:bangbang:</strong></font></sup> Code will be available here soon.
___________

The repository contains the implementations for Learning Spectral-Spatial Morphological Attention Transformer for Hyperspectral Image Classification.



---------------------
### Dataset

* **Trento** AISA Eagle sensors were used to collect HSI data over rural regions in the south of Trento, Italy, where the Optech ALTM 3100EA sensors collected LiDAR data. There are 63 bands in each HSI with wavelength ranging from 0.42-0.99 μm. The spectral resolution is 9.2 nm, and the spatial resolution is 1 meters per pixel. The scene comprises 6 vegetation land-cover classes that are mutually exclusive and a pixel count of 600 × 166.

* **Muffle** The MUUFL Gulfport scene was collected over the campus of the University of Southern Mississippi in November 2010 using the Reflective Optics System Imaging Spectrometer (ROSIS) sensor. There are 325 × 220 pixels with 72 spectral bands in the HSI of this dataset. The 8 initial and final bands were removed due to noise, giving a total of 64 bands. The data depicts 11 urban land-cover classes containing 53687 ground truth pixels.

* **Houston** was acquired by the ITRES CASI-1500 sensor over the University of Houston campus, TX, USA, in June 2012. This data set was originally released by the 2013 IEEE GRSS data fusion contest2, and it has been widely applied for evaluating the performance of land cover classification. The original image is 349 × 1905 pixels recorded in 144 bands ranging from 0.364 to 1.046 μm.

* **Augsburg** scene includes an HSI image captured by DAS-EOC, DLR over the city of Augsburg, Germany. The collection is done by the Sentinel-1 sensor. The spatial resolutions of the image is down-sampled to a unified spatial resolution of 30 m ground sampling distance (GSD). There are 332 × 485 pixels and 180 spectral bands ranging between 0.4-2.5 μm in the HS image.

## Models

The following traditional machine learning methods will be available:

- [x] [RF](https://ieeexplore.ieee.org/document/1396322) 
- [x] [SVM](https://ieeexplore.ieee.org/document/1323134) 
- [x] [RNN](https://ieeexplore.ieee.org/document/8662780)
- [x] [KNN](https://ieeexplore.ieee.org/document/9065747) 

The following deep learning methods will be available:

- [x] [CNN-1D](https://www.sciencedirect.com/science/article/pii/S0924271619302187)
- [x] [CNN-2D](https://ieeexplore.ieee.org/document/7326945)
- [x] [CNN-3D](https://ieeexplore.ieee.org/document/8344565)

The following transformer based deep learning methods will be available:

- [x] [ViT](https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers-1)
- [x] [SpectralFormer](https://ieeexplore.ieee.org/document/9627165)
- [x] [morphFormer]()
