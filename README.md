# MRI-image-translation-T1-to-T2-using-cyclegan   
Magnetic resonance imaging (MRI) is one of the most commonly used tests in neurology and neurosurgery. MRI provides exquisite detail of brain, spinal cord and vascular anatomy, and has the advantage of being able to visualize anatomy in all three planes: axial, sagittal and coronal.   
The most common MRI sequences are T1-weighted and T2-weighted scans. In T1 weighted images, contrast and brightness of the image are predominately determined by T1 properties of tissue. In T2 weighted images, the contrast and brightness are predominately determined by the T2 properties of tissue.  
On T1 images FAT is white. On T2 images both FAT and WATER are white.  Here is the sample of T1 and T2 weighted image: 
![alt text](https://www.startradiology.com/uploads/images/english-class-mri-technique-fig15-example-t1-t2-tumor-blanco.jpg)  
Both these contrast helps radiologist to conclude about malfunctions in scanned image with confidence. But the process of getting both contrasts is quite exhaustive and requires time. So, with the help of deep learning would try to produce alternate contrast if one is given.  
Using [CycleGAN](https://arxiv.org/abs/1703.10593) a variant of GAN is used. CycleGAN does not require paired dataset to translate image from one domain to another. 
