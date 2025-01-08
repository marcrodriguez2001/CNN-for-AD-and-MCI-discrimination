# CNN-for-AD-and-MCI-discrimination
I developed a Convolutional Neural Network (CNN) binary classifier to differentiate between Alzheimer's Disease (AD) and Mild Cognitive Impairment (MCI) using imaging data provided by the Alzheimer's Disease Neuroimaging Initiative (ADNI) through a formal data request approved for research purposes. MCI represents the transitional stage between age-related memory decline and more severe forms of dementia. Accurate distinction between MCI and AD is critical, as the treatment strategies for each condition differ significantly.

In the file *"Presentation_AD_MCI_CNN.pdf"* contains a summary presentation of the project, including its objectives, methodology, and the outcomes and results.

The files *"AD_images.ipynb"* and *"MCI_images.ipynb"* handle the preprocessing of images. They extract images from their respective folders, which are in .dcm (DICOM format), and convert them into matrices and PNG images for further analysis.

Finally, the file *"CNN-to-discriminate-AD-and-MCI.ipynb"* contains the CNN binary classifier model for distinguishing AD from MCI, along with the results of the model's performance.
