<h1 align="center">Title: Probability Density Function Learning using GAN</h1>

<h2>1. Methodology</h2>

  Flow of the system:
    
   Data Collection → Data Pre-Processing → Nonlinear Transformation → GAN Training → PDF Estimation → Result Analysis
    
   Explanation of Steps
    
   Data Collection:
    
   NO₂ air pollution dataset
    
   Data Pre-Processing:
    
   Remove missing values and standardize data
    
   Nonlinear Transformation:
    
   𝑧 = 𝑥 + 𝑎sin(𝑏𝑥)
    
   z = x + asin(bx)
    
   GAN Training:
    
   Generator produces synthetic samples while the Discriminator classifies real vs fake.
    
   PDF Estimation:
    
   Kernel Density Estimation (KDE) is applied to generated samples.
    
   Result Analysis:
    
   Compare real distribution and GAN-learned distribution.

<h2>2. Result Table</h2>

 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/91ba4443-4277-4611-9ae6-4c47c15738df" />




<h2>3.Result Graph</h2>
    
   <img width="655" height="385" alt="image" src="https://github.com/user-attachments/assets/0267c5e9-453b-416e-b0f5-2160a6abae54" />


   
    

