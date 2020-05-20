# DTICryptotanshinone
Drug Target interaction prediction for osteosarcoma

Using the code in https://github.com/luoyunan/DTINet as a reference, I have tried to use DTINet to identify the target of a herbal drug.

The details and references can be found in the RSaraf_Report.pdf and the presentation can be used as a reference to understand the gist of this project.

This is a course project for ECEN 766. It is still in it's initial stages.

1. Add relevant data about the drugs and proteins in the folder : data
2. Create a new folder : network
3. Run compute_similarity.m in the folder : src
4. Use run_DCA.m to calculate feature vectors for drugs and proteins
5. Use requirements.txt to set up the Python environment (>= 2.7)
6. Install _train_mf as a function from leml-imf-src.zip using the instructions as given
7. Run IMC.ipynb to generate interaction.txt
8. Run Predicted_Interaction.ipynb to find the targets of the drug of interest
