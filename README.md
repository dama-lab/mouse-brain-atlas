# Multi-template MRI mouse brain atlas (in vivo and ex vivo)
[![DOI](https://zenodo.org/badge/166476589.svg)](https://zenodo.org/badge/latestdoi/166476589)

Mouse Brain MRI atlas (both in-vivo and ex-vivo) (repository relocated from the [original webpage](http://cmic.cs.ucl.ac.uk/staff/da_ma/multi_atlas/))

**List of atlases**

- [`FVB_NCrl`](https://github.com/dancebean/mouse-brain-atlas/tree/master/FVB_NCrl): Brain MRI atlas of the whld-type `FVB_NCrl` mouse strain (used as the background strain for the  `rTg4510` which is a tauopathy model mice express a repressible form of human tau containing the P301L mutation that has been linked with familial frontotemporal dementia.)

- [`NeAt`](https://github.com/dancebean/mouse-brain-atlas/tree/master/NeAt): Brain MRI atlas of the whld-type `C57BL/6J` mouse strain. Atlas was created based on the original [`MRM NeAt`](http://brainatlas.mbi.ufl.edu/) mouse brain atlas (template images reoriented and bias-corrected, left/right structure label seperated, and 4th ventricle manual segmentation added).

- [`Tc1 Cerebellum`](https://github.com/dancebean/mouse-brain-atlas/tree/master/Tc1_Cerebellum/): TC1 mouse cerebellar cortical sublayer lobules.This mouse cerebellar atlas can be used for mouse cerebellar morphometry.

This atlas can be used by the corresponding [automatic mouse brain segmentation tools](https://github.com/dancebean/multi-atlas-segmentation), which can use the in-vivo/ex-vivo atlas here to perform multi-atlas structural parellation based on non-rigid registration and label fusion.

![Sample image of ex vivo atlas](https://github.com/dancebean/multi-atlas-segmentation/blob/master/docs/quickcheckdemo.png) [Click for sample quality control image of the parcellation output (generated using mas_quickcheck). The similar color between the olfactory bulb and the cortex is due to the limited colormap of `jet`.](https://github.com/dancebean/multi-atlas-segmentation/blob/master/docs/quickcheckdemo.png)

![TC1 Cerebellum](https://github.com/dancebean/mouse-brain-atlas/blob/master/docs/segmentation_qc_all_28_original_aspect_ratio.png)

**Citation**

- If you use the segmented brain structure, or use the atlas along with the [automatic mouse brain MRI segmentation tools](https://github.com/dancebean/multi-atlas-segmentation), we ask you to kindly cite the following papers:

  - Ma D, Cardoso MJ, Modat M, Powell N, Wells J, Holmes H, Wiseman F, Tybulewicz V, Fisher E, Lythgoe MF, Ourselin S. **Automatic structural parcellation of mouse brain MRI using multi-atlas label fusion.** PloS one. 2014 Jan 27;9(1):e86576.
http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0086576

  - Ma D, Holmes HE, Cardoso MJ, Modat M, Harrison IF, Powell NM, O'Callaghan J, Ismail O, Johnson RA, O’Neill MJ, Collins EC, Mirza F. Beg, Karteek Popuri, Mark F. Lythgoe, and Sebastien Ourselin **Study the longitudinal in vivo and cross-sectional ex vivo brain volume difference for disease progression and treatment effect on mouse model of tauopathy using automated MRI structural parcellation.** Frontiers in Neuroscience. 2019;13:11.
https://www.frontiersin.org/articles/10.3389/fnins.2019.00011

- If you use the brain MR images of the `FVB_NCrl` mouse strain (the wildtype background of rTg4510), we ask you to kindly cite the following papers: 

  - Wells JA, O'Callaghan JM, Holmes HE, Powell NM, Johnson RA, Siow B, Torrealdea F, Ismail O, Walker-Samuel S, Golay X, Rega M. **In vivo imaging of tau pathology using multi-parametric quantitative MRI. Neuroimage.** 2015 May 1;111:369-78.
https://www.sciencedirect.com/science/article/pii/S105381191500124X

  - Holmes HE, Colgan N, Ismail O, Ma D, Powell NM, O'Callaghan JM, Harrison IF, Johnson RA, Murray TK, Ahmed Z, Heggenes M. **Imaging the accumulation and suppression of tau pathology using multiparametric MRI.** Neurobiology of aging. 2016 Mar 1;39:184-94.
https://www.sciencedirect.com/science/article/pii/S0197458015006053

  - Holmes HE, Powell NM, Ma D, Ismail O, Harrison IF, Wells JA, Colgan N, O'Callaghan JM, Johnson RA, Murray TK, Ahmed Z. **Comparison of in vivo and ex vivo MRI for the detection of structural abnormalities in a mouse model of tauopathy.** Frontiers in neuroinformatics. 2017 Mar 31;11:20.
https://www.frontiersin.org/articles/10.3389/fninf.2017.00020/full

- If you're using the [mouse MRI T2* Active Starining Cerebellar atlas](Tc1_Cerebellum), we ask you to please kindly cite the following papers:
  - Ma, D., Cardoso, M. J., Zuluaga, M. A., Modat, M., Powell, N. M., Wiseman, F. K., Cleary, J. O., Sinclair, B., Harrison, I. F., Siow, B., Popuri, K., Lee, S., Matsubara, J. A., Sarunic, M. V, Beg, M. F., Tybulewicz, V. L. J., Fisher, E. M. C., Lythgoe, M. F., & Ourselin, S. (2020). Substantially thinner internal granular layer and reduced molecular layer surface in the cerebellum of the Tc1 mouse model of Down Syndrome – a comprehensive morphometric analysis with active staining contrast-enhanced MRI. NeuroImage, 117271. https://doi.org/https://doi.org/10.1016/j.neuroimage.2020.117271
  - Ma, D., Cardoso, M. J., Zuluaga, M. A., Modat, M., Powell, N., Wiseman, F., Tybulewicz, V., Fisher, E., Lythgoe, M. F., & Ourselin, S. (2015). Grey Matter Sublayer Thickness Estimation in the Mouse Cerebellum. In Medical Image Computing and Computer Assisted Intervention 2015 (pp. 644–651). https://doi.org/10.1007/978-3-319-24574-4_77
  

**Reference**
- For the original information of the `NeAt` atlas, please please refer to the website: http://brainatlas.mbi.ufl.edu/, and the following two reference papers:
  - Ma Yu, Smith David, Hof Patrick R, Foerster Bernd, Hamilton Scott, Blackband Stephen J, Yu Mei, Benveniste Helene **In Vivo 3D Digital Atlas Database of the Adult C57BL/6J Mouse Brain by Magnetic Resonance Microscopy**. Front. Neuroanat. 2, 1 (2008).
  - Ma Yu,  Hof P R,  Grant S C,  Blackband S J,  Bennett R,  Slatest L,  McGuigan M D,  Benveniste H **A three-dimensional digital atlas database of the adult C57BL/6J mouse brain by magnetic resonance microscopy**. Neuroscience 135, 1203–15 (2005).
