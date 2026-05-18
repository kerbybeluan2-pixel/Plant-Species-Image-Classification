# Plant-Species-Image-Classification 
https://drive.google.com/drive/folders/1RrQ6O5Gtvw7vEOna7y_-DDEB9xhxJw5E?usp=drive_link 

**DATA SET SCREENSHOT**
<img width="1899" height="900" alt="image" src="https://github.com/user-attachments/assets/22be2e8a-1c24-4cb4-8936-c9e54dfa39e7" />

**A. Project Overview**

**Brief Description of the Project:**
This project focuses on building an image classification model using Teachable Machine to identify different types of creeper plants. The dataset includes 5,000 images, with 250 images for each plant species.

The images are organized into labeled categories and uploaded to Teachable Machine for training, testing, and validation. The main goal is to create an AI model that can automatically classify creeper plants based on their visual characteristics.

**Purpose of the Image Classification Model:**
The purpose of this model is to provide a fast, reliable, and consistent way to identify creeper plants based on their visual features. By training the model on a balanced dataset with diverse images, it can accurately recognize different plant species in real-world scenarios.


 **B. Plant Species in the Dataset:**

1. Magnolia × soulangeana
![1](https://github.com/user-attachments/assets/7a8e0db1-89db-4d62-8fce-f245590f202b)

**Magnolia × soulangeana** – Commonly known as saucer magnolia, this plant is notable for its large, cup-shaped flowers and broad leaves. It is included in the dataset to help the model recognize flowering patterns, leaf shapes, and seasonal variations.

2. Tabebuia rosea
![2](https://github.com/user-attachments/assets/5f3bcdfd-0695-4b2b-a7f5-e0e635b8e328)

**Tabebuia rosea** – Commonly known as pink trumpet tree or rosy trumpet tree, this plant is distinguished by its vibrant pink to magenta trumpet-shaped flowers and compound leaves. It is included in the dataset to help the model recognize distinctive flower colors, petal structures, and seasonal blooming patterns.

**C. Model Training Details**

<img width="328" height="673" alt="image" src="https://github.com/user-attachments/assets/a9d83a9f-758f-42dd-8305-cfa308739cb6" />
Number of images per class :250

**D. Model Evaluation**

<img width="898" height="885" alt="image" src="https://github.com/user-attachments/assets/8080c060-6429-4d4b-9b91-a7dc8b998d59" />

**E. Model Testing**

<img width="387" height="900" alt="Screenshot 2026-02-16 191113" src="https://github.com/user-attachments/assets/43900bca-8f7b-4bdc-817d-31b6148353d0" />

<img width="380" height="896" alt="Screenshot 2026-02-16 185609" src="https://github.com/user-attachments/assets/b9dc1981-c642-487b-acd6-2f04c7ef9881" />

<img width="379" height="895" alt="Screenshot 2026-02-16 184128" src="https://github.com/user-attachments/assets/4a764def-6845-4c4d-9400-f2191f9a09e5" />

<img width="408" height="904" alt="Screenshot 2026-02-16 182738" src="https://github.com/user-attachments/assets/264d2605-0c6d-4c04-ab0f-132e8fd3737d" />

<img width="385" height="900" alt="Screenshot 2026-02-16 190603" src="https://github.com/user-attachments/assets/c49282e5-6cdd-4224-9692-c013ddc4b549" />

<img width="379" height="900" alt="Screenshot 2026-02-16 185334" src="https://github.com/user-attachments/assets/ff5f8f2e-9058-4cd2-92a7-f75b7c65362e" />

<img width="395" height="901" alt="Screenshot 2026-02-16 183439" src="https://github.com/user-attachments/assets/0ef3449a-a99f-45cc-a671-3685a7bdf3c4" />

<img width="385" height="893" alt="Screenshot 2026-02-16 190434" src="https://github.com/user-attachments/assets/e7e6d05f-0ed5-44cf-a169-430844050ace" />

<img width="385" height="898" alt="Screenshot 2026-02-16 184512" src="https://github.com/user-attachments/assets/014a4e27-d42f-4279-93b5-1c2bd4870217" />

<img width="398" height="896" alt="Screenshot 2026-02-16 182938" src="https://github.com/user-attachments/assets/4915f5f1-2cf3-44ee-9849-cd735bd108ca" />

**Reflection Questions**

**1. How did the number of images per class affect your model's accuracy?****
**Answer:** The number of images per class had a significant impact on the model's accuracy. Having a balanced dataset ensured that the model could learn each class properly, reducing bias and improving overall performance.

**2. Which plant species were most commonly misclassified and why?**
**Answer:** The ivy gourd was most frequently misclassified. This is because its visual features, such as leaf color and shape, are very similar to other creeper plants, making it difficult for the model to distinguish between them.

**3. How did changing the epochs, batch size, or learning rate affect the training results?**
Answer: Adjusting settings like epochs, batch size, and learning rate improved the training results. By fine-tuning these parameters, the model became more likely to classify images correctly.

**4. What challenges did you encounter during dataset collection and labeling?**
Answer: The main challenge was the large number of images. Labeling each image manually was time-consuming and required careful attention to avoid errors.

**5. If you were to improve your model, what specific changes would you make and why?**
**Answer:** I would increase the number of epochs because the current model still misclassifies some images. Training longer could help the model better learn subtle differences between similar creeper plants.
