# BenHamedLab & Co

This github organizes the work of [the BenHamedLab](http://www.BenHamedLab.org) and collaborators. Some aspects of this work is also presented here: [The Brain 3.0 project](https://sites.google.com/view/thebrain30project/accueil/). Current projects are private and will be made public as they are verified and reach the publication stage. 

## **EDNiX (EvoDevo NeuroImaging Explorer)**

Simon Clavagnier*, Clément Garin*, Léon Tremblay, Christos Constantinidis, Suliann Ben Hamed

EDNiX is a comprehensive brain MRI image processing pipeline, designed for longittudinal, cross-species and multimodal data imaging. It is highly flexibile and adaptable to various MRI datasets. The pipeline supports anatomical MRI, functional MRI (fMRI), and PET scans images, facilitating data processing from raw images to statistical analyses. It accommodates as much as possible to the various constraints of different species, imaging setups, and acquisition sequences. EDNiX is developed to enhance cross-species and developmental neuroimaging research. EDNiX can be used with any BIDSified MRI dataset and specific atlases.

Along with EDNiX we will also release MRI datasets and libraries of cross-species atlases. 

Coming soon !

# Other projects BenHamedLab has contributed to

## **[The MacqD deep-learning-based model for automatic detection of socially housed laboratory macaques:](https://www.nature.com/articles/s41598-025-95180-x)**

Genevieve Jiawei Moat*, Maxime Gaudet-Trafit*, Julian Paul, Jaume Bacardit, Suliann Ben Hamed, Colline Poirier (2025) **_Scientific Reports_**

Despite advancements in video-based behaviour analysis and detection models for various species, existing methods are suboptimal to detect macaques in complex laboratory environments. To address this gap, we present MacqD, a modified Mask R-CNN model incorporating a SWIN transformer backbone for enhanced attention-based feature extraction. MacqD robustly detects macaques in their home-cage under challenging scenarios, including occlusions, glass reflections, and overexposure to light. To evaluate MacqD and compare its performance against pre-existing macaque detection models, we collected and analysed video frames from 20 caged rhesus macaques at Newcastle University, UK. Our results demonstrate MacqD's superiority, achieving a median F1-score of 99% for frames with a single macaque in the focal cage (surpassing the next-best model by 21%) and 90% for frames with two macaques. Generalisation tests on frames from a different set of macaques from the same animal facility yielded median F1-scores of 95% for frames with a single macaque (surpassing the next-best model by 15%) and 81% for frames with two macaques (surpassing the alternative approach by 39% ). Finally, MacqD was applied to videos of paired macaques from another facility and resulted in F1-score of 90%, reflecting its strong generalisation capacity. This study highlights MacqD's effectiveness in accurately detecting macaques across diverse settings.

* [The MacqD deep-learning-based model for automatic detection of socially housed laboratory macaques](https://www.nature.com/articles/s41598-025-95180-x)

* https://github.com/C-Poirier-Lab/MacqD


