# final term project

b09502140 康軒愷

the HR diagram of M22 

### **Title:**

- M22 global cluster observation data

### **1. Introduction:**

- It seems that stars are usually born in big groups, as members of a **cluster** of stars. All the stars in the cluster form at about the same time. So, if we look at a cluster, we see a bunch of stars which are all roughly the same age. However, the stars do not all have the same mass: most tend to have masses less than the Sun's, but a few may be much more massive.
- Concentrate on clusters is the simple fact that all the stars are very nearly the same distance away from us. That means that their *apparent* brightness (or magnitude) is almost as good as their *absolute* brightness (or magnitude). That is, the stars in the cluster which appear to be brightest are really the most powerful; the stars in the cluster which appear to be dimmest are really emitting the least radiation. The difference between the apparent magnitude and the absolute magnitude, the so-called **distance modulus**, is the same for all the stars in the cluster. This means we can very easily compare the *observed* HR diagram of a cluster to a *theoretical* HR diagram, based on stellar models.

### **2. Data and Observations:**

- M22 (globular cluster):

[https://drive.google.com/drive/folders/13tfq14Mex32Zi7zVyIM53ySCe0kRCE_e?usp=sharing](https://drive.google.com/drive/folders/13tfq14Mex32Zi7zVyIM53ySCe0kRCE_e?usp=sharing)

- bias and darks

[https://drive.google.com/drive/folders/1lNNe-QgR1Rjv-h5MaYhAeWs-7gfazdxW?usp=sharing](https://drive.google.com/drive/folders/1lNNe-QgR1Rjv-h5MaYhAeWs-7gfazdxW?usp=sharing)

- observation log
    
    ![M22_Observing_Log.jpg](final%20term%20project%207a7a2fc5993a412b8b9bdbb3c1ccf263/M22_Observing_Log.jpg)
    
- data process tools
    - calibration :python
    - stack: siril
    - Apass data:[https://www.aavso.org/download-apass-data](https://www.aavso.org/download-apass-data)
    - SExtractor
- 

### **3. Data Processing:**

![截圖 2023-12-26 上午7.18.29.png](final%20term%20project%207a7a2fc5993a412b8b9bdbb3c1ccf263/%25E6%2588%25AA%25E5%259C%2596_2023-12-26_%25E4%25B8%258A%25E5%258D%25887.18.29.png)

- Include details on data cleaning, color index calculation, and any corrections applied (e.g., apparent magnitude to absolute magnitude).
- Master bias (-15degree,-10degree)


### **4. HR Diagram Construction:**

- Present the steps involved in creating the B-V to V HR diagram.
    
    ![M22_HRD.png](final%20term%20project%207a7a2fc5993a412b8b9bdbb3c1ccf263/M22_HRD.png)
    
- we can find a turnover (1.05,17)
    
    ![M22_HRD拷貝.png](final%20term%20project%207a7a2fc5993a412b8b9bdbb3c1ccf263/M22_HRD%25E6%258B%25B7%25E8%25B2%259D.png)
    

 **script:**

- https://github.com/kkai0414/HRD-for-global-cluster-M22-observational-data

###