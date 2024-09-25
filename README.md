# ComplexBased2D-ProteinPatternClassificationBy-ML
In this study, we propose a novel complex-based approach for 2D pattern representation of amino acid sequences. With this approach, 2D images obtained from amino acid sequences of two different protein families are tested on the classification problem with machine learning methods.
## Project title: “COMPLEX-BASED 2D PROTEIN PATTERN IMAGE CLASSIFICATION WITH ML (CNN, RF, SVM).”¶
## DESCRIPTION:
In this study, we propose a novel complex-based approach for 2D representation of amino acid sequences. To investigate the representational power of this new approach, amino acid sequences belonging to kinase and GPCR protein families are converted into 2D images and tested on the protein classification problem using Support Vector Machines (SVM), Random Forests (RF) and Convolutional Neural Networks (DNN).
# THE STUDY PROCEEDS IN THE FOLLOWING STEPS:
## STEP 1 (DATA IMPORT):
Amino acid sequences of kinase and GPCR proteins are imported separately in fasta form from the NCBI gene bank using accession numbers.
Datasets of protein/amino acid sequences are available on GitHub at [29] (at https://github.com/A-Yaku
 poglu/ComplexVsRealANNProteinClassifyGit).
## STEP 2 (DATA PREPROCESSING):
The amino acid sequences of kinase and GPCR proteins are labeled as “1” and “0”, randomly shuffled and saved as a single data frame in fasta form.
## STEP 3 (COMPLEX CODING):
The data frame in fasta form is converted into complex numbers with our proposed Complex Encoding Method and saved as a complex-valued data frame.
## STEP 4 (CONVERSION TO 2D IMAGES):
The amino acid sequences converted into complex numbers are converted into 2D images to create a meaningful and distinct pattern specific to each protein and to be given as input to neural networks. The images are labeled and saved as a new 2D image data frame.
## STEP 5 (CNN-2D PROTEİN CLASSIFICATION):
2D complex image data representing kinase and GPCR proteins are classified using Convolutional Neural networks.
## STEP 6 (SVM-2D PROTEİN CLASSIFICATION):
2D complex image data representing kinase and GPCR proteins are classified using Support vector machines.
## STEP 7 (RF-2D PROTEİN CLASSIFICATION):
2D complex image data representing kinase and GPCR proteins are classified using Random Forest.
