# HyperspectralImageResearch
A collection of Hyperspectral Image research
  
## What is a Hyperspectral Image
"Hyperspectral imaging is a powerful technology combining spectroscopy with imaging capability. It enables gathering detailed information about the composition and characteristics of objects and surfaces in a way that is impossible with conventional imaging systems.

Thanks to its noninvasive, and nondestructive capability in identifying and quantifying material, hyperspectral imaging has become increasingly popular in various industries and research applications."

Captures information across the electromagnetic spectrum, giving a spectrum for each pixel within a scene. Typically creating a 3D data cube, compared to an RGB image which containes three channels a hyperspectral image for example could contain >100 channels.

<img width="661" alt="image" src="https://github.com/RobWilliamson15/HyperspectralImageResearch/assets/98591110/bd4bc765-93a4-40e3-840d-2906565c8eb5"> (https://www.specim.com/technology/what-is-hyperspectral-imaging/)

## Use cases
- Quality control
- Food quality
- Agriculture
- Surveillance
- Environmental monitroing
- Mineral Exploration

## Wavelengths
- Visual 380-800nm
- VNIR 400-1,000nm
- NIR 900-1,700nm
- SWIR 1,000-2,500nm

## Research
(Only including papers which have an open code base)
### Spectral Reconstruction
[State of the art](https://paperswithcode.com/task/spectral-reconstruction)
- MST++: Multi-stage Spectral-wise Transformer for Efficient SPectral Reconstruction [Paper](https://arxiv.org/abs/2111.07910) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)
- Multi-Stage Progressive Image Restoration [Paper](https://arxiv.org/abs/2102.02808) [Code](https://github.com/swz30/MPRNet)
- Restormer: Efficient Transformer for High-Resolution Image Restoration [Paper](https://arxiv.org/abs/2111.09881) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)
- Learning Enriched Features for Real Image Restoration and Enhancement [Paper](https://arxiv.org/abs/2003.06792) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)
- HINet: Half Instance Normalization Network for Image Restoration [Paper](https://arxiv.org/abs/2105.06086) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)
- HDNet: High-resolution Dual-domain Learning for Spectral Compressive Imaging [Paper](https://arxiv.org/abs/2203.02149) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)
- Enhanced Deep Residual Networks for Single Image Super-Resolution [Paper](https://arxiv.org/abs/1707.02921) [Code](https://github.com/caiyuanhao1998/MST-plus-plus)

### Classification
- SpectralDiff: A Generative Framework for Hyperspectral Image Classification With Diffusion Models [Paper](https://ieeexplore.ieee.org/document/10234379) [Code](https://github.com/chenning0115/SpectralDiff?tab=readme-ov-file)

## Challenges
-  [NTIRE 2022 Spectral Recovery](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Arad_NTIRE_2022_Spectral_Recovery_Challenge_and_Data_Set_CVPRW_2022_paper.pdf)
-  [NTIRE 2020 Challenge on Spectral Reconstruction from an RGB Image](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Arad_NTIRE_2020_Challenge_on_Spectral_Reconstruction_From_an_RGB_Image_CVPRW_2020_paper.pdf)
-  [NTIRE 2018 Challenge on Spectral Reconstruction from an RGB Image](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8575291)

## Open Source Datasets
-  [Hyperspectral Remote Sensing Scences](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
-  [CAVE](https://www.cs.columbia.edu/CAVE/databases/multispectral/)
-  [ICVL](https://icvl.cs.bgu.ac.il/hyperspectral/)
-  [Harvard](http://vision.seas.harvard.edu/hyperspec/index.html)
-  [ARAD1k](https://github.com/boazarad/ARAD_1K)
-  [Real HSI](https://github.com/mengziyi64/TSA-Net)

## Standard Measurements
- Peak Signal to noise ratio [PSNR](https://www.geeksforgeeks.org/python-peak-signal-to-noise-ratio-psnr/)
- Structural Similarity [SSIM](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=1284395&casa_token=9zE87t-EW90AAAAA:uuXgiNpQVFJvNpbqsmtaTCtXjuSBgOHAplMI_SC1fCmnJqhUte_6uKR0LMam_Y5jElLpmcEkwg)
- Mean Squared Error [MSE](https://statisticsbyjim.com/regression/mean-squared-error-mse/)
- Root Mean Square Error [RMSE](https://www.statology.org/how-to-interpret-rmse/)
- Spectral Angle Mapper [SAM](https://archive.org/details/NASA_NTRS_Archive_19940012238)
- Relative Dimensionless Global Error [ERGAS](https://www.irjet.net/archives/V7/i6/IRJET-V7I6199.pdf)

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=RobWilliamson15.HyperspectralImageResearch&theme=radical)
