# Cell biology
*****************

**Table of Contents**:

- [cell_imaging processing in chronological order](#cell_imaging_processing_chronological_order)
  - [review](#review)
  - [2D/3D cell segmentation](#2D/3D_cell_segmentation)
  - [2D/3D cell tracking](#2D/3D_cell_tracking)
  - [mitosis detection](#mitosis_detection) 
  - [lineage tracing](#lineage_tracing)
  - [FISH-quant](#FISH-quant)
  - [Insights](#Insight)
- [computer vision](#computer_vision) 
- [cell reprogramming imaging](#cell_reprogramming_imaging)
- [cell mobility analysis](#cell_mobility_analysis)
- [cell movement modelling](#cell_movement_modelling)
- [collective cell behavior](#collective_cell_behavior)
- [cell intelligence](cell_intelligence)
- [single-cell_omics](#single-cell_omics)
- [cell_lineage](#cell_lineage)
*****************


## cell_imaging_processing
### review
[04/19/2021 Developing open-source software for bioimage analysis: opportunities and challenges ,under peer review](https://f1000research.com/articles/10-302).<br>
[04/15/2021 Democratising deep learning for microscopy with ZeroCostDL4Mic, Nature communications](https://www.nature.com/articles/s41467-021-22518-0).<br>
[04/01/2021 Data science in cell imaging, J Cell Sci](https://journals.biologists.com/jcs/article/134/7/jcs254292/238123/Data-science-in-cell-imaging).<br>
[01/04/2021 DeepCell Kiosk: scaling deep learning–enabled cellular image analysis with Kubernetesv, Nature Methods](https://www.nature.com/articles/s41592-020-01023-0).<br>
[05/27/2019 Deep learning for cellular image analysis, nature methods](https://www.nature.com/articles/s41592-019-0403-1).<br>
[11/18/2019 CLIJ: GPU-accelerated image processing for everyone, Nature Methods](https://www.nature.com/articles/s41592-019-0650-1).<br>
[07/2019 Imaging, Visualization, and Computation in Developmental Biology, Annual Review of Biomedical Data Science](https://www.annualreviews.org/doi/abs/10.1146/annurev-biodatasci-072018-021305).<br>
[04/17/2019 Integrating Imaging and Omics: Computational Methods and Challenges, Annual Review of Biomedical Data Science](https://www.annualreviews.org/doi/abs/10.1146/annurev-biodatasci-080917-013328).<br>
[05/18/2019 Single-cell approaches to cell competition: High-throughput imaging, machine learning and simulations, Seminars in Cancer Biology](https://www.sciencedirect.com/science/article/abs/pii/S1044579X18301780?via%3Dihub).<br>
[03/18/2019 Microscopy and Cell Biology: New Methods and New Questions, Annual Review of Physical Chemistry](https://www.annualreviews.org/doi/abs/10.1146/annurev-physchem-042018-052527).<br>
[07/08/2009 Quantitative Time-Lapse Fluorescence Microscopy in Single Cells, Annual Review of Cell and Developmental Biology](https://www.annualreviews.org/doi/abs/10.1146/annurev.cellbio.042308.113408).<br>

### 2D/3D cell segmentation
[04/19/2021 Open-source deep-learning software for bioimage segmentation, MBoC](https://www.molbiolcell.org/doi/abs/10.1091/mbc.E20-10-0660).<br>
[12/08/2020 Cell segmentation and tracking using CNN-based distance predictions and a graph-based matching strategy, PLOS one](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0243219).<br>
[06/15/2020 Star-convex Polyhedra for 3D Object Detection and Segmentation in Microscopy, CVPR](https://openaccess.thecvf.com/content_WACV_2020/papers/Weigert_Star-convex_Polyhedra_for_3D_Object_Detection_and_Segmentation_in_Microscopy_WACV_2020_paper.pdf).<br>
[10/28/2020 Automated cell tracking using StarDist and TrackMate, F1000Res](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7670479/).<br>
[08/31/2018 CDeep3M—Plug-and-Play cloud-based deep learning for image segmentation, Nature Methods](https://www.nature.com/articles/s41592-018-0106-z).<br>
[06/09/2018 Cell Detection with Star-convex Polygons, arXiv](https://arxiv.org/abs/1806.03535).<br>
[07/01/2017 fastER: a user-friendly tool for ultrafast and robust cell segmentation in large-scale microscopy, Bioinformatics](https://academic.oup.com/bioinformatics/article/33/13/2020/3045025).<br>


### 2D/3D cell tracking
[03/30/2021 3DeeCellTracker, a deep learning-based pipeline for segmenting and tracking cells in 3D time lapse images, eLife](https://elifesciences.org/articles/59187).<br>
[03/16/2021 A graph-based cell tracking algorithm with few manually tunable parameters and automated segmentation error correction, Bioaxiv](https://www.biorxiv.org/content/10.1101/2021.03.16.435631v1).<br>
[02/22/2021  CellMAPtracer: A User-Friendly Tracking Tool for Long-Term Migratory and Proliferating Cells Associated with FUCCI Systems, Cells](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7927118/).<br>
[09/10/2020 Automated deep lineage tree analysis using a Bayesian single cell tracking approach, Bioaxiv](https://www.biorxiv.org/content/10.1101/2020.09.10.276980v1).<br>
[08/04/2020 EllipTrack: A Global-Local Cell-Tracking Pipeline for 2D Fluorescence Time-Lapse Microscopy, Cell Reports](https://www.cell.com/cell-reports/fulltext/S2211-1247(20)30969-4).<br>
[10/14/2019 Accurate cell tracking and lineage construction in live-cell imaging experiments with deep learning](https://www.biorxiv.org/content/10.1101/803205v2.full.pdf+html).<br>
[08/26/2019 Toward Robust Fully 3D Filopodium Segmentation and Tracking in Time-Lapse Fluorescence Microscopy](https://ieeexplore.ieee.org/abstract/document/8803721).<br>
[03/29/2019 eDetect: A Fast Error Detection and Correction Tool for Live Cell Imaging Data Analysis, iScience](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6383125/).<br>
[2016 Segmentation and tracking of cells and particles in time-lapse microscopy, Magnusson, Klas Doctoral Thesis](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1049813&dswid=-8323).<br>
[10/30/2017 An objective comparison of cell-tracking algorithms, Nat Methods](https://www.nature.com/articles/nmeth.4473).<br>
[2016 Segmentation and tracking of cells and particles in time-lapse microscopy, Doctoral thesis](https://www.diva-portal.org/smash/get/diva2:1049813/FULLTEXT01.pdf).<br>
[07/12/2016 Software tools for single-cell tracking and quantification of cellular and molecular properties, Nature biotechnology](https://www.nature.com/articles/nbt.3626)<br>
[04/26/2016 Detection and tracking of overlapping cell nuclei for large scale mitosis analyses, BMC Bioinformatics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4845473/).<br>
[11/14/2014 Global linking of cell tracks using the Viterbi algorithm, IEEE Trans Med Imaging](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4765504/).<br>
[06/01/2014 A benchmark for comparison of cell tracking algorithms, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/11/1609/283435?login=true).<br>
[01/19/2014 Objective comparison of particle tracking methods, Nature Methods](https://www.nature.com/articles/nmeth.2808).<br>
[07/12/2012 A batch algorithm using iterative application of the Viterbi algorithm to track cells and construct cell lineages,  2012 9th IEEE International Symposium on Biomedical Imaging (ISBI)](https://ieeexplore.ieee.org/abstract/document/6235564/authors#authors).<br>
[2011 Cell tracking for automated analysis of timelapse microscopy, Magnusson, Klas Master Thesis](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A470908&dswid=-6775).<br>


### mitosis detection
[01/31/2018 DeepMitosis: Mitosis detection via deep detection, verification and segmentation networks, Med Image Anal](https://www.sciencedirect.com/science/article/abs/pii/S1361841517301834?via%3Dihub).<br>

### lineage tracing
[11/08/2016 Moral Lineage Tracing, arXiv](https://arxiv.org/pdf/1511.05512.pdf).<br>
[07/20/2014 Fast, accurate reconstruction of cell lineages from large-scale fluorescence microscopy data, Nature Methods](https://www.nature.com/articles/nmeth.3036/).<br>
[11/08/2013 Long-Term Live Cell Imaging and Automated 4D Analysis of Drosophila Neuroblast Lineages, Plos one](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0079588).<br>

### FISH-quant
[03/09/2021 RS-FISH: Precise, interactive and scalable smFISH spot detection using Radial Symmetry, Bioaxiv](https://www.biorxiv.org/content/10.1101/2021.03.09.434205v1.full.pdf+html).<br>
[11/05/2016 smiFISH and FISH-quant – a flexible single RNA detection approach with super-resolution capability](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5159540/).<br>
### Insights
[09/04/2020 Live-cell imaging and analysis reveal cell phenotypic transition dynamics inherently missing in snapshot data, Sci Adv](https://advances.sciencemag.org/content/6/36/eaba9319).<br>

## computer vision

## cell reprogramming imaging
[04/26/2019 Cell competition during reprogramming gives rise to dominant clones, Science](https://science.sciencemag.org/content/364/6438/eaan0925).<br>
[01/30/2014 Nonstochastic Reprogramming from a Privileged Somatic Cell State, Cell](https://www.cell.com/fulltext/S0092-8674(14)00072-5).<br>
[01/17/2013 Dynamic Migration and Cell‐Cell Interactions of Early Reprogramming Revealed by High‐Resolution Time‐Lapse Imaging, Stem Cells](https://stemcellsjournals.onlinelibrary.wiley.com/doi/full/10.1002/stem.1323).<br>
[05/02/2010 Dynamic single cell imaging of direct reprogramming reveals an early specifying event, Nat Biotech](https://www.nature.com/articles/nbt.16320).<br>





## cell mobility analysis
[12/10/2020 Bridging from single to collective cell migration: A review of models and links to experiments, PLoS computational biology](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008411).<br>

## cell movement modelling

## collective cell behavior
[07/13/2020 Cell-scale biophysical determinants of cell competition in epithelia, Bioaxiv](https://www.biorxiv.org/content/10.1101/729731v2.full.pdf+html).<br>
[08/08/2019 Distinct modes of cell competition are governed by entropic and energetic properties of mixed cell populations, Bioaxiv](https://www.biorxiv.org/content/10.1101/729731v1).<br>
[07/16/2018 Entropic effects in cell lineage tree packings, Nature Physics](https://www.nature.com/articles/s41567-018-0202-0).<br>
[09/20/2017 Local cellular neighborhood controls proliferation in cell competition, MBoC](https://www.molbiolcell.org/doi/10.1091/mbc.e17-06-0368).<br>
[09/07/2016 MitoGen: A Framework for Generating 3D Synthetic Time-Lapse Sequences of Cell Populations in Fluorescence Microscopy, IEEE Transactions on Medical Imaging](https://ieeexplore.ieee.org/abstract/document/7562482).<br>


## cell intelligence

1.[ESC-Track: A computer workflow for 4-D segmentation, tracking, lineage tracing and dynamic context analysis of ESCs](https://pubmed.ncbi.nlm.nih.gov/32720710/).<br>
2.[Automatic three‐dimensional segmentation of mouse embryonic stem cell nuclei by utilising multiple channels of confocal fluorescence images](https://onlinelibrary.wiley.com/doi/10.1111/jmi.12949).<br>
3.[Evaluation of Deep Learning Strategies for Nucleus Segmentation in Fluorescence Images](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23863).<br>
4.[DeLTA: Automated cell segmentation, tracking, and lineage reconstruction using deep learning](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007673).<br>
5.[ChipSeg: an automatic tool to segment bacteria and mammalian cells cultured in microfluidic devices](https://www.biorxiv.org/content/10.1101/2020.08.03.225045v1.abstract).<br>
6.[A Rapid and Efficient 2D/3D Nuclear Segmentation Method for Analysis of Early Mouse Embryo and Stem Cell Image Data](https://www.sciencedirect.com/science/article/pii/S2213671114000277#fig1).<br>
7.[Survey statistics of automated segmentations applied to optical imaging of mammalian cells](https://link.springer.com/article/10.1186/s12859-015-0762-2).<br>
8.[Robust and automated three-dimensional segmentation of densely packed cell nuclei in different biological specimens with Lines-of-Sight decomposition](https://link.springer.com/article/10.1186/s12859-015-0617-x).<br>
9.[Automated Identification and Localization of Hematopoietic Stem Cells in 3D Intravital Microscopy Data](https://www.sciencedirect.com/science/article/pii/S2213671115001605).<br>
10.[A high-throughput imaging and nuclear segmentation analysis protocol for cleared 3D culture models](https://www.nature.com/articles/s41598-018-29169-0).<br>
11.[Segmentation of Nuclei From 3D Microscopy Images of Tissue via Graphcut Optimization](https://ieeexplore.ieee.org/abstract/document/7346405).<br>
12.[3D Clumped Cell Segmentation Using Curvature Based Seeded Watershed](https://www.mdpi.com/2313-433X/2/4/31).<br>
13.[A method for the evaluation of thousands of automated 3D stem cell segmentations](https://onlinelibrary.wiley.com/doi/abs/10.1111/jmi.12303?casa_token=OvrlH5uEexoAAAAA:T88Gs1Emcs8T4BaqOl9AwCBxWKUQTtXLhr9WL2LJhTGCP-MtrYKJlfTbjZAQVs5GpUuo710JUMLBHaY).<br>
14.[Brain development: machine learning analysis of individual stem cells in live 3D tissue](https://www.biorxiv.org/content/10.1101/137406v2.abstract).<br>
15.[NesSys: a novel method for accurate nuclear segmentation in 3D](https://www.biorxiv.org/content/10.1101/502872v1.abstract).<br>
16.[Three-dimensional GPU-accelerated active contours for automated localization of cells in large images](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0215843).<br>
17.[Software tools for 3D nuclei segmentation and quantitative analysis in multicellular aggregates](https://www.sciencedirect.com/science/article/pii/S2001037020302853).<br>
18.[Segmentation of cell nuclei in fluorescence microscopy images: An integrated framework using level set segmentation and touching-cell splitting](https://www.sciencedirect.com/science/article/abs/pii/S0031320316300280).<br>
19.[Nessys: A new set of tools for the automated detection of nuclei within intact tissues and dense 3D cultures](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000388&rev=1).<br>
20.[DeepSynth: Three-dimensional nuclear segmentation of biological images using neural networks trained with synthetic data](https://www.nature.com/articles/s41598-019-54244-5).<br>
21.[3D-Cell-Annotator: an open-source active surface tool for single-cell segmentation in 3D microscopy images](https://academic.oup.com/bioinformatics/article/36/9/2948/5709038?login=true).<br>
22.[GIANI: open-source software for automated analysis of 3D microscopy images](https://www.biorxiv.org/content/10.1101/2020.10.15.340810v1.abstract).<br>
23.[WaveletSEG: Automatic wavelet-based 3D nuclei segmentation and analysis for multicellular embryo quantification](https://www.biorxiv.org/content/10.1101/2020.07.24.220285v1.abstract).<br>
24.[TANGO: a generic tool for high-throughput 3D image analysis for studying nuclear organization](https://academic.oup.com/bioinformatics/article/29/14/1840/231770?login=true).<br>\
25.[CellSegm - a MATLAB toolbox for high-throughput 3D cell segmentation](https://link.springer.com/article/10.1186/1751-0473-8-16).<br>
26.[A deep convolutional neural network for classification of red blood cells in sickle cell anemia](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005746).<br>
27.[A Manual Segmentation Tool for Three-Dimensional Neuron Datasets](https://www.frontiersin.org/articles/10.3389/fninf.2017.00036/full).<br>
28.[The Allen Cell Structure Segmenter: a new open source toolkit for segmenting 3D intracellular structures in fluorescence microscopy images](https://www.biorxiv.org/content/10.1101/491035v1.abstract).<br>
29.[Deep learning guided image-based droplet sorting for on-demand selection and analysis of single cells and 3D cell cultures](https://pubs.rsc.org/ko/content/articlelanding/2020/lc/d0lc00055h/unauth#!divAbstract).<br>
30.[Cellpose: a generalist algorithm for cellular segmentation](https://www.nature.com/articles/s41592-020-01018-x).<br>
31.[Deep learning for cell image segmentation and ranking](https://www.sciencedirect.com/science/article/abs/pii/S089561111830048X?casa_token=MoxaBeyOZ4kAAAAA:zq6Ytq-LT_djzcs6OT_-xp67U1JnNkD5fBJho_MKkHdvIfSoKli8Uh1h9lUGQmX-5ZQgnekTwQ4).<br>
32.[Cell segmentation methods for label-free contrast microscopy: review and comprehensive comparison](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2880-8).<br>
33.[Split and merge watershed: A two-step method for cell segmentation in fluorescence microscopy images](https://www.sciencedirect.com/science/article/abs/pii/S1746809419301491?casa_token=I1PcXkLroL4AAAAA:cdjC-gaAP9XTpUBtG0ixS39dUlNEGHTOJqYid320RMEhbqiMIrIkvxNbre9o6y1vwmG9hz6TP3A).<br>
34.[Deep learning for cellular image analysis](https://www.nature.com/articles/s41592-019-0403-1).<br>
35.[CellProfiler 3.0: Next-generation image processing for biology](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005970).<br>
36.[Data-analysis strategies for image-based cell profiling](https://www.nature.com/articles/nmeth.4397).<br>
37.[Keras R-CNN: library for cell detection in biological images using deep neural networks](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03635-x).<br>
38.[Oufti: an integrated software package for high‐accuracy, high‐throughput quantitative microscopy analysis](https://onlinelibrary.wiley.com/doi/full/10.1111/mmi.13264).<br>
39.[Deep Learning Automates the Quantitative Analysis of Individual Cells in Live-Cell Imaging Experiments](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005177).<br>
40.[Label‐Free Identification of White Blood Cells Using Machine Learning](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23794).<br>
41.[Label-free assessment of red blood cell storage lesions by deep learning](https://www.biorxiv.org/content/10.1101/256180v2.abstract).<br>
42.[OpenSegSPIM: a user-friendly segmentation tool for SPIM data](https://academic.oup.com/bioinformatics/article/32/13/2075/1743029?login=true).<br>
43.[A practical guide to intelligent image-activated cell sorting](https://www.nature.com/articles/s41596-019-0183-1).<br>
44.[Lineage Tracing: Computational Reconstruction Goes Beyond the Limit of Imaging](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6399003/).<br>
45.[Quanti.us: a tool for rapid, flexible, crowd-based annotation of images](https://www.nature.com/articles/s41592-018-0069-0).<br>
46.[ilastik: interactive machine learning for (bio)image analysis](https://www.nature.com/articles/s41592-019-0582-9).<br>
47.[Quantitative Digital Microscopy with Deep Learning](https://arxiv.org/abs/2010.08260).<br>
48.[U-Net: deep learning for cell counting, detection, and morphometry](https://www.nature.com/articles/s41592-018-0261-2).<br>
49.[A workflow to process 3D+time microscopy images of developing organisms and reconstruct their cell lineage](https://www.nature.com/articles/ncomms9674/).<br>
50.[Multi-view light-sheet imaging and tracking with the MaMuT software reveals the cell lineage of a direct developing arthropod limb](https://elifesciences.org/articles/34410).<br>
51.[Cell segmentation in 3D confocal images using supervoxel merge-forests with CNN-based hypothesis selection](https://ieeexplore.ieee.org/abstract/document/8363598).<br>
52.[Image analysis of neural stem cell division patterns in the zebrafish brain](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23260).<br>
53.[Three-dimensional microscopy and image analysis methodology for mapping and quantification of nuclear positions in tissues with approximate cylindrical geometry](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2017.0332).<br>
54.[3D image segmentation supported by a point cloud](https://www.aimsciences.org/article/doi/10.3934/dcdss.2020351?viewType=html).<br>
55.[Towards Automatic Embryo Staging in 3D+t Microscopy Images Using Convolutional Neural Networks and PointNets](https://link.springer.com/chapter/10.1007/978-3-030-59520-3_16).<br>
56.[Software tools for single-cell tracking and quantification of cellular and molecular properties](https://www.nature.com/articles/nbt.3626?report=reader).<br>
57.[Cell tracking using deep neural networks with multi-task learning](https://www.sciencedirect.com/science/article/abs/pii/S0262885616302001?casa_token=-u5HyqhI_mwAAAAA:tSZRu2U6J-SewSmLR7erIqpX56Q3_uaBvg0L8E0pXD5g0J40lqWIiTg9fQpucOQHHBC21L0RDh4#!).<br>
58.[Fluorescent Nanodiamond Applications for Cellular Process Sensing and Cell Tracking](https://www.mdpi.com/2072-666X/9/5/247).<br>
59.[Quantitative label-free single cell tracking in 3D biomimetic matrices](https://www.nature.com/articles/s41598-017-14458-x).<br>
60.[A probabilistic approach to joint cell tracking and segmentation in high-throughput microscopy videos](https://www.sciencedirect.com/science/article/abs/pii/S1361841518302081?casa_token=y5awB8rHI7sAAAAA:JFU3C0-XoWlCgyiBhYWYX1uziwqUirQAJnXes8WUp5PX7Zw11GX00nzxPTQuciZCHmKU7c2NUFE).<br>
61.[Live-cell time-lapse imaging and single-cell tracking of in vitro cultured neural stem cells – Tools for analyzing dynamics of cell cycle, migration, and lineage selection](https://www.sciencedirect.com/science/article/abs/pii/S1046202317301172?casa_token=gbBYZJhicyQAAAAA:zFbeDsVz0DT0XJPQfSR9RCwlIhQgRxz34cl7dckWcCxWq6vGfaDhZsU0Sm5VBQzRgKAhx2NNbzE).<br>
62.[Weakly-Supervised Cell Tracking via Backward-and-Forward Propagation](https://link.springer.com/chapter/10.1007/978-3-030-58610-2_7).<br>
63.[Computerized cell tracking: Current methods, tools and challenges](https://www.sciencedirect.com/science/article/pii/S2468502X20300711).<br>
64.[Long term intravital single cell tracking under multiphoton microscopy](https://www.sciencedirect.com/science/article/abs/pii/S0165027020304659?casa_token=3yMUGXPsS2cAAAAA:x4L5oVRbOLXpmtJRtvwbs9i8rlkEU8s-m9-adzFgPZv5WdZJMhzwSNpVqwOoUQttSTNvOte-K88).<br>
65.[A New Approach for Cell Detection and Tracking](https://ieeexplore.ieee.org/abstract/document/8769977).<br>
66.[Joint cell segmentation and tracking using cell proposals](https://ieeexplore.ieee.org/abstract/document/7493415).<br>
67.[Cell Tracking with Deep Learning and the Viterbi Algorithm](https://ieeexplore.ieee.org/abstract/document/8481231).<br>
68.[A Benchmark for Epithelial Cell Tracking](https://openaccess.thecvf.com/content_eccv_2018_workshops/w33/html/Funke_A_Benchmark_for_Epithelial_Cell_Tracking_ECCVW_2018_paper.html).<br>
69.[Automated Cell Tracking Using Motion Prediction-Based Matching and Event Handling](https://ieeexplore.ieee.org/abstract/document/8490710).<br>
70.[Deep Reinforcement Learning for Data Association in Cell Tracking](https://www.frontiersin.org/articles/10.3389/fbioe.2020.00298/full).<br>
71.[Automated cell tracking using StarDist and TrackMate](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7670479/).<br>
72.[TrackPad: Software for semi-automated single-cell tracking and lineage annotation](https://www.sciencedirect.com/science/article/pii/S2352711019302390).<br>
73.[Light‐sheet microscopy‐based 3D single‐cell tracking reveals a correlation between cell cycle and the start of endoderm cell internalization in early zebrafish development](https://onlinelibrary.wiley.com/doi/abs/10.1111/dgd.12695?casa_token=OAoNtuJd_eoAAAAA:Z70ZBteYliyzmeke7sgGazPg0-meA3tFuqaRYMriPgJV8DUc2r9SQpA_nASWuX6dyCFkGooj1Hq2JnQ).<br>
74.[Cell segmentation and tracking using CNN-based distance predictions and a graph-based matching strategy](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0243219).<br>
75.[Segmenting and tracking cell instances with cosine embeddings and recurrent hourglass networks](https://www.sciencedirect.com/science/article/pii/S136184151930057X).<br>
76.[An Automated Cell Tracking Approach with Multi-Bernoulli Filtering and Ant Colony Labor Division](https://ieeexplore.ieee.org/abstract/document/8907462).<br>
77.[Accurate cell tracking and lineage construction in live-cell imaging experiments with deep learning](https://www.biorxiv.org/content/10.1101/803205v1.abstract).<br>
78.[Cell Tracking Profiler – a user-driven analysis framework for evaluating 4D live-cell imaging data](https://jcs.biologists.org/content/133/22/jcs241422.abstract).<br>
79.[Online Neural Cell Tracking Using Blob-Seed Segmentation and Optical Flow](https://openaccess.thecvf.com/content_CVPRW_2019/html/CVMI/Yi_Online_Neural_Cell_Tracking_Using_Blob-Seed_Segmentation_and_Optical_Flow_CVPRW_2019_paper.html).<br>
80.[Real-time tracking of stem cell viability, proliferation, and differentiation with autonomous bioluminescence imaging](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-020-00815-2).<br>
81.[Joint Multi-frame Detection and Segmentation for Multi-cell Tracking](https://link.springer.com/chapter/10.1007/978-3-030-34110-7_36).<br>
82.[Automated Imaging, Tracking, and Analytics Pipeline for Differentiating Environmental Effects on Root Meristematic Cell Division](https://www.frontiersin.org/articles/10.3389/fpls.2019.01487/full).<br>
83.[In Vivo Cell Tracking Using Two-Photon Microscopy](https://link.springer.com/protocol/10.1007/978-1-4939-3721-9_11).<br>
84.[Cell Tracking Across Noisy Image Sequences Via Faster R-CNN and Dynamic Local Graph Matching](https://ieeexplore.ieee.org/abstract/document/8621192).<br>
85.[Tracking-Assisted Segmentation of Biological Cells](https://arxiv.org/abs/1910.08735).<br>
86.[NucliTrack: an integrated nuclei tracking application](https://academic.oup.com/bioinformatics/article/33/20/3320/3871473?login=true).<br>
87.[Cell tracking in time-lapse microscopy image techniques](https://books.google.com/books?hl=zh-CN&lr=&id=Lk8MEAAAQBAJ&oi=fnd&pg=PA101&dq=Cell+Tracking+&ots=eth9jY_qh3&sig=Taf_W-_5z4Xl0FfXk5hz7zgpdqA#v=onepage&q=Cell%20Tracking&f=false).<br>
88.[Commentary: Live Imaging Followed by Single Cell Tracking to Monitor the Cell Biology and Lineage Progression of Multiple Neural Populations](https://www.researchgate.net/profile/Felipe_Ortega/publication/327401180_Commentary_Live_Imaging_Followed_by_Single_Cell_Tracking_to_Monitor_the_Cell_Biology_and_Lineage_Progression_of_Multiple_Neural_Populations/links/5cc829b0a6fdcc1d49b9de59/Commentary-Live-Imaging-Followed-by-Single-Cell-Tracking-to-Monitor-the-Cell-Biology-and-Lineage-Progression-of-Multiple-Neural-Populations.pdf).<br>
89.[High-throughput detection and tracking of cells and intracellular spots in mother machine experiments](https://www.nature.com/articles/s41596-019-0216-9).<br>
90.[A Machine Learning Segmentation for Cell Tracking and Analysis](https://www.ideals.illinois.edu/handle/2142/104061).<br>
91.[A Cell Segmentation/Tracking Tool Based on Machine Learning](https://link.springer.com/protocol/10.1007/978-1-4939-9686-5_19).<br>
92.[A Robust and Fast Framework for Cell Tracking](https://www.ingentaconnect.com/content/asp/jmihi/2018/00000008/00000005/art00010).<br>
93.[Cell tracking for cell image analysis](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10251/102510P/Cell-tracking-for-cell-image-analysis/10.1117/12.2275029.short?SSO=1).<br>
94.[Fluorescence based segmentation and cell tracking software for mother-machine experiments](https://ieeexplore.ieee.org/abstract/document/8730275).<br>
95.[Semi-supervised learning for cell tracking in microscopy images](https://ieeexplore.ieee.org/abstract/document/8363727).<br>
96.[Faster Mean-shift: GPU-accelerated Embedding-clustering for Cell Segmentation and Tracking](https://arxiv.org/abs/2007.14283).<br>
97.[SuperSegger: robust image segmentation, analysis and lineage tracking of bacterial cells](https://onlinelibrary.wiley.com/doi/full/10.1111/mmi.13486).<br>
98.[A Bayesian Approach for Joint Cell Tracking and Segmentation in Microscopy Videos](https://public.celltrackingchallenge.net/participants/BGU-IL%20(1).pdf).<br>
99.[In Vivo Cell Tracking Techniques for Applications in Central Nervous System Disorders](https://link.springer.com/chapter/10.1007/978-4-431-56059-3_8).<br>
100.[Cell Population Tracking in a Honeycomb Structure Using an IMM Filter Based 3D Local Graph Matching Model](https://ieeexplore.ieee.org/abstract/document/8060531).<br>
101.[In vivo single-RNA tracking shows that most tRNA diffuses freely in live bacteria](https://academic.oup.com/nar/article/45/2/926/2953301?login=true).<br>
102.[Particle-Cell Detecting and Tracking in Live-Cell Time-Lapse Images](https://ieeexplore.ieee.org/abstract/document/8121795).<br>
103.[Long-Term Cell Fate Tracking of Individual Renal Cells Using Serial Intravital Microscopy](https://link.springer.com/protocol/10.1007/7651_2019_232).<br>
104.[Lineage Tracking for Probing Heritable Phenotypes at Single-Cell Resolution](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0152395).<br>
105.[DeepSeed Local Graph Matching for Densely Packed Cells Tracking](https://ieeexplore.ieee.org/abstract/document/8809785).<br>
106.[Automated tracking of label-free cells with enhanced recognition of whole tracks](https://www.nature.com/articles/s41598-019-39725-x).<br>
107.[A fully-automated, robust, and versatile algorithm for long-term budding yeast segmentation and tracking](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0206395).<br>
108.[Segmenting and Tracking Multiple Dividing Targets Using ilastik](https://link.springer.com/chapter/10.1007/978-3-319-28549-8_8).<br>
109.[Reconstruction of cell lineages and behaviors underlying arthropod limb outgrowth with multi-view light-sheet imaging and tracking](https://www.biorxiv.org/content/10.1101/112623v1.abstract).<br>
110.[Optical cell tracking analysis using a straight-forward approach to minimize processing time for high frame rate data](https://aip.scitation.org/doi/abs/10.1063/1.4943420).<br>
111.[Cell Tracking using Convolutional Neural Networks](http://cs231n.stanford.edu/reports/2016/pdfs/326_Report.pdf).<br>
112.[On-line Tracking of Cells and Their Lineage from Time Lapse Video Data](https://ieeexplore.ieee.org/abstract/document/8570546).<br>
113.[Tracking and Imaging of Transplanted Stem Cells in Animals](https://link.springer.com/protocol/10.1007/7651_2019_275).<br>
114.[Deeply-supervised density regression for automatic cell counting in microscopy images](https://www.sciencedirect.com/science/article/abs/pii/S1361841520302565).<br>
115.[CellCycleGAN: Spatiotemporal Microscopy Image Synthesis of Cell Populations using Statistical Shape Models and Conditional GANs](https://arxiv.org/abs/2010.12011).<br>
116.[SplineDist: Automated Cell Segmentation with Spline Curves](https://www.biorxiv.org/content/10.1101/2020.10.27.357640v1.abstract).<br>
117.[A bird’s-eye view of deep learning in bioimage analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7494605/).<br>
118.[A Hybrid Approach for Segmentation and Tracking of Myxococcus Xanthus Swarms](https://ieeexplore.ieee.org/abstract/document/7444158).<br>
119.[Interactive Tracking of Cells in Microscopy Image Sequences](https://cs-web.bu.edu/faculty/betke/papers/Gentil-etal-IMIC-MICCAI-2016.pdf).<br>
120.[Label free, quantitative single-cell fate tracking of time-lapse movies](https://www.sciencedirect.com/science/article/pii/S2215016119302791).<br>
121.[Joint segmenting and tracking densely packed cells using dynamic-GVF based snakes](https://ieeexplore.ieee.org/abstract/document/8368696).<br>
122.[Microscopic imaging of living cells, automatic tracking and the description of the kinetics of the cells for imagemining](https://www.researchgate.net/profile/Petra_Perner/publication/313228574_Microscopic_imaging_of_living_cells_automatic_tracking_and_the_description_of_the_kinetics_of_the_cells_for_image-_mining/links/5a2f67040f7e9bfe81703764/Microscopic-imaging-of-living-cells-automatic-tracking-and-the-description-of-the-kinetics-of-the-cells-for-image-mining.pdf).<br>
123.[Cell Lineage Tracking Based on Labeled Random Finite Set Filtering](https://ieeexplore.ieee.org/abstract/document/8570327).<br>
124.[Convolutional Features-Based CRF Graph Matching for Tracking of Densely Packed Cells](https://ieeexplore.ieee.org/abstract/document/8545249).<br>
125.[Segmentation and tracking of Pseudomonas aeruginosa for cell dynamics analysis in time-lapse images](https://ieeexplore.ieee.org/abstract/document/7493426).<br>
126.[Live-cell 3D single-molecule tracking reveals how NuRD modulates enhancer dynamics](https://www.biorxiv.org/content/10.1101/2020.04.03.003178v1.abstract).<br>
127.[Automated tracking approach with ant colonies for different cell population density distribution](https://link.springer.com/article/10.1007/s00500-016-2048-7).<br>
128.[Automated cell lineage tracing in Caenorhabditis elegans](https://www.pnas.org/content/103/8/2707).<br>
129.[Automated cell tracking identifies mechanically oriented cell divisions during Drosophila axis elongation](https://dev.biologists.org/content/144/7/1350).<br>
130.[Real-Time Three-Dimensional Cell Segmentation in Large-Scale Microscopy Data of Developing Embryos](https://www.cell.com/developmental-cell/pdfExtended/S1534-5807(15)00837-0).<br>
131.[Fast, accurate reconstruction of cell lineages from large-scale fluorescence microscopy data](https://www.nature.com/articles/nmeth.3036/).<br>
132.[Interactive exemplar-based segmentation toolkit for biomedical image analysis](https://ieeexplore.ieee.org/abstract/document/7163842).<br>
133.[Emerging Imaging and Genomic Tools for Developmental Systems Biology Author links open overlay panel](https://www.sciencedirect.com/science/article/pii/S1534580716300715).<br>
134.[Cousins at work: How combining medical with optical imaging enhances in vivo cell tracking](https://www.sciencedirect.com/science/article/pii/S135727251830150X).<br>
135.[Robust Nucleus/Cell Detection and Segmentation in Digital Pathology and Microscopy Images: A Comprehensive Review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5233461/).<br>
136.[EmbryoMiner: A new framework for interactive knowledge discovery in large-scale cell tracking data of developing embryos](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5929571/).<br>
137.[Multi-scale imaging and analysis identify pan-embryo cell dynamics of germlayer formation in zebrafish](https://www.nature.com/articles/s41467-019-13625-0).<br>
138.[Shape-aware Segmentation of Biomedical Images using Deep Learning](https://is.muni.cz/th/wzv56/filip_lux_rigo.pdf).<br>
139.[Cellular and molecular imaging for stem cell tracking in neurological diseases](https://svn.bmj.com/content/early/2020/10/29/svn-2020-000408).<br>
140.[Robust single neuron tracking of calcium imaging in behaving Hydra](https://www.biorxiv.org/content/10.1101/2020.06.22.165696v1.abstract).<br>
141.[Two-Photon Image Tracking of Neural Stem Cells via Iridium Complexes Encapsulated in Polymeric Nanospheres](https://pubs.acs.org/doi/abs/10.1021/acsbiomaterials.8b01231).<br>
142.[Quantitative high-speed imaging of entire developing embryos with simultaneous multiview light-sheet microscopy](https://www.nature.com/articles/nmeth.2062).<br>
143.[Nucleus segmentation across imaging experiments: the 2018 Data Science Bowl](https://www.nature.com/articles/s41592-019-0612-7).<br>
144.[nucleAIzer: A Parameter-free Deep Learning Framework for Nucleus Segmentation Using Image Style Transfer](https://www.sciencedirect.com/science/article/pii/S2405471220301174).<br>
145.[CP-CHARM: segmentation-free image classification made accessible](https://link.springer.com/article/10.1186/s12859-016-0895-y).<br>
146.[DoGNet: A deep architecture for synapse detection in multiplexed fluorescence images](https://journals.plos.org/ploscompbiol/article?rev=2&id=10.1371/journal.pcbi.1007012).<br>
147.[Inpainting Networks Learn to Separate Cells in Microscopy Images](http://129.206.117.249/sites/default/files/publications/files/852479027/wolf_20_inpainting-min.pdf).<br>
148.[Analyzing Image Segmentation for Connectomics](https://www.frontiersin.org/articles/10.3389/fncir.2018.00102/full).<br>
149.[The candidate multi-cut for cell segmentation](https://ieeexplore.ieee.org/abstract/document/8363658).<br>
150.[Large Scale Image Segmentation with Structured Loss Based Deep Learning for Connectome Reconstruction](https://ieeexplore.ieee.org/abstract/document/8364622).<br>
151.[An objective comparison of cell-tracking algorithms](https://www.nature.com/articles/nmeth.4473).<br>
152.[3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation](https://arxiv.org/abs/1606.06650).<br>
153.[DoGNet: A deep architecture for synapse detection in multiplexed fluorescence images](https://journals.plos.org/ploscompbiol/article?rev=2&id=10.1371/journal.pcbi.1007012).<br>
154.[Challenges in long-term imaging and quantification of single-cell dynamics](https://www.nature.com/articles/nbt.3713).<br>
155.[Cell Tracking via Proposal Generation and Selection](https://arxiv.org/abs/1705.03386).<br>
156.[Biologically constrained optimization based cell membrane segmentation in C. elegans embryos](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1717-6).<br>
157.[LimeSeg: a coarse-grained lipid membrane simulation for 3D image segmentation](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2471-0).<br>
158.[Accurate 3D Cell Segmentation Using Deep Features and CRF Refinement](https://ieeexplore.ieee.org/abstract/document/8803095).<br>
159.[Robust detection and segmentation of cell nuclei in biomedical images based on a computational topology framework](https://pubmed.ncbi.nlm.nih.gov/28314191/).<br>
160.[A Topological Loss Function for Deep-Learning based Image Segmentation using Persistent Homology](https://pubmed.ncbi.nlm.nih.gov/32886606/).<br>
161.[Recent computational methods for white blood cell nuclei segmentation: A comparative study](https://pubmed.ncbi.nlm.nih.gov/31046984/).<br>
162.[Automatic three-dimensional segmentation of mouse embryonic stem cell nuclei by utilising multiple channels of confocal fluorescence images](https://pubmed.ncbi.nlm.nih.gov/32720710/).<br>
163.[3D Segmentation,Visualization and Quantitative Analysis of Differentiation Activity for Mouse Embryonic Stem Cells using Time-Lapse Fluorescence Microscopy Images](https://ieeexplore.ieee.org/document/8251279).<br>
164.[DeepCell Kiosk: scaling deep learning–enabled cellular image analysis with Kubernetes](https://www.nature.com/articles/s41592-020-01023-0).<br>
165.[nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation](https://www.nature.com/articles/s41592-020-01008-z).<br>
166.[Maximizing Kolmogorov Complexity for accurate and robust bright field cell segmentation](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-15-32).<br>
167.[Automated Segmentation of Fluorescence Microscopy Images for 3D Cell Detection in human-derived Cardiospheres](https://www.nature.com/articles/s41598-019-43137-2).<br>
168.[Automated cell boundary and 3D nuclear segmentation of cells in suspension](https://www.nature.com/articles/s41598-019-46689-5).<br>
169.[An objective comparison of cell-tracking algorithms](https://www.nature.com/articles/nmeth.4473).<br>
170.[Accurate cell segmentation in microscopy images using membrane patterns](https://academic.oup.com/bioinformatics/article/30/18/2644/2475348).<br>
171.[Applications, promises, and pitfalls of deep learning for fluorescence image reconstruction.](https://www.nature.com/articles/s41592-019-0458-z).<br>




useful videos 1[DigitalSreeni](https://www.youtube.com/channel/UC34rW-HtPJulxr5wp2Xa04w/videos).<br>
collection-[Deep learning in microscopy](https://www.nature.com/collections/cfcdjceech).<br>
forum-[image.sc](https://forum.image.sc/tags/c/image-analysis/6/segmentation)
library-[cell image library](cellimagelibrary.org).<br>
## single-cell_omics
1.[Lineage tracing meets single-cell omics: opportunities and challenges](https://www.nature.com/articles/s41576-020-0223-2).<br>
2.[Integrative single-cell analysis](https://www.nature.com/articles/s41576-019-0093-7).<br>
3.[CellTagging: combinatorial indexing to simultaneously map lineage and identity at single-cell resolution](https://www.nature.com/articles/s41596-019-0247-2).<br>
4.[Unravelling cellular relationships during development and regeneration using genetic lineage tracing](https://www.nature.com/articles/s41580-019-0186-3).<br>
5.[Single cell RNA-sequencing reveals cellular heterogeneity and trajectories of lineage specification during murine embryonic limb development](https://www.sciencedirect.com/science/article/pii/S0945053X19304020?casa_token=9QOyoYbHgrAAAAAA:9Pz8k5IefrLrVdNa7WZ9onIVk3XtqVkcpv8EuVO8-LgTlbnNHi__zc1UUVbHVQvl7VIq1bCcF0E).<br>
6.[Single-Cell Analysis of Regional Differences in Adult V-SVZ Neural Stem Cell Lineages](https://www.sciencedirect.com/science/article/pii/S2211124718319740).<br>
7.[Dissecting Cell Lineage Specification and Sex Fate Determination in Gonadal Somatic Cells Using Single-Cell Transcriptomics](https://www.sciencedirect.com/science/article/pii/S2211124719302487).<br>
8.[DNA barcodes evolve for high-resolution cell lineage tracing](https://www.sciencedirect.com/science/article/abs/pii/S1367593119300274?casa_token=HxmlxW_70z4AAAAA:q_P8SiLgQyP3RAqDgWuiBokyMoy1fCe04lLqSiO_k7Vv1j1EoHKNmsYkezh3yjn2a3XdreHpa78).<br>
9.[Recording development with single cell dynamic lineage tracing](https://dev.biologists.org/content/146/12/dev169730.abstract).<br>
10.[CALISTA: Clustering and Lineage Inference in Single-Cell Transcriptional Analysis](https://www.biorxiv.org/content/10.1101/257550v3.abstract).<br>
11.[Single-Cell Multi-omic Integration Compares and Contrasts Features of Brain Cell Identity](https://www.sciencedirect.com/science/article/pii/S0092867419305045#!).<br>
12.[The emergence of transcriptional identity in somatosensory neurons](https://www.nature.com/articles/s41586-019-1900-1).<br>
13.[Single-cell analysis of olfactory neurogenesis and differentiation in adult humans](https://www.nature.com/articles/s41593-020-0587-9).<br>
14.[Next-Generation Lineage Tracing and Fate Mapping to Interrogate Development](https://www.sciencedirect.com/science/article/abs/pii/S1534580720308418).<br>
15.[Robust lineage reconstruction from high-dimensional single-cell data](https://academic.oup.com/nar/article/44/14/e122/2468175?login=true).<br>
16.[Cell lineage inference from SNP and scRNA-Seq data](https://academic.oup.com/nar/article/47/10/e56/5367412?login=true).<br>
17.[Analysis of Cell Fate from Single-Cell Gene Expression Profiles in C. elegans](https://www.sciencedirect.com/science/article/pii/S0092867409011180).<br>
18.[A multiscale model of early cell lineage specification including cell division](https://www.nature.com/articles/s41540-017-0017-0).<br>
19.[Single-cell lineage analysis reveals extensive multimodal transcriptional control during directed beta-cell differentiation](https://www.nature.com/articles/s42255-020-00314-2).<br>
20.[Single-Cell Transcriptomics Meets Lineage Tracing](https://www.sciencedirect.com/science/article/pii/S1934590918301760).<br>
21.[Statistical Inference in Cell Lineage Trees](https://www.biorxiv.org/content/10.1101/267450v1.full).<br>
22.[Automated deep lineage tree analysis using a Bayesian single cell tracking approach](https://www.biorxiv.org/content/10.1101/2020.09.10.276980v1.abstract).<br>
23.[Single-cell mapping of gene expression landscapes and lineage in the zebrafish embryo](https://science.sciencemag.org/content/360/6392/981.abstract).<br>
24.[Scrublet: Computational Identification of Cell Doublets in Single-Cell Transcriptomic Data](https://www.sciencedirect.com/science/article/pii/S2405471218304745).<br>
25.[Lineage tracing on transcriptional landscapes links state to fate during differentiation](https://science.sciencemag.org/content/367/6479/eaaw3381.abstract).<br>
26.[A Unified Framework for Lineage Tracing and Trajectory Inference](https://www.biorxiv.org/content/10.1101/2020.07.31.231621v1.abstract).<br>
27.[CellRank for directed single-cell fate mapping](https://www.biorxiv.org/content/10.1101/2020.10.19.345983v1.abstract).<br>
28.[Optimal-Transport Analysis of Single-Cell Gene Expression Identifies Developmental Trajectories in Reprogramming](https://www.cell.com/cell/fulltext/S0092-8674(19)30039-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS009286741930039X%3Fshowall%3Dtrue#%20).<br>
29.[Building a lineage from single cells: genetic techniques for cell lineage tracking](https://www.nature.com/articles/nrg.2016.159).<br>
30.[GCNG: graph convolutional networks for inferring gene interaction from spatial transcriptomics data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02214-w).<br>
31.[Deep learning for inferring gene relationships from single-cell expression data](https://www.pnas.org/content/116/52/27151.short).<br>
32.[A polynomial based model for cell fate prediction in human diseases](https://bmcsystbiol.biomedcentral.com/articles/10.1186/s12918-017-0502-5).<br>
33.[eesawPred: A Web Application for Predicting Cell-fate Determinants in Cell Differentiation](https://www.nature.com/articles/s41598-018-31688-9).<br>
34.
## cell_lineage
1.[Mechanisms of 3D cell migration](https://www.nature.com/articles/s41580-019-0172-9).<br>
2.[Single-cell analysis uncovers convergence of cell identities during axolotl limb regeneration](https://science.sciencemag.org/content/362/6413/eaaq0681.abstract).<br>
3.[Semi-supervised machine learning facilitates cell colocalization and tracking in intravital microscopy](https://www.biorxiv.org/content/10.1101/829838v1.abstract).<br>
4.[Cell Tracking using Convolutional Neural Networks](http://cs231n.stanford.edu/reports/2016/pdfs/326_Report.pdf).<br
5.[In Toto Imaging and Reconstruction of Post-Implantation Mouse Development at the Single-Cell Level](https://www.sciencedirect.com/science/article/pii/S0092867418312431).<br>
6.[Long-term self-renewing stem cells in the adult mouse hippocampus identified by intravital imaging](https://www.nature.com/articles/s41593-020-00759-4).<br>
7.[MARS: discovering novel cell types across heterogeneous single-cell experiments](https://www.nature.com/articles/s41592-020-00979-3).<br>






lecture_seminar
[MIA Meeting](https://www.youtube.com/watch?v=_jSo7oeqT0c&list=PLlMMtlgw6qNjROoMNTBQjAcdx53kV50cS)
