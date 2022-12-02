# Plant Disease Detection

## Introduction

Getting affected by a disease is very common in plants due to various factors such as fertilizers, cultural practices followed, environmental conditions, etc. These diseases hurt agricultural yield and eventually the economy based on it. 

Any technique or method to overcome this problem and getting a warning before the plants are infected would aid farmers to efficiently cultivate crops or plants, both qualitatively and quantitatively. Thus, disease detection in plants plays a very important role in agriculture.

## The PlantVillage Dataset

We use a publicly available and quite famous, the PlantVillage Dataset. The dataset was published by crowdAI during the ["PlantVillage Disease Classification Challenge"](https://www.crowdai.org/challenges/plantvillage-disease-classification-challenge). 

The dataset consists of about **54,305 images** of plant leaves collected under controlled environmental conditions. The plant images span the following **14 species**:

> **Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.**

The dataset contains a total of **38 classes** of plant disease and **1** class of background images listed below:

1. Apple Scab
2. Apple Black Rot
3. Apple Cedar Rust
4. Apple healthy
5. Blueberry healthy
6. Cherry healthy
7. Cherry Powdery Mildew
8. Corn Gray Leaf Spot
9. Corn Common Rust
10. Corn healthy
11. Corn Northern Leaf Blight
12. Grape Black Rot
13. Grape Black Measles
14. Grape Leaf Blight
15. Grape healthy
16. Orange Huanglongbing
17. Peach Bacterial Spot
18. Peach healthy
19. Bell Pepper Bacterial Spot
20. Bell Pepper healthy
21. Potato Early Blight
22. Potato healthy
23. Potato Late Blight
24. Raspberry healthy
25. Soybean healthy
26. Squash Powdery Mildew
27. Strawberry Healthy
28. Strawberry Leaf Scorch
29. Tomato Bacterial Spot
30. Tomato Early Blight
31. Tomato Late Blight
32. Tomato Leaf Mold
33. Tomato Septoria Leaf Spot
34. Tomato Two Spotted Spider Mite
35. Tomato Target Spot
36. Tomato Mosaic Virus
37. Tomato Yellow Leaf Curl Virus
38. Tomato healthy

Due to the limited computational power, it is difficult to train the classification model locally on a majority of normal machines.

## Streamlit App
I have used an open source app framework Streamlit in Python language. It helps us create web apps for data science and machine learning. 

1. Streamlit app UI: Simple UI created by streamlit where the user can upload files.

<img width="500" alt="Screenshot 2022-12-03 at 1 39 20 AM" src="https://user-images.githubusercontent.com/64124824/205377869-a827cc6d-cd4d-4e71-9a0a-2524bb125c65.png">
2. After Uploading image: ("In this case it was Potato leaf with Early_blight")

<img width="500" alt="Screenshot 2022-12-03 at 1 39 47 AM" src="https://user-images.githubusercontent.com/64124824/205378045-14751864-25d3-4793-9d4a-476b5f01da01.png">

3. Prediction: You can see the results model have predicted below 

<img width="500" alt="Screenshot 2022-12-03 at 1 39 54 AM" src="https://user-images.githubusercontent.com/64124824/205378284-42248b35-a991-48de-b533-a5b91405051c.png">


 
