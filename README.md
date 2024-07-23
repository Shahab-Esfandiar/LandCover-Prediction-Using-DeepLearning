# Land Cover Change Prediction Using Deep Learning

![df6e7000-0400-11eb-8adb-d170335df985](https://github.com/user-attachments/assets/d9fdf08a-a2fe-4f86-81c8-8f7dbe4a9a9a)

## Introduction

*Predicting land cover change using deep learning leverages advanced machine learning algorithms to forecast and analyze changes in land cover patterns. **Land cover** refers to the physical and biological features of the Earth's surface, including forests, farms, docks, residential areas, and other natural and artificial elements. These patterns are crucial for ecological studies, urban planning, resource management, and climate change analysis.*

*Deep learning algorithms are trained using historical land cover data, satellite images, and geographical information to predict future changes. By analyzing relationships between land cover patterns and external factors such as urbanization, population growth, and climate change, these models generate accurate predictions. The ability to manage complex datasets allows deep learning models to uncover patterns that traditional methods might miss, aiding in better decision-making and sustainable development.*

---

## Project Objective
![model_diagram_](https://github.com/user-attachments/assets/e6bac037-04e7-47cc-9f84-763fbe8b50fa)

*The objective of this project is to develop a deep learning model that can predict land cover maps for future years using **historical land cover** data and **population data**. To achieve this goal, a hybrid architecture of `CNN` and recurrent networks `(GRU, LSTM, RNN)` is proposed.*

---

## Study Area
![British-Columbia-map-MAP-locator-cities-CORE](https://github.com/user-attachments/assets/50000afd-2999-4e13-a74f-95343043dc26)


*The study area for this project is the province of **British Columbia in Canada**, covering 30% of the province's area. According to provincial reports, population growth in these areas has been the main driver of land cover changes.*

---

## Data Used
![Screenshot 2024-07-22 173828](https://github.com/user-attachments/assets/2ebae469-8005-482d-bcc0-a730405b2d6a)

- **Land Cover Data** : *Spatial resolution of __30 meters__ and __annual__ temporal resolution.*
- **Population Density Data** : *Spatial resolution of 1 kilometer and temporal resolution of __five years__.*

---

## Model Evaluation Criteria
*For this project, we considered the criteria used to determine **classification** accuracy, and the results are as follows :*

- **Confusion Matrix**
  
![Screenshot 2024-07-22 175851](https://github.com/user-attachments/assets/0d8f6beb-1efc-45c8-9049-ffa7e451ec32)

  
- **F1 Score = %46**
- **Precision = %45**
- **Recall = %46**
- **jac_distance = -0.3056**

---

![Screenshot 2024-07-22 180112](https://github.com/user-attachments/assets/884369d7-c6a2-4a8c-a93e-4b627d6f0ec7)

*Due to the **large volume** of data, we selected a small portion of it and performed the necessary processing. The model was then trained for **20 epochs**. Since complex features needed to be learned in this project, this number of epochs and the data volume did not yield accurate results.* 
*If we can train the entire dataset using a powerful hardware system and sufficient time, and increase the number of epochs to 100, the model’s prediction accuracy could be satisfactory And to prevent the model’s **bias** towards a specific class that has been more prevalent in the selected data.*
