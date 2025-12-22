EyeDiagnosis-System


This project is a complete eye disease identification system using a CNN-based machine learning model. It can detect five major eye diseases from images and provides recommended doctors for treatment, helping patients get proper care quickly and efficiently.

Problem
Many people struggle to identify which eye disease they have just by observing symptoms. Visiting multiple doctors to get a diagnosis can be time-consuming, stressful, and costly. Choosing the wrong doctor can delay treatment and worsen the condition.  

Solution
This project provides an automated solution:  
- The CNN model analyzes eye images and identifies the disease accurately.  
- Based on the prediction, the system recommends suitable doctors considering their experience, specialization, and fees.  
- This approach saves time, guides patients to the right doctor, and supports better treatment planning.  

Diseases Identified
The model can identify the following eye diseases:  
1. Cataracts  
2. Crossed Eye  
3. Glaucoma  
4. Uveitis  
5. Diabatic Ratinopathy



 How It Works
- CNN (Convolutional Neural Networks) are used because they are excellent for image identification, automatically extracting features like edges, shapes, and textures.  
- The model compares the input image with the available dataset to predict the disease.  
- After prediction, the system recommends the best doctors to treat the disease properly.  

 Dataset
The dataset used is from Kaggle ["gunavenkatdoddi/eye-diseases-classification"]
 and includes labeled images for each disease.  

 Features
- Automatic disease identification from eye images  
- Doctor recommendation based on experience, specialization, and fees  
- Quick and accurate diagnosis support  
- Reduces patient effort and treatment delay  

Future Enhancements
- Integration of treatment support: hotel stay, food, medicine, and pharmacy options  
- Support for international treatment and advanced operations  
- Enhanced prediction accuracy with larger datasets  

 How to Use
1. Open the notebook "EyeDisease.ipynb" in Google Colab.  
2. Run the cells step by step to identify eye diseases.  
3. See the recommended doctors for each predicted disease.


Created by: Prajjval Pawar | B.tec CSE, 2026
