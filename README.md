## Project title: “COMPARISON OF COMPLEX CONVOLUTIONAL NEURAL NETWORKS, REAL CONVOLUTIONAL NEURAL NETWORKS, SVM AND RF METHODS FOR COMPLEX-BASED 2D PROTEIN PATTERN IMAGE CLASSIFICATION.
#### DESCRIPTION
In this study, we propose a new complex-based approach for 2D representation of amino acid sequences. To investigate the representativeness of this new approach, amino acid sequences of kinase and GPCR protein families are converted into 2D images. These 2D protein images are classified using Real-valued Convolutional Neural Networks, Complex-valued Convolutional Neural Networks, Support Vector Machines and Random Forest machine learning methods. The results are compared statistically.
## THE STUDY PROCEEDS IN THE FOLLOWING STEPS
##### STEP 1 (DATA IMPORT)
Amino acid sequences of kinase and GPCR proteins are imported from the NCBI gene bank in separate fasta form using accession numbers. 
##### STEP 2 (DATA PREPROCESSING)
Amino acid sequences of kinase and GPCR proteins are labeled as “1” and “0”, randomly shuffled and saved as a single data frame in fasta format.
##### STEP 3 (COMPLEX CODING)
The data frame in fasta format is converted to complex numbers by the proposed 2D Complex Coding Method and saved as a complex-valued data frame.
##### STEP 4 (CONVERSION TO 2B IMAGES)
The amino acid sequences converted into complex numbers are converted into 2D images to form a meaningful and distinct pattern unique to each protein and given as input to neural networks. The images are labeled and saved as a new 2D image data frame.
##### STEP 5 (2D PROTEIN CLASSIFICATION with Reel-CNN)
2D complex image data representing kinase and GPCR proteins are classified using Reel-Valued Convolutional Neural Networks. 
##### STEP 6 (2D PROTEIN CLASSIFICATION with Complex Valued-CNN)
2D complex image data representing kinase and GPCR proteins are classified using Complex-Valued Convolutional Neural Networks.
##### STEP 7 (2D PROTEIN CLASSIFICATION with SVM)
2D complex image data representing kinase and GPCR proteins are classified using Support Vector Machines (SVM).
##### STEP 8 (2D PROTEIN CLASSIFICATION with RF)
2D complex image data representing kinase and GPCR proteins are classified using Random Forest (RF).
##### STEP 9 STATISTICAL ANALYSIS
The means and standard deviations of the metric results obtained by running the networks of each machine learning method 10 times are calculated. It is investigated whether there is a statistically significant difference between them.
###### Technical and Development Notes:
The applications of the study were carried out using the Python programming language in the Jupyter Notebook environment. During the code development process, deep learning libraries and code repositories such as Keras and TensorFlow were utilized. In the debugging and compilation stages of the developed code, the generative artificial intelligence tool ChatGPT-4o (version: 2024-05-13) was used solely for technical support purposes and within the framework of limited and full scientific responsibility principles, with its accuracy verified.
