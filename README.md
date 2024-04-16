# Awesome-Medical-Dataset [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🔥🔥🔥 Medical Dataset is very important for Medical Image Analysis. In this repository, we provide an up-to-date list of medical datasets.

## Table of Content

---

:book: **Contents**

- [Imaging](#Imaging)
  - [Whole Body (5)](#whole-body)
  - [Head and Neck (30)](#head-and-neck)
  - [Chest (24)](#chest)
  - [Abdomen (27)](#abdomen)
  - [Heart (6)](#heart)
  - [Bones (4)](#bones)
  - [Endoscopy (19)](#endoscopy)
  - [Retina (22)](#retina)
  - [Skin (6)](#skin)
  - [Microscopic imaging (22)](#microscopic-imaging)
- [Imaging and Text (22)](#Image-text-dataset)
- [Text (13)](#Text-dataset)

---

## Medical Image Datasets

### Whole Body

| Dataset                                                   | Description                                                         | Official Website                                                                                                    | Download Link                                                                       | Paper                                                                  | Release Date  | Challenge          |
|:----------------------------------------------------------|:--------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------|:-----------------------------------------------------------------------|:--------------|:-------------------|
| [CT-ORG](./resources/CT-ORG.md)                           | 3D CT, 140 Cases, 6 Categories of Organ Segmentation.               | [Github](https://github.com/bbrister/ctOrganSegmentation)                                                           | [TCIA](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=61080890) | [Scientific Data](https://www.nature.com/articles/s41597-020-00715-8)  | 2020          | -                  |
| [AutoPET](./resources/Auto-PET.md)                        | 3D PET-CT, 1214 Cases, 1 Category of Whole Body Tumor Segmentation. | [Grand Challenge](https://autopet.grand-challenge.org/), [Grand Challenge](https://autopet-ii.grand-challenge.org/) | [TCIA](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=93258287) | [Scientific Data](https://www.nature.com/articles/s41597-022-01718-3)  | 2022-04       | MICCAI'2022 & 2023 | 
| [TotalSegmentator](./resources/TotalSegmentator.md)       | 3D CT, 1204 Cases, 104 Categories of Whole Body Organ Segmentation. | [Github](https://github.com/wasserth/TotalSegmentator)                                                              | [Zenodo](https://zenodo.org/record/6802614)                                         | [RSNA](https://pubs.rsna.org/doi/10.1148/ryai.230024)                  | 2022-07       | -                  |
| [TotalSegmentator V2](./resources/TotalSegmentator_v2.md) | 3D CT, 1228 Cases, 117 Categories of Whole Body Organ Segmentation. | [Github](https://github.com/wasserth/TotalSegmentator)                                                              | [Zenodo](https://doi.org/10.5281/zenodo.6802613)                                    | [RSNA](https://pubs.rsna.org/doi/10.1148/ryai.230024)                  | 2023          | -                  |
| [ULS](./resources/ULS.md)                                 | 3D CT, 38842 Cases, 1 Category of Whole Body Tumor Segmentation.    | [Grand Challenge](https://uls23.grand-challenge.org/)                                                               | -                                                                                   | -                                                                      | 2023-10       | -                  |

### Head and Neck

| Dataset                                               | Description                                                                                                       | Official Website                                                                               | Download Link                                                                              | Paper                                                                                                                                                                      | Release Date | Challenge                      |
|:------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [L2R-OASIS](./resources/L2R-OASIS.md)                 | 3D MRI, 416 Cases, 35 Categories of Brain Segmentation and Registration                                           | [Grand Challenge](https://learn2reg.grand-challenge.org/Datasets/)                             | [Project Homepage](https://www.oasis-brains.org/#data)                                     | [Cognitive Neuroscience](https://dash.harvard.edu/bitstream/handle/1/33896768/Buckner_OpenAccess.pdf?sequence=2)                                                           | 2007         | -                              |
| [DDTI](./resources/DDTI.md)                           | 2D Ultrasound, 637 Cases, 1 Category of Thyroid Nodule Segmentation                                               | [Project Homepage](http://cimalab.intec.co/applications/thyroid/)                              | [Project Homepage](http://cimalab.intec.co/applications/thyroid/)                          | [SPIE'2015](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9287/92870W/An-open-access-thyroid-ultrasound-image-database/10.1117/12.2073532.short?SSO=1) | 2015-01      | -                              |
| [Ultrasound Nerve Segmentation](./resources/UNS.md)   | 2D Ultrasound, 11143 Cases, 1 Category of Cervical Nerve Segmentation                                             | [Kaggle](https://kaggle.com/competitions/ultrasound-nerve-segmentation)                        | [Kaggle](https://www.kaggle.com/c/ultrasound-nerve-segmentation/data)                      | -                                                                                                                                                                          | 2016-05      | Kaggle                         |
| [BraTS-TCGA-LGG](./resources/BraTS-TCGA-LGG.md)       | 3D MRI, 65 Cases, 3 Categories of Low Grade Glioma (LGG) Segmentation                                             | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-lgg/)                   | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-lgg/)               | [Scientific Data](https://www.nature.com/articles/sdata2017117)                                                                                                            | 2017         | BRATS2015                      |
| [BraTS-TCGA-GBM](./resources/BraTS-TCGA-GBM.md)       | 3D MRI, 102 Cases, 3 Categories of Glioblastoma Multiforme (GBM) Segmentation                                     | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-gbm/)                   | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-gbm/)               | [Scientific Data](https://www.nature.com/articles/sdata2017117)                                                                                                            | 2017         | BRATS2015                      |
| [PDDCA](./resources/PDDCA.md)                         | 3D CT, 48 Cases, 9 Categories of Head and Neck Organs Segmentation                                                | [ImagEngLab](https://www.imagenglab.com/newsite/pddca/)                                        | [ImagEngLab](https://www.imagenglab.com/newsite/pddca/)                                    | [Medical Physics](https://aapm.onlinelibrary.wiley.com/doi/10.1002/mp.12197)                                                                                               | 2017-03      | -                              |
| [iSeg](./resources/iSeg.md)                           | 3D MRI, 13 Cases, 3 Categories of Brain Tissue Segmentation                                                       | [Project Homepage](https://iseg2019.web.unc.edu/)                                              | [Project Homepage](https://iseg2019.web.unc.edu/)                                          | [TMI'2021](https://doi.org/10.1109/TMI.2021.3055428)                                                                                                                       | 2019         | MICCAI'2017 & 2019             |
| [MSD Hippocampus](./resources/MSD_Hippocampus.md)     | 3D MRI, 394 Cases, 2 Categories of Hippocampus Segmentation                                                       | [MSD](http://medicaldecathlon.com/)                                                            | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2)   | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                                                                                                 | 2019-02      | Medical Segmentation Decathlon |
| [WMH](./resources/WMH.md)                             | 3D MRI, 170 Cases, 1 Category of White Matter Hyperintensity Segmentation                                         | [Project Homepage](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/AECRSD)        | [Project Homepage](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/AECRSD)    | [TMI'2019](https://ieeexplore.ieee.org/document/8669968)                                                                                                                   | 2019-11      | -                              |
| [TN-SCUI2020](./resources/TN-SCUI2020.md)             | 2D Ultrasound, 4554 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Grand Challenge](https://tn-scui2020.grand-challenge.org/Home/)                               | -                                                                                          | [Zenodo](https://zenodo.org/records/3715942#.XvBr7GgzaUk)                                                                                                                  | 2020-05      | MICCAI'2020                    |
| [BraTS21](./resources/BraTS2021.md)                   | 3D MRI, 2040 Cases, 3 Categories of Glioma Segmentation                                                           | [Synapse](https://www.synapse.org/#!Synapse:syn25829067/wiki/610863)                           | [Synapse](https://www.synapse.org/#!Synapse:syn51514105)                                   | [ArXiv'2021](https://arxiv.org/abs/2107.02314)                                                                                                                             | 2021-07      | RSNA-ASNR-MICCAI'2021          |
| [FeTA 2022](./resources/FeTA.md)                      | 3D MRI, 280 Cases, 7 Categories of Infant Brain Tissue Segmentation                                               | [Grand Challenge](https://feta.grand-challenge.org/)                                           | -                                                                                          | [Scientific Data](https://www.nature.com/articles/s41597-021-00946-3)                                                                                                      | 2021         | MICCAI'2021 & 2022             |
| [ATLAS v2.0 (ISLES 2022)](./resources/ATLASv2.0.md)   | 3D MRI, 1271 Cases, 1 Category of Lesions After Stroke Segmentation                                               | [Grand Challenge](https://atlas.grand-challenge.org/)                                          | [Project Homepage](http://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)              | [Scientific Data](https://www.nature.com/articles/s41597-022-01401-7)                                                                                                      | 2021-12      | MICCAI'2022                    |
| [cSeg 2022](./resources/cSeg2022.md)                  | 3D MRI, 13 Cases, 3 Categories of Brain Tissue Segmentation                                                       | [Project Homepage](https://tarheels.live/cseg2022/)                                            | [Project Homepage](https://tarheels.live/cseg2022/data/)                                   | -                                                                                                                                                                          | 2022-04      | MICCAI'2022                    |
| [HECKTOR](./resources/HECKTOR_2022.md)                | 3D PET-CT, 882 Cases, 2 Categories of Tumor and Lymph Node                                                        | [Grand Challenge](https://hecktor.grand-challenge.org/)                                        | -                                                                                          | [Springer Link](https://link.springer.com/book/10.1007/978-3-031-27420-6)                                                                                                  | 2022-06      | MICCAI'2022                    |
| [INSTANCE 2022](./resources/INSTANCE_2022.md)         | 3D CT, 200 Cases, 1 Category of Intracranial Hemorrhage Segmentation                                              | [Grand Challenge](https://instance.grand-challenge.org/)                                       | -                                                                                          | [Biomedical and Health Informatics ](https://ieeexplore.ieee.org/document/9511297)                                                                                         | 2022-04      | MICCAI'2022                    |
| [ISLES22](./resources/ISLES22.md)                     | 3D MRI, 400 Cases, 1 Category of Ischemic Stroke Lesion Segmentation                                              | [Grand Challenge](https://isles22.grand-challenge.org/)                                        | [Zenodo](https://doi.org/10.5281/zenodo.7153326)                                           | [Scientific Data](https://www.nature.com/articles/s41597-022-01875-5)                                                                                                      | 2022-05      | MICCAI'2022                    |
| [Teeth3DS](./resources/Teeth3DS.md)                   | 3D IOS, 1800 Cases, 32 Categories of Teeth Segmentation                                                           | [Github](https://github.com/DCBIA-OrthoLab/3DTeethSeg22_challenge)                             | [OSF](https://osf.io/xctdy/)                                                               | [ArXiv'2022](https://arxiv.org/pdf/2210.06094)                                                                                                                             | 2022-10      | MICCAI'2022                    |
| [TN3K](./resources/TN3K.md)                           | 2D Ultrasound, 3494 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)               | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)           | [ISBI'2021](https://ieeexplore.ieee.org/abstract/document/9434087/)                                                                                                        | 2021-05      | ISBI'2021                      |
| [TG3K](./resources/TG3K.md)                           | 2D Ultrasound, 3585 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)               | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)           | [Computers in Biology and Medicine](https://www.sciencedirect.com/science/article/pii/S0010482522010976)                                                                   | 2022-12      | ISBI'2021                      |
| [HaN-Seg](./resources/HaN-Seg.md)                     | 3D CT & MRI, 42 Cases, 30 Categories of Head and Neck Organs-at-Risk Segmentation                                 | [Grand Challenge](https://han-seg2023.grand-challenge.org/)                                    | [Zenodo](https://zenodo.org/record/7442914#.ZBtfBHbMJaQ)                                   | [Medical Physics](https://aapm.onlinelibrary.wiley.com/doi/10.1002/mp.16197)                                                                                               | 2023-01      | -                              |
| [SMILE-UHURA 2023](./resources/SMILE-UHURA%202023.md) | 3D 7T High Resoulution MRI, 14 Cases, 1 Category of Cerebral Artery Segmentation                                  | [Synapse](https://www.synapse.org/#!Synapse:syn47164761/wiki/620033)                           | [Synapse](https://www.synapse.org/#!Synapse:syn47164761/wiki/620033)                       | -                                                                                                                                                                          | 2023-03      | ISBI'2023                      |
| [ToothFairy](./resources/ToothFairy.md)               | 3D CBCT, 443 Cases, 1 Category of Inferior Alveolar Nerve Segmentation                                            | [Grand Challenge](https://toothfairy.grand-challenge.org/toothfairy/)                          | [Project Homepage](https://ditto.ing.unimore.it/toothfairy/)                               | [CVPR'2022](https://openaccess.thecvf.com/content/CVPR2022/html/Cipriano_Improving_Segmentation_of_the_Inferior_Alveolar_Nerve_Through_Deep_Label_CVPR_2022_paper.html)    | 2023-03      | MICCAI'2023                    |
| [SegRap 2023](./resources/SegRap2023.md)              | 3D CT, 200 Cases, 47 Categories of Head and Neck Organs-at-Risk Segmentation                                      | [Grand Challenge](https://segrap2023.grand-challenge.org/)                                     | -                                                                                          | [ArXiv'2023](https://arxiv.org/abs/2312.09576)                                                                                                                             | 2023-04      | MICCAI'2023                    |
| [CAS2023](./resources/CAS2023.md)                     | 3D MRI, 100 Cases, 1 Category of Cerebral Artery Segmentation                                                     | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/9804)                                  | [CodeLab](https://codalab.lisn.upsaclay.fr/competitions/9804#participate-get_starting_kit) | -                                                                                                                                                                          | 2023-04      | MICCAI'2023                    |
| [CrossMoDA 2023](./resources/CrossMoDA2023.md)        | 3D MRI, 983 Cases, 3 Categories of Vestibular Schwannoma (VS) and Cochlea Segmentation                            | [Project Homepage](https://crossmoda-challenge.ml/)                                            | [Synapse](https://www.synapse.org/#!Synapse:syn51236108/files/)                            | [MIA'2023](https://www.sciencedirect.com/science/article/pii/S1361841522002560)                                                                                            | 2023-04      | MICCAI'2023                    |
| [BraTS2023-SSA](./resources/BraTS2023-SSA.md)         | 3D MRI, 105 Cases, 3 Categories of Glioma Segmentation in Africa                                                  | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622556)                           | [Synapse](https://www.synapse.org/#!Synapse:syn51514109)                                   | [ArXiv'2023](https://arxiv.org/abs/2305.19369)                                                                                                                             | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-MEN](./resources/BraTS2023-MEN.md)         | 3D MRI, 1650 Cases, 3 Categories of Meningioma Segmentation                                                       | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622353)                           | [Synapse](https://www.synapse.org/#!Synapse:syn51514106)                                   | [ArXiv'2023](https://arxiv.org/pdf/2305.07642)                                                                                                                             | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-PED](./resources/BraTS2023-PED.md)         | 3D MRI, 228 Cases, 3 Categories of Pediatrics Glioma Segmentation                                                 | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622461)                           | [Synapse](https://www.synapse.org/#!Synapse:syn51514108)                                   | [ArXiv'2023](https://arxiv.org/abs/2305.17033)                                                                                                                             | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-MET](./resources/BraTS2023-MET.md)         | 3D MRI, 328 Cases, 3 Categories of Brain Metastasis Segmentation                                                  | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622553)                           | [Synapse](https://www.synapse.org/#!Synapse:syn51514107)                                   | [ArXiv'2023](https://arxiv.org/abs/2306.00838)                                                                                                                             | 2023-06      | ASNR-MICCAI'BRATS2023          |

### Chest


| Dataset                                                                       | Description                                                                                     | Official Website                                                                            | Download Link                                                                                            | Paper                                                                                                      | Release Date | Challenge                      |
|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [LUNA16](./resources/LUNA16.md)                                               | 3D CT, 888 Cases, 1 Category of Lung Nodule Detection                                           | [Grand Challenge](https://luna16.grand-challenge.org/Home/)                                 | -                                                                                                        | [MIA'2017](https://doi.org/10.1016/j.media.2017.06.015)                                                    | 2016-03      | LUNA16                         |
| [Breast Ultrasound Dataset B](./resources/Breast_Ultrasound_DatasetB.md)      | 2D Ultrasound, 163 Cases, 1 Category of Breast Lesions Detection                                | [Project Homepage](http://www2.docm.mmu.ac.uk/STAFF/M.Yap/dataset.php)                      | -                                                                                                        | [Biomedical and Health Informatics'2017](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8003418)     | 2018-06      | -                              |
| [FUMPE](./resources/FUMPE.md)                                                 | 3D CT, 35 Cases, 1 Category of Pulmonary Embolism (PE) Segmentation                             | [Figshare](https://figshare.com/collections/FUMPE/4107803/1)                                | [Kaggle](https://www.kaggle.com/datasets/andrewmvd/pulmonary-embolism-in-ct-images)                      | [Scientific Data](https://www.nature.com/articles/sdata2018180)                                            | 2018-09      | -                              |
| [SegTHOR](./resources/SegTHOR.md)                                             | 3D CT, 60 Cases, 4 Categories of Thoracic Organs at Risk Segmentation                           | [CodaLab](https://competitions.codalab.org/competitions/21145)                              | [CodaLab](https://competitions.codalab.org/competitions/21145#participate-get_starting_kit)              | [IPTA'2020](https://ieeexplore.ieee.org/document/9286453)                                                  | 2019-01      | ISBI'2019                      |
| [MSD Lung Tumours](./resources/MSD_Lung_Tumours.md)                           | 3D CT, 96 Cases, 1 Category of Lung Tumor Segmentation                                          | [MSD](http://medicaldecathlon.com/)                                                         | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2)                 | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                                 | 2019-02      | Medical Segmentation Decathlon |
| [LNDb](./resources/LNDb.md)                                                   | 3D CT, 294 Cases, 1 Category of Lung Nodule Segmentation                                        | [Grand Challenge](https://lndb.grand-challenge.org/)                                        | [Zenodo](https://zenodo.org/record/7153205#.Yz_oVHbMJPZ)                                                 | [MIA'2021](https://pubmed.ncbi.nlm.nih.gov/33740739/)                                                      | 2019-11      | ICIAR'2020                     |
| [BUSI](./resources/BUSI.md)                                                   | 3D Ultrasound, 780 Cases, 3 Categories of Breast Tumor Segmentation                             | [Project Homepage](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset)                       | [Project Homepage](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset)                                    | [Data in Brief'2020](https://www.sciencedirect.com/science/article/pii/S2352340919312181)                  | 2019-11      | -                              |
| [PleThora](./resources/PleThora.md)                                           | 3D CT, 402 Cases, 2 Categories of Pleural Effusion and Thoracic Segmentation                    | [TCIA](https://www.cancerimagingarchive.net/analysis-result/plethora/)                      | [TCIA](https://www.cancerimagingarchive.net/analysis-result/plethora/)                                   | [Medical Physics'2020](https://aapm.onlinelibrary.wiley.com/doi/epdf/10.1002/mp.14424)                     | 2020-04      | -                              |
| [COVID_CT_COVID-CT](./resources/COVID_CT_COVID-CT.md)                         | 2D CT, 746 Cases, 2 Categories of Pneumonia Classification                                      | [Tianchi](https://tianchi.aliyun.com/dataset/106604)                                        | -                                                                                                        | [ArXiv'2020](https://arxiv.org/pdf/2003.13865.pdf)                                                         | 2020-06      | -                              |
| [COVIDGR](./resources/COVIDGR.md)                                             | 2D X-Ray, 852 Cases, 2 Categories Pneumonia Classification                                      | [Github](https://github.com/ari-dasci/covidgr)                                              | [OpenDataLab](https://opendatalab.com/OpenDataLab/COVIDGR)                                               | [Biomedical and Health Informatics'2020](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9254002) | 2020-12      | -                              |
| [COVID-19 CHEST X-RAY DATABASE](./resources/COVID-19_CHEST_X-RAY_DATABASE.md) | 2D X-ray, 3886 Cases, 3 Categories of Pneumonia Classification                                  | [Project Homepage](https://www.heywhale.com/mw/dataset/6027caee891f960015c863d7/content)    | [Google Drive](https://drive.google.com/file/d/1xt7g5LkZuX09e1a8rK9sRXIrGFN6rjzl/view?usp=sharing)       | [IEEE Access'2020](https://ieeexplore.ieee.org/abstract/document/9144185)                                  | 2021-01      | -                              |
| [Chest CT-Scan images](./resources/ChestCT-Scan_images.md)                    | 2D CT, 1000 Cases, 4 Categories of Lung Tumor Classification                                    | [Tianchi](https://tianchi.aliyun.com/dataset/93929)                                         | -                                                                                                        | -                                                                                                          | 2021-03      | -                              |
| [COVID-19-CT SCAN IMAGES](./resources/COVID-19-CT_SCAN_IMAGES.md)             | 2D CT, 1400 Cases, 2 Categories of Pneumonia Classification                                     | [Tianchi](https://tianchi.aliyun.com/dataset/93666)                                         | -                                                                                                        | -                                                                                                          | 2021-03      | -                              |
| [Chest X-ray PD Dataset](./resources/ChestX-rayPDDataset.md)                  | 2D X-Ray, 4575 Cases, 3 Categories of Pneumonia Classification                                  | [Project Homepage](https://data.mendeley.com/datasets/jctsfj2sfn/1)                         | [Project Homepage](https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/jctsfj2sfn-1.zip) | -                                                                                                          | 2021-04      | -                              |
| [Shenzhen chest X-ray set](./resources/Shenzhen_chest_X-ray.md)               | 2D X-Ray, 662 cases, 2 Categories of Tuberculosis Classification                                | [NIH](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets) | [NIH](https://openi.nlm.nih.gov/imgs/collections/ChinaSet_AllFiles.zip)                                  | [Quantitative Imaging in Medicine and Surgery'2014](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4256233/) | 2021-06      | -                              |
| [Chest X-Ray Imaging_(Pneumonia)](./resources/ChestX-RayImaging_Pneumonia.md) | 2D X-ray, 5856 Cases, 2 Categories of Pneumonia Classification                                  | [Project Homepage](https://www.heywhale.com/mw/dataset/62c2ac49913a54a66037f872/content)    | [Project Homepage](https://www.heywhale.com/mw/dataset/62c2ac49913a54a66037f872/file)                    | [paper](https://data.mendeley.com/datasets/rscbjbr9sj/2)                                                   | 2022-07      | -                              |
| [Parse 2022](./resources/Parse.md)                                            | 3D CT, 200 Cases, 1 Category of Pulmonary Artery Segmentation                                   | [Grand Challenge](https://parse2022.grand-challenge.org/)                                   | -                                                                                                        | [ArXiv'2023](https://arxiv.org/abs/2304.03708)                                                             | 2022-04      | MICCAI'2022                    |
| [ATM22](./resources/ATM22.md)                                                 | 3D CT, 500 Cases, 1 Category of Lung Airway Segmentation                                        | [Grand Challenge](https://atm22.grand-challenge.org/)                                       | -                                                                                                        | [MIA'2023](https://www.sciencedirect.com/science/article/pii/S1361841523002177)                            | 2022-05      | MICCAI'2022                    |
| [MVSeg-3DTEE 2023](./resources/MVSeg-3DTEE.md)                                | 3D Ultrasound, 175 Cases, 2 Categories of Mitral Valve Segmentation                             | [Synapse](https://www.synapse.org/#!Synapse:syn51186045/wiki/621356)                        | [Synapse](https://www.synapse.org/#!Synapse:syn51186045/wiki/621356)                                     | [Thesis](https://ir.lib.uwo.ca/cgi/viewcontent.cgi?article=12693&context=etd)                              | 2023         | MICCAI'2023                    |
| [TDSC-ABUS2023](./resources/TDSC-ABUS2023.md)                                 | 3D Ultrasound, 200 Cases, 1 Category of Breast Tumor Detection, Segmentation and Classification | [Grand Challenge](https://tdsc-abus2023.grand-challenge.org/TDSC-ABUS2023/)                 | -                                                                                                        | -                                                                                                          | 2023-03      | MICCAI'2023                    |
| [AIIB23](./resources/AIIB23.md)                                               | 3D CT, 312 Cases, 1 Category of Lung Airway Segmentation                                        | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/13238)                              | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/13238#learn_the_details-dataset)                 | -                                                                                                          | 2023-05      | MICCAI'2023                    |
| [SEG.A.](./resources/SEG.A.md)                                                | 3D CTA, 56 Cases, 1 Category of Aorta Segmentation                                              | [Grand Challenge](https://multicenteraorta.grand-challenge.org/)                            | -                                                                                                        | [Data in Brief'2022](https://www.sciencedirect.com/science/article/pii/S2352340922000130?via%3Dihub)       | 2023-05      | MICCAI'2023                    |
| [LNQ 2023](./resources/LNQ2023.md)                                            | 3D CT, 513 Cases, 1 Category of Lymph Node Quantification                                       | [Grand Challenge](https://lnq2023.grand-challenge.org/lnq2023/)                             | -                                                                                                        | -                                                                                                          | 2023-05      | MICCAI'2023                    |
| [SARS-COV-2 Ct-Scan](./resources/SARS-COV-2.md)                               | 2D CT, 2482 Cases, 2 Categories of Pneumonia Classification                                     | [Kaggle](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)             | -                                                                                                        | [paper](https://www.medrxiv.org/content/10.1101/2020.04.24.20078584v3.full.pdf)                            | 2020-05      | -                              |


### Abdomen

| Dataset                                                                                         | Description                                                                | Official Website                                                                                    | Download Link                                                                            | Paper                                                                                          | Release Date | Challenge                      |
|:------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [3D-IRCADB](./resources/3D-IRCADB.md)                                                           | 3D CT, 22 Cases, 40 Categories of Abdominal Organ and Tumor Segmentation   | [Project Homepage](https://www.ircad.fr/research/data-sets/liver-segmentation-3d-ircadb-01/)        | [Project Homepage](https://cloud.ircad.fr/index.php/s/JN3z7EynBiwYyjy/download)          | [paper](https://www-sop.inria.fr/geometrica/events/wam/abstract-ircad.pdf)                     | 2010         | -                              |
| [BTCV](./resources/BTCV.md)                                                                     | 3D CT, 50 Cases, 13 Categories of Abdominal Organ Segmentation             | [Synapse](https://www.synapse.org/#!Synapse:syn3193805/wiki/)                                       | [Synapse](https://www.synapse.org/#!Synapse:syn3193805/files/)                           | -                                                                                              | 2015-04      | MICCAI'2015                    |
| [BTCV Cervix](./resources/BTCV_Cervix.md)                                                       | 3D CT, 50 Cases, 4 Categories of Abdominal Organ Segmentation              | [Synapse](https://www.synapse.org/#!Synapse:syn3193805/wiki/217790)                                 | [Synapse](https://www.synapse.org/#!Synapse:syn3378972)                                  | -                                                                                              | 2015-04      | MICCAI'2015                    |
| [LiTS](./resources/LiTS.md)                                                                     | 3D CT, 201 Cases, 2 Categories of Liver and Tumor Segmentation             | [CodaLab](https://competitions.codalab.org/competitions/17094)                                      | [CodaLab](https://competitions.codalab.org/competitions/17094#participate)               | [MIA'2023](https://www.sciencedirect.com/science/article/pii/S1361841522003085)                | 2017-06      | ISBI'2017, MICCAI'2017 & 2018  |
| [MSD Pancreas Tumour](./resources/MSD_Pancreas_Tumour.md)                                       | 3D CT, 420 Cases, 2 Categories of Pancreas and Tumour Segmentation         | [MSD](http://medicaldecathlon.com/)                                                                 | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                     | 2019-02      | Medical Segmentation Decathlon |
| [MSD Hepatic Vessel](./resources/MSD_Hepatic_Vessel.md)                                         | 3D CT, 443 Cases, 2 Categories Liver Blood vessels and Tumor Segmentation  | [MSD](http://medicaldecathlon.com/)                                                                 | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                     | 2019-02      | Medical Segmentation Decathlon |
| [MSD Spleen](./resources/MSD_Spleen.md)                                                         | 3D CT, 61 Cases, 1 Category of Spleen Segmentation                         | [MSD](http://medicaldecathlon.com/)                                                                 | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                     | 2019-02      | Medical Segmentation Decathlon |
| [MSD Colon Cancer](./resources/MSD_Colon_Cancer.md)                                             | 3D CT, 190 Cases, 1 Category of Colon Tumor Segmentation                   | [MSD](http://medicaldecathlon.com/)                                                                 | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                     | 2019-02      | Medical Segmentation Decathlon |
| [MSD Prostate](./resources/MSD_Prostate.md)                                                     | 3D MR, 48 Cases, 2 Categories of Prostate Segmentation                     | [MSD](http://medicaldecathlon.com/)                                                                 | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)                     | 2019-02      | Medical Segmentation Decathlon |
| [KiTS19](./resources/KiTS19.md)                                                                 | 3D CT, 300 Cases, 2 Categories of Kidney and Tumor Segmentation            | [Grand Challenge](https://kits19.grand-challenge.org/)                                              | [Github](https://github.com/neheller/kits19)                                             | [MIA'2021](https://www.sciencedirect.com/science/article/pii/S1361841520301857)                | 2019-03      | MICCAI'2019                    |
| [CHAOS](./resources/CHAOS.md)                                                                   | 3D CT&MRI, 40 Cases, 4 Categories of Abdominal Organ Segmentation          | [Grand Challenge](https://chaos.grand-challenge.org/Combined_Healthy_Abdominal_Organ_Segmentation/) | [Zenodo](https://zenodo.org/record/3431873#.Yl_9itpBxaQ)                                 | [MIA'2021](https://linkinghub.elsevier.com/retrieve/pii/S1361841520303145)                     | 2019-04      | ISBI'2019                      |
| [KiTS21](./resources/KiTS21.md)                                                                 | 3D CT, 400 Cases, 3 Categories of Kidney and Tumor Segmentation            | [Project Homepage](https://kits-challenge.org/kits21/)                                              | -                                                                                        | [ArXiv'2021](https://arxiv.org/abs/1912.01054)                                                 | 2021-03      | MICCAI'2021                    |
| [FLARE 2021](./resources/FLARE2021.md)                                                          | 3D CT, 511 Cases, 4 Categories of Abdominal Organ Segmentation             | [Grand Challenge](https://flare.grand-challenge.org/)                                               | -                                                                                        | [MIA'2022](https://www.sciencedirect.com/science/article/abs/pii/S1361841522002444?via%3Dihub) | 2021-05      | MICCAI'2021                    |
| [AbdomenCT-1K](./resources/AbdomenCT-1K.md)                                                     | 3D CT, 1112 Cases, 4 Categories of Abdominal Organ Segmentation            | [Github](https://github.com/JunMa11/AbdomenCT-1K)                                                   | [Github](https://github.com/JunMa11/AbdomenCT-1K)                                        | [TPAMI'2021](https://ieeexplore.ieee.org/document/9497733)                                     | 2021-07      | -                              |
| [QUBIQ2021](./resources/QUBIQ2021.md)                                                           | 3D CT, 90 Cases, 2 Categories of Pancreas and Lesions Segmentation         | [Grand Challenge](https://qubiq21.grand-challenge.org/QUBIQ2021/)                                   | -                                                                                        | [MICCAIWorkshop'2021](https://link.springer.com/chapter/10.1007/978-3-031-08999-2_9)           | 2021-08      | MICCAI'2021                    |
| [WORD](./resources/WORD.md)                                                                     | 3D CT, 150 Cases, 16 Categories of Abdominal Organ Segmentation            | [Github](https://github.com/HiLab-git/WORD)                                                         | [Github](https://github.com/HiLab-git/WORD)                                              | [MIA'2022](https://arxiv.org/pdf/2111.02403.pdf)                                               | 2021-11      | -                              |
| [FLARE 2023](./resources/FLARE2023.md)                                                          | 3D CT, 2300 Cases, 13 Categories of Abdominal Organ Segmentation           | [Grand Challenge](https://flare22.grand-challenge.org/)                                             | -                                                                                        | [ArXiv'2023](https://arxiv.org/pdf/2308.05862.pdf)                                             | 2022-03      | MICCAI'2022                    |
| [KiPA22](./resources/KiPA22.md)                                                                 | 3D CTA, 130 Cases, 4 Categories of Vessel and Tumor Segmentation           | [Grand Challenge](https://kipa22.grand-challenge.org/)                                              | -                                                                                        | [MIA'2021](https://www.sciencedirect.com/science/article/abs/pii/S1361841521001018)            | 2022-04      | MICCAI'2022                    |
| [AMOS 2022](./resources/AMOS.md)                                                                | 3D CT&MRI, 600 Cases, 15 Categories of Abdominal Organ Segmentation        | [Grand Challenge](https://amos22.grand-challenge.org/)                                              | -                                                                                        | [ArXiv'2022](https://arxiv.org/abs/2206.08023)                                                 | 2022-05      | MICCAI'2022                    |
| [PI-CAI](./resources/PI-CAI.md)                                                                 | 3D MR, 1500 Cases, 1 Category of Prostate Tumor Segmentation               | [Grand Challenge](https://pi-cai.grand-challenge.org/)                                              | [Zenodo](https://zenodo.org/records/6624726)                                             | -                                                                                              | 2022-05      | -                              |
| [LLD-MMRI2023](./resources/LLD-MMRI2023.md)                                                     | 3D MRI, 394 Cases, Liver Lesion Detection                                  | [Github](https://github.com/LMMMEng/LLD-MMRI2023/tree/main?tab=readme-ov-file)                      | -                                                                                        | [paper](https://zenodo.org/records/7852363)                                                    | 2023-02      | MICCAI'2023                    |
| [SPPIN](./resources/SPPIN.md)                                                                   | 3D MRI, 111 Cases, 1 Category of Pediatric Neuroblastoma Segmentation      | [Grand Challenge](https://sppin.grand-challenge.org/sppin/)                                         | [Zenodo](https://zenodo.org/record/7845214)                                              | [paper](https://doi.org/10.5281/zenodo.7848306)                                                | 2023-04      | MICCAI'2023                    |
| [FLARE 2023](./resources/FLARE2023.md)                                                          | 3D CT, 4500 Cases, 14 Categories of Abdominal Organ and Tumor Segmentation | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/12239)                                      | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/12239#learn_the_details-dataset) | -                                                                                              | 2023-04      | MICCAI'2023                    |
| [KiTS23](./resources/KiTS23.md)                                                                 | 3D CT, 599 Cases, 3 Categories of Kidney and Tumor Segmentation            | [Project Homepage](https://kits-challenge.org/kits23/)                                              | -                                                                                        | [MIA'2021](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301857)            | 2023-04      | MICCAI'2023                    |
| [ATLAS (MICCAI2023)](./resources/ATLAS.md)                                                      | 3D CE-MRI, 90 Cases, 2 Categories of Liver and Tumor Segmentation          | [Grand Challenge](https://atlas-challenge.u-bourgogne.fr/)                                          | -                                                                                        | [paper](https://doi.org/10.3390/data8050079)                                                   | 2023-04      | MICCAI'2023                    |
| [MOOD2023](./resources/MOOD2023.md)                                                             | 3D CT&MR, 1300 Cases, Out-of-Distribution Detection                        | [Project Homepage](http://medicalood.dkfz.de/web/)                                                  | [Project Homepage](http://medicalood.dkfz.de/BzlSoOiDmh/dd.html)                         | [TMI'2022](https://ieeexplore.ieee.org/document/9762702)                                       | 2023-04      | MICCAI'2023                    |
| [UW-Madison GI Tract Image Segmentation](./resources/UW-Madison_GI_Tract_Image_Segmentation.md) | 2D MRI, 38496 Cases, 3 Categories of Gastrointestinal Tract Segmentation   | [Kaggle](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/overview)       | -                                                                                        | -                                                                                              | 2022-04      | -                              |

### Heart

| Dataset                                       | Description                                                                               | Official Website                                                      | Download Link                                                                                         | Paper                                                                           | Release Date | Challenge                      |
|:----------------------------------------------|:------------------------------------------------------------------------------------------|:----------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [ACDC](./resources/ACDC.md)                   | 3D MRI, 150 Cases, 3 Categories of Left and Right Ventricles and Myocardial Segmentation  | [Project Homepage](https://www.creatis.insa-lyon.fr/Challenge/acdc/)  | [Link](https://humanheart-project.creatis.insa-lyon.fr/database/#collection/637218c173e9f0047faa00fb) | [TMI'2018](https://ieeexplore.ieee.org/document/8360453)                        | 2017         | MICCAI'2017                    |
| [MM-WHS](./resources/MM-WHS.md)               | 3D CT/MRI, 120 Cases, 7 Categories of Heart Substructure Segmentation                     | [Github](https://zmiclab.github.io/zxh/0/mmwhs/)                      | [Link](https://mega.nz/folder/UNMF2YYI#1cqJVzo4p_wESv9P_pc8uA)                                        | [TPAMI'2019](https://ieeexplore.ieee.org/document/8458220)                      | 2017         | MICCAI'2017                    |
| [MyoPS 2020](./resources/MyoPS_2020.md)       | 3D MRI, 45 Cases, 5 Categories of Myocardial Pathology Segmentation                       | [Github](https://zmiclab.github.io/zxh/0/myops20/)                    | [Link](https://mega.nz/folder/BRdnDISQ#FnCg9ykPlTWYe5hrRZxi-w)                                        | [TPAMI'2023](https://ieeexplore.ieee.org/document/9965747)                      | 2020-04      | MICCAI'2020                    |
| [LAScarQS 2022](./resources/LAScarQS_2022.md) | 3D MRI, 194 Cases, 2 Categories of Left Atrium and Scar Segmentation                      | [Github](https://zmiclab.github.io/projects/lascarqs22/)              | [Github](https://zmiclab.github.io/projects/lascarqs22/data.html)                                     | [MIA'2022](https://www.sciencedirect.com/science/article/pii/S1361841521003480) | 2022-04      | MICCAI'2022                    |
| [CMRxMotion](./resources/CMRxMotion.md)       | 3D MRI, 360 Cases, 3 Categories of Heart Structure Segmentation                           | [Synapse](https://www.synapse.org/#!Synapse:syn28503327/wiki/617823)  | -                                                                                                     | [ArXiv'2022](https://arxiv.org/abs/2210.06385)                                  | 2022-05      | MICCAI'2022                    |
| [MSD Cardiac](./resources/MSD_Cardiac.md)     | 3D MRI, 30 Cases, 1 Category of Left Atrium Segmentation                                  | [MSD](http://medicaldecathlon.com/)                                   | [Google Drive](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2)              | [Nature Communication](https://www.nature.com/articles/s41467-022-30695-9)      | 2019-02      | Medical Segmentation Decathlon |


### Bones

| Dataset                                 | Description                                                                              | Official Website                                         | Download Link                                            | Paper                                                                      | Release Date | Challenge          |
|:----------------------------------------|:-----------------------------------------------------------------------------------------|:---------------------------------------------------------|:---------------------------------------------------------|:---------------------------------------------------------------------------|:-------------|:-------------------|
| [VerSe](./resources/VerSe.md)           | 3D CT, 374 Cases, 26 Categories of Spine Segmentation                                    | [Github](https://github.com/anjany/verse)                | -                                                        | [MIA'2021](https://linkinghub.elsevier.com/retrieve/pii/S1361841521002127) | 2020-05      | MICCAI'2019 & 2020 |
| [CTPelvic1K](./resources/CTPelvic1K.md) | 3D CT, 1184 Cases, 4 Categories of Lumbar Spine, Sacrum, Left and Right Hip Segmentation | [Github](https://github.com/MIRACLE-Center/CTPelvic1K)   | [Zenodo](https://zenodo.org/record/4588403#.YEyLq_0zaCo) | [IJCARS](https://link.springer.com/article/10.1007/s11548-021-02363-8)     | 2020-12      | -                  |
| [CTSpine1K](./resources/CTSpine1K.md)   | 3D CT, 1005 Cases, 25 Categories of Spine Segmentation                                   | [Github](https://github.com/MIRACLE-Center/CTSpine1K)    | -                                                        | [ArXiv'2021](https://arxiv.org/abs/2105.14711)                             | 2021-05      | -                  |
| [SPIDER](./resources/SPIDER.md)         | 3D MR, 544 Cases, 19 Categories of Spine, Intervertebral Disc, Spinal Canal Segmentation | [Grand Challenge](https://spider.grand-challenge.org/)   | -                                                        | [ArXiv'2023](https://arxiv.org/abs/2306.12217)                             | 2023-06      | -                  |

### Endoscopy

[Kvasir-SEG](./resources/Kvasir-SEG.md) (2D, Endoscopy, 1160 Cases, 1 Category)

[Kvasir-Capsule](./resources/Kvasir-Capsule.md) (2D, Endoscopy, 4741504 Cases, 14 Categories)

[CVC-ClinicDB](./resources/CVC-ClinicDB.md) (2D, Endoscopy, 612 Cases, 1 Category)

[EndoMapper](./resources/EndoMapper.md) (2D, Endoscopy Video, 59 Cases)

[EndoSLAM](./resources/EndoSLAM.md) (2D, Endoscopy, 64577 Cases)

[m2caiseg](./resources/m2caiseg.md) (2D, Endoscopy, 307 Cases, 19 Categories)

[EAD 2019](./resources/EAD2019.md) (2D, Endoscopy, 2991 Cases, 7 Categories)

[LDPolypVideo](./resources/LDPolypVideo.md) (2D, Endoscopy, 861400帧, 1 Category)

[LIMUC](./resources/LIMUC.md) (2D, Endoscopy, 11276, 4 Categories)

[SUN Colonoscopy Video](./resources/SUN_Colonoscopy_Video.md) (2D, Endoscopy, 158,690 Cases, 100 Categories)

[Colonoscopic](./resources/Colonoscopic.md) (2D, Endoscopy, 152 Cases, 3 Categories)

[Sinus Surgery Endoscopic Image Datasets](./resources/Sinus_Surgery.md) (2D Rhinoscopy, 9003 Cases, 1 Category)

[The Nerthus Dataset](./resources/Nerthus.md) (2D Endoscopy, 5525 Cases, Classification of 4 Categories of intestinal cleansing levels)

[CholecT45 Dataset](./resources/CholecT45.md) (2D Endoscopy, 90489 Cases, 128 Categories of cholecystectomy surgery action recognition)

[CholecSeg8k](./resources/CholecSeg8k.md) (2D Endoscopy, 8080 Cases, 13 Categories of Cholecystectomy Surgery Semantic segmentation)

[FetReg 2021 Task1](./resources/FetReg.md) (2D Fetoscope, 2718 Cases, 3 Categories of Blood vessels, Fetus, Surgical Tools Segmentation)

[Endoscopic Bladder Tissue Classification Dataset](./resources/Endoscopic_Bladder_Tissue_Classification.md) (2D Endoscopy, 1754 Cases, 4 Categories of Cystoscopy Tissue Classification)

[Surgical scene segmentation](./resources/Surgical_Scene_Segmentation.md) (2D Endoscopy, 9156 Cases, 32 Categories of Surgery Scene Segmentation)

[SARAS-ESAD](./resources/SARAS-ESAD.md) (2D Endoscopy, 33398 Cases, 21 Categories of Surgical Action Recognition)

### Retina

[ODIR-5K](./resources/ODIR-5K.md) (2D retinal images, 5000 Cases, 8 Categories)

[RFMiD 2.0](./resources/RFMiD.md) (2D retinal images, 3200 Cases, 45 Categories)

[Multi-Label Retinal Diseases](./resources/Multi-LabelRetinalDiseases.md) (2D retinal images, 2451 Cases, 20 Categories of Eye Diseases Classification)

[STARE](./resources/STARE.md) (2D retinal images, 20 Cases, 1 Category)

[DRIVE](./resources/DRIVE.md) (2D retinal images, 40 Cases, 1 Category)

[CHASE](./resources/CHASE.md) (2D retinal images, 28 Cases, 1 Category)

[HRF](./resources/HRF.md) (2D retinal images, 45 Cases, 1 Category)

[IDRID](./resources/IDRID.md) (2D retinal images, 81 Cases, 5 Categories)

[ORVS](./resources/ORVS.md) (2D retinal images, 49 Cases, 1 Category)

[LES-AV](./resources/LES-AV.md) (2D retinal images, 22 Cases, 1 Category)

[PALM19](./resources/PALM19.md) (2D retinal images, 1200 Cases, 1 Category)

[RITE](./resources/RITE.md) (2D retinal images, 40 Cases, 1 Category)

[Retinal image quality assessment dataset](./resources/Retinal_QA.md) (2D retinal images, 216 Cases, 3 Categories of image quality evaluation)

[DRISHTI-GS](./resources/DRISHTI-GS.md) (2D retinal images, 101 Cases, 2 Categories of Optic Cup and Optic Disc Segmentation)

[Retina](./resources/Retina.md) (2D retinal images, 601 Cases, 4 Categories of Cataracts, Glaucoma Retinopathy)

[Eyepacs](./resources/Eyepacs.md) (2D retinal images, 35126 Cases, 5 Categories of Diabetic Retinopathy Grading)

[Messidor-2](./resources/Messidor-2.md) (2D retinal images, 1748 Cases, 2 Categories of Diabetic Retinopathy Classification)

[OCTA-500](./resources/OCTA-500.md) (2D OCT , 500 Cases, 1 Category)

[ROSE](./resources/ROSE.md) (2D OCT, 229 Cases, 1 Category)

[Retinal OCT-C8](./resources/Retinal_OCT-C8.md) (2D OCT, 24000 Cases, 8 Categories)

[RETOUCH](./resources/RETOUCH.md) (3D OCT, 112例, 3 Categories)

[OCT 2017](./resources/OCT2017.md) (2D OCT, 35126 Cases, 4 Categories of Eye Disease Classification)

### Skin

[ISIC 2017](./resources/ISIC2017.md) (2D dermoscopic images, 2750 Cases, 1 Category)

[ISIC 2020](./resources/ISIC2020.md) (2D dermoscopic images，33126 Cases，2 Categories)

[MED-NODE](./resources/MED-NODE.md) (2D dermoscopic images, 170 Cases, 2 Categories)

[PED-UFES-20](./resources/PED-UFES-20.md) (2D dermoscopic images, 2298 Cases, 6 Categories)

[PH²](./resources/PH2.md) (2D dermoscopic images, 200 Cases, 2 Categories)

[Web-scraped Skin Image](./resources/Web-scraped_Skin_Image.md) (2D dermoscopic images, 804 Cases, 6 Categories of Dermatology Classification)

### Microscopic imaging

[NeurIPS 2022 Cell Seg](./resources/NeurIPS2022CellSeg.md) (2D Microscopic imaging, 3022 Cases, 1 Category)

[Malignant Lymphoma Classification](./resources/MalignantLymphomaClassification.md) (2D Pathological sections, 374 Cases, 3 Categories)

[BioMediTech](./resources/BioMediTech.md) (2D Cell imaging, 1862 Cases, 4 Categories)

[GlaS](./resources/GlaS.md) (2D Pathological Images, 165 Cases, 1 Category)

[LC25000](./resources/LC25000.md) (2D Pathological Images, 25000 Cases, 5 Categories)

[CoNIC2022](./resources/CoNIC2022.md) (2D Pathological Images, 4981 Cases, 7 Categories of Segmentation of Nuclei within Tissues)

[MoNuSeg](./resources/MoNuSeg.md) (2D Microscopic imaging, 53 Cases, 1 Category of Nucleus Segmentation)

[Corneal Nerve Tortuosity](./resources/Corneal_Nerve_Tortuosity.md) (2D Microscopic imaging, 30 Cases, 3 Categories of Degree of Corneal Nerve Distortion)

[Corneal Nerve](./resources/Corneal_Nerve.md) (2D Microscopic imaging, 90 Cases, 2 Categories of Corneal Abnormality Classification)

[CORN](./resources/CORN.md) (2D Microscopic imaging，1698 Cases, 1 Category of Corneal Nerve Segmentation)

[HuSHeM](./resources/HuSHeM.md) (2D Microscopic imaging, 216 Cases, 4 Categories of Sperm Classification)

[Malaria Cell Images](./resources/Malaria.md) (2D Microscopic imaging, 27558 Cases, 2 Categories of Malaria Classification)

[DigestPath2019](./resources/DigestPath2019.md) (2D Pathological imaging, 250 Cases, 1 Category of Digestive System Pathology Segmentation and Detection)

[ICIAR 2018 BACH Task1](./resources/ICIAR_2018_BACH_Task1.md) (2D Histology imaging, 400 Cases, 4 Categories of Breast Cancer Classification)

[ICIAR 2018 BACH Task2](./resources/ICIAR_2018_BACH_Task2.md) (2D Histology imaging, 30 Cases, 3 Categories of Breast Cancer Segmentation)

[Complete Blood Count](./resources/CompleteBloodCount.md) (2D Blood Smear, 360 Cases, 3 Categories of Blood Cell Count)

[ANHIR](./resources/ANHIR.md) (2D Pathological imaging, 481 Cases, Pathological image lung lobes and breast tissue registration)

[SICAPv2](./resources/SICAPv2.md) Prostate Pathology Segmentation Dataset (2D Pathological imaging, 18783 Cases, 4 Categories of Prostate Cancer Grade)

[ICPR-HEp-2](./resources/ICPR-HEp-2.md) (2D Cell Fluorescence Microscopy imaging, 14K, 6 Categories of Cell Classification)

[Bone Marrow Cytomorphology](./resources/BoneMarrowCytomorphology.md) (2D Pathological imaging, 171,375 Cases, 21 Categories of Bone Marrow Cell Morphological Classification)

[PatchCamelyon](./resources/PatchCamelyon.md) (2D Pathological imaging, 327,680 Cases, 2 Categories of Breast Cancer Metastasis Classification)

[Leukemia](./resources/Leukemia.md) (2D Microscopic imaging, 1867 Cases, 2 Categories of Leukemia Cell Classification)

## Image text dataset

[VQA-RAD](./resources/VQA-RAD.md) (VQA, 3515  Cases QA Pair)

[SLAKE](./resources/SLAKE.md) (VQA, 14028  Cases QA Pair)

[PathVQA](./resources/PathVQA.md) (VQA, 32799 Cases QA Pair)

[ROCOV2](./resources/ROCOV2.md) (caption, 80080  Cases image-caption Pair)

[ImageClef-2019-VQA-Med](./resources/ImageClef-2019-VQA-Med.md) (VQA, 15292  Cases QA Pair)

[RP3D-Caption](./resources/RP3D-Caption.md) (caption, 69523 Cases image-caption Pair)

[Montgomery County CXR Set](./resources/MontgomeryCounty.md) (2D X-Ray, 138例, 2 Categories of CXR Image Abnormality Diagnosis)

[PMC-OA](./resources/PMC-OA.md) (VQA, 1.6M QA Pair)

[MMMU Health&Medicine](./resources/MMMU_Health&Medicine.md) (VQA, 1752 Cases QA Pair)

[MedICaT](./resources/MedICaT.md) (VQA, 217060 Cases QA Pair)

[CT-RATE](./resources/CT-RATE.md) chest CT and its radiology diagnostic report data set (Caption, 47149 Cases)

[Quilt-1M](./resources/Quilt-1M.md) Visual-Language Histopathology Dataset (Caption, 768826 Cases)

## Text dataset

[MedQA](./resources/MedQA.md) (QA, 61,097 Cases QA Pair)

[MedMCQA](./resources/MedMCQA.md) (QA, 193,155 Cases QA Pair)

[PubMedQA](./resources/PubMedQA.md) (QA, 1000 Cases Expert annotation QA Pair)

[HealthSearchQA](./resources/HealthSearchQA.md) (QA, 3173 Cases QA Pair)

[webMedQA](./resources/webMedQA.md) (QA, 63,284 Cases QA Pair)

[LiveQA](./resources/LiveQA.md) (QA, 634例 QA Pair)

[CMExam](./resources/CMExam.md) (QA, 68K Cases QA Pair)

[CMB](./resources/CMB.md) (QA, 270K Cases QA Pair)

[MedDialog-CN](./resources/MedDialog-CN.md) (QA, 1.1M Cases QA Pair)

[Chinese Medical Dialogue Dataset](./resources/ChineseMedicalDialogueDataset.md) (QA, 792K Cases QA Pair)

[cMedQA](./resources/cMedQA.md) v2.0 (QA, 108K Cases QA Pair)

[Huatuo-26M](./resources/Huatuo-26M.md) (QA, 26M Cases QA Pair)

[ShenNong-TCM-Dataset/EB](./resources/ShenNong-TCM.md) (QA, 113K Cases QA Pair)

[MedBench](./resources/MedBench.md) (QA, 113K Cases QA Pair)











