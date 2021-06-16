# Detection of Plant Disease

![Plant Image](https://cdn-images-1.medium.com/max/1200/1*FswlF4lZPQ4kT_gkybacZw.jpeg)

## Introduction :

Now-a-days due to changes in the environmental conditions, plants are being affected which results in the decrease in the yield. Some of the reasons where plants are affected is over usage of fertilizers, pesticides etc., This may reduce the agricultural yield and eventually the economy based on it. 

A sign of plant disease is physical evidence of the pathogen. A symptom of plant disease is a visible effect of disease on the plant. Symptoms may include a detectable change in color, shape or function of the plant as it responds to the pathogen. Leaf wilting is a typical symptom, caused by the fungal plant pathogens. Common bacterial blight symptoms include brown, necrotic lesions surrounded by a bright yellow halo at the leaf margin or interior of the leaf on bean plants. You are not actually seeing the disease pathogen, but rather a symptom that is being caused by the pathogen.

Any technique or method to overcome this problem and getting a warning before the plants are infected would aid farmers to efficiently cultivate crops or plants, both qualitatively and quantitatively. Thus, disease detection in plants plays a very important role in agriculture.

Finally, farmers will be benificial in detecting whether the crop is effected by any disease or not and can hope for the best regarding the crop yeild.

## The PlantVillage Dataset :

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

Due to the limited computational power, it is difficult to train the classification model locally on a majority of normal machines. Therefore, we use the processing power offered by Google Colab notebook as it connects us to a free TPU instance quickly and effortlessly.

## Mean F1 Score Calulation : 

The F1 score is computed separately for all classes using :

<h4><b>F1 = 2*(pr) / (P + R)</b></h4>
<h4><b>P = tp / (tp + fp)</b></h4>
<h4><b>R = tp / (tp + fn)</b></h4>

<ul> <li> P refers to the precision</li>
<li> R refers to the recall</li>
<li> tp refers to the number of True Positives</li>
<li> fp refers to the number of False Positives</li>
<li> fn refers to the number of False Negatives</li>
</ul>
 
Then finally the Mean of all the F1 scores across all the classes is used for come up with the combined Mean F1 score.


## Some Useful Links :

1. The PlantVillage dataset paper can be found [here](https://arxiv.org/abs/1511.08060).


## Project Admin👨‍:

<p align="center">
<img width=20% src="https://avatars.githubusercontent.com/u/72383661?v=4">
</p>
<a href="https://www.linkedin.com/in/kashishag19/">
<h5 align="center"><b>Kashish Agarwal</b></a>

## License 

<p align="center">
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/blob/main/LICENSE">
<img width=35% src="https://media.tenor.com/images/68ecdcb63296f1db6532bf5b83051da9/tenor.gif"></p>
<h5 align = "center"><b>MIT License</b></a> 