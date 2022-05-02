# Knee Tear Detection using MRNet with Neural Networks

A model to detect Knee Tears trying to eliminate the step of Doctor's examination of the MRI scan results with MRNet data, a set of 3D tesor data with the help of 3D Convolutional Layers followed by the Convolutional Layers of ResNet50 to extract the features and one hidden Fully Connected Layer and one Output Layer.

Achieved ~95% of Training Accuracy and ~90% Testing Accuracy.

*From https://stanfordmlgroup.github.io/competitions/mrnet/*

### About Dataset

The MRNet dataset consists of 1,370 knee MRI exams performed at Stanford University Medical Center. The dataset contains 1,104 (80.6%) abnormal exams, with 319 (23.3%) ACL tears and 508 (37.1%) meniscal tears; labels were obtained through manual extraction from clinical reports. The dataset accompanies the publication of the MRNet work here.


### Dataset Details

The most common indications for the knee MRI examinations in this study included acute and chronic pain, follow-up or preoperative evaluation, injury/trauma. Examinations were performed with GE scanners (GE Discovery, GE Healthcare, Waukesha, WI) with standard knee MRI coil and a routine non-contrast knee MRI protocol that included the following sequences: coronal T1 weighted, coronal T2 with fat saturation, sagittal proton density (PD) weighted, sagittal T2 with fat saturation, and axial PD weighted with fat saturation. A total of 775 (56.6%) examinations used a 3.0-T magnetic field; the remaining used a 1.5-T magnetic field.
