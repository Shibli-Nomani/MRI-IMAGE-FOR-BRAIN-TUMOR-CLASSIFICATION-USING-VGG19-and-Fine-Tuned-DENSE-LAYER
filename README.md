# 🐲 MRI IMAGE FOR BRAIN TUMOR CLASSIFICATION USING VGG19 and Fine Tuned DENSE LAYER
![vgg19model](https://github.com/Shibli-Nomani/MRI-IMAGE-FOR-BRAIN-TUMOR-CLASSIFICATION-USING-VGG19-and-Fine-Tuned-DENSE-LAYER/assets/101654553/5755dbe2-e752-4985-982e-f5b0bef936ef)

# 👇 Kaggle Link :
https://www.kaggle.com/code/shiblinomani/mri-of-brain-tumor-classification-using-vgg19#%F0%9F%98%B2-MODEL-PREDICTION-WITH-VALIDATION(UNSEEN-DATA)

# 😉 About Dataset
https://www.kaggle.com/datasets/iashiqul/mri-image-based-brain-tumor-classification

What is an MRI Image?
MRI (Magnetic Resonance Imaging) produces detailed images of the brain's internal structures using magnetic fields and radio waves.

**Importance of Brain Tumor Classification**
Analyzing MRI images helps categorize different brain tumors, aiding in:

1. Early detection and diagnosis.

2. Tailoring effective treatment plans.

3. Monitoring tumor progression.

**Dataset Details**
Training Dataset: **`[TREAT AS TRAINING IMAGE DATA FOR MODEL TRAINING]`**
* Glioma: 1321 files
* Meningioma: 1339 files
* No Tumor: 1595 files
* Pituitary: 1457 files

Testing Dataset: **`[TREAT AS VALIDATION IMAGE DATA DURING MODEL TRAINING]`**
* Glioma: 300 files
* Meningioma: 306 files
* No Tumor: 405 files
* Pituitary: 300 files

Validation Dataset: **`[TREAT AS UNSEEN IMAGE DATA FOR MODEL TESTING]`**
* Glioma: 175 files
* Meningioma: 139 files
* No Tumor: 162 files
* Pituitary: 179 files

The dataset contains MRI images of various brain tumors, aiming to train models to accurately classify these images, aiding in automated tumor detection and patient care.



# 😂 SUMMARY
The model is based on the VGG19 architecture pre-trained on ImageNet, with additional dense layers fine-tuned for a specific task. With a remarkable training accuracy of 99.905% and a negligible training loss of 0.004%, the model exhibits a high capacity to learn intricate patterns within the training data. During validation, the model achieves an accuracy of 99.314% and low loss of 0.035.

Upon evaluating the model's performance on test images, it achieves an accuracy of 99.6947%, showcasing its reliability and consistency across new, unseen data. The addition of dense layers, batch normalization, and dropout mechanisms further enhances the model's capability to generalize and avoid overfitting.

🎉 Overall, the model demonstrates performance across training, validation, and test datasets, showcasing its high accuracy and minimal loss. However, future improvements could involve exploring different architectures or hyperparameter tuning to potentially extract more intricate features or improve computational efficiency, aiming for even greater performance.

"Thrilled to share the incredible performance of my model! With a staggering accuracy of [99.6947%], it showcases exceptional learning prowess. 🚀 Curious minds, what do you think? Your insights could fuel its journey to even greater heights! #AI #MachineLearning #FeedbackWelcome" 🌟✨


## Authors

- [@LinkedIn Khan MD Shibli Nomani](https://www.linkedin.com/in/khan-md-shibli-nomani-45445612b/)


