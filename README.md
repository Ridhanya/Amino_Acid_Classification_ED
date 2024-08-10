<h1 (or 2 etc.) align="center">Automating the Amino Acid Identification in Elliptical Dichroism (ED) Spectrometer With Machine Learning (ML)</h1>

This repository contains the codes used to acquire results for the amino acid classification problem using the absorption profiles from the ED Spectrometer with ML. The details of what each folder contains is as follows:

1. Alanine_Arginine_Classification - It contains the code, data and model files associated with ML classification of L-Alanine and L-Arginine
2. Alanine_Arginine_Lysine_Classification - It contains the code, data and model files associated with classification of L-Alanine, L-Arginine and L-Lysine
3. All_Amino_Acid_Classification - It contains the code, data and model files associated with classification of 17 amino acid categories (these categories are specified in the paper).
4. Data_Preprocessing - It contains the data (before and after preprocessing) and codes used to preprocess the data obtained from the ED spectrometer. This preprocessed data was then used to investigate ML approaches.
5. Transfer_Learning_Approach - It contains the code, data and model files associated with classification of L-Alanine, L-Arginine and L-Lysine using a transfer learning approach where the model trained on the classification of L-Arginine and L-Alanine was freezed and only the final layer was trained to classify L-Lysine effectively.

Each of these folders also contains a readme of its own where the details of individual files in each of these folders are briefly explained. Please note that the paths to the data and models are not relative but absolute and might need to be edited to make them work in your respective environments. Jupyter Notebook needs to be set up along with Tensorflow 2.11.1 (or any version >=2.0), and other necessary Python libraries have to be installed to make these codes work.
