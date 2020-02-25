---
title: "Using transfer learning to detect illnesses in the brain"
excerpt: "Developed transfer learning models to detect tumours in 3D images of the brain. <br/> <img src='/images/projects/mri_transfer/mri_project.png' alt='Brain registration, skullstripping, VAE autoencoder' style='width:60%;border-radius:2%;' > "
collection: projects
---

In this research project, I developed transfer learning models to detect tumours in 3D images of the brain. I designed and 
implemented a series of convolutional neural networks for image classification, comparing the models between each other to determine 
 which performed best. One of these networks included a stacked convolutional autoencoder pre-trained entirely on a larger Alzheimer’s 
patient MRI dataset before transfer learning was applied to detect tumours in a separate brain image dataset.

Used Python with pytorch to both develop and analyse the performance of each network to determine which worked best. tcsh was used 
extensively throughout the project for both the pre-processing, alongside another intern, and the parsing of large amounts of data as 
well as the training of the networks on an external computer cluster. Prior to and throughout the internship, I was required to research 
both the statistical theory behind machine learning and the state of current research on transfer learning specifically. A thorough 
understanding of object-oriented design was important to produce software that could be easily modified and extended in the future.

See the project [here](https://github.com/dominicwllmsn/MRI_transferlearn).

<img src="/images/projects/mri_transfer/itk_snap_multi.png" alt="Pleased" style="border-radius:2%;width:80%;align:center;" />

*ITK-Snap MRI viewer used in the project for preprocessing/checking file integrity*