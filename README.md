Masking Approach for Homogeneous Image Plane: In case of Bright Field Microscop

Bright-field microscopy is a crucial technique in
biomedical imaging. Segmenting live cell culture images in bright-
field microscopy presents challenges due to low contrast, uneven
lighting, and noise. The following study introduces a novel and
innovative unsupervised masking technique that segments bright-
field microscopy pictures without the necessity of pre-trained
models or operator annotations. Our approach utilizes statistical
background modeling, spatial statistics (Moran’s I, modified
variogram, Cumulative Squared Shift of Nodal Intensity), fuzzy
inference, and shape analysis to differentiate foreground from
background. In contrast to region-growing approaches, our
methodology does not depend on distance metrics but rather
establishes thresholds adaptively. Comparative assessments of our
algorithm with Cellpose and StarDist on challenging unstained
cell culture images demonstrate that our method yields visually
coherent segmentation. The proposed algorithm has been pre-
sented through a graphical user interface (GUI) and we offer
an expert-driven evaluation to ascertain segmentation quality
and as well as the standard evaluation metrics including Ac-
curacy, Recall, Precision, IoU and F1 score. This paper advances
efficient, training-free segmentation methods, with prospective
developments in instance segmentation.
