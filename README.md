
# Detection of Plant Disease

<div align="center">

<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/badge/Built%20by-developers%20%3C%2F%3E-0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=yellow"></a>
<a href="https://github.com/kashish-ag/"><img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg?v=103"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease"><img src="https://img.shields.io/badge/PR's%3F-Welcomed-brightgreen.svg?v=103"></a>

<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/watchers"><img src="https://img.shields.io/github/watchers/kashish-ag/Detection-of-Plant-Disease?style=flat"></a> 
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/graphs/contributors"><img src="https://img.shields.io/github/contributors/kashish-ag/Detection-of-Plant-Disease?color=brightgreen"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/stargazers"><img src="https://img.shields.io/github/stars/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/network/members"><img src="https://img.shields.io/github/forks/kashish-ag/Detection-of-Plant-Disease?color=yellow"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/issues"><img src="https://img.shields.io/github/issues/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/issues?q=is%3Aissue+is%3Aclosed"><img src="https://img.shields.io/github/issues-closed-raw/kashish-ag/Detection-of-Plant-Disease?color=yellow"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/pulls"><img src="https://img.shields.io/github/issues-pr/kashish-ag/Detection-of-Plant-Disease?color=brightgreen"></a>
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/pulls?q=is%3Apr+is%3Aclosed"><img src="https://img.shields.io/github/issues-pr-closed-raw/kashish-ag/Detection-of-Plant-Disease?color=0059b3"></a> 
</div>
<p align=center>
<img src="https://user-images.githubusercontent.com/74819092/124498690-63afb280-ddda-11eb-8a50-10ec7d46db44.png" hieght=400, width=400>
</p>

## Introduction

Getting affected by a disease is very common in plants due to various factors such as fertilizers, cultural practices followed, environmental conditions, etc. These diseases hurt agricultural yield and eventually the economy based on it. 

Any technique or method to overcome this problem and getting a warning before the plants are infected would aid farmers to efficiently cultivate crops or plants, both qualitatively and quantitatively. Thus, disease detection in plants plays a very important role in agriculture.

## The PlantVillage Dataset

We use a publicly available and quite famous, the PlantVillage Dataset. The dataset was published by crowdAI during the ["PlantVillage Disease Classification Challenge"](https://www.crowdai.org/challenges/plantvillage-disease-classification-challenge). 

The dataset consists of about **54,305 images** of plant leaves collected under controlled environmental conditions. The plant images span the following **14 species**:

> **Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.**

The dataset contains a total of **38 classes** of plant disease and **1** class of background images listed below:
|                     |                      |                        |                          | 
| :---:               |    :----:            |          :---:         |         :---:            |  
| Apple Scab          | Apple Black Rot      | Apple Cedar Rust       | Apple Healthy            |
| Blueberry Healthy   | Cherry Healthy       | Cherry Powdery Mildew  | Corn Northern Leaf Blight|
|Corn Gray Leaf Spot  |Corn Common Rust      |Corn healthy            | Grape Black Rot          |     
|Grape Black Measles  | Grape Leaf Blight    | Grape Healthy          | Bell Pepper Healthy      |
| Orange Huanglongbing|Peach Bacterial Spot  | Peach Healthy          |Bell Pepper Bacterial Spot|
| Potato Early Blight | Potato Healthy       | Potato Late Blight     |Raspberry Healthy         |
| Soybean Healthy     | Squash Powdery Mildew| Strawberry Healthy     | Strawberry Leaf Scorch   |
|Tomato Bacterial Spot| Tomato Early Blight  | Tomato Late Blight     |Tomato Leaf Mold          |
|Tomato Septoria Leaf Spot| Tomato Two Spotted Spider Mite | Tomato Target Spot |Tomato Mosaic Virus |
|Tomato Yellow Leaf Curl Virus | Tomato Healthy      |    |    |


Due to the limited computational power, it is difficult to train the classification model locally on a majority of normal machines. Therefore, we use the processing power offered by Google Colab notebook as it connects us to a free TPU instance quickly and effortlessly.

## 💻Tech Stacks
</br>
<p>
<img alt="Jupyter" src="https://img.shields.io/badge/jupyter%20-%23323330.svg?&style=for-the-badge&logo=jupyter&logoColor=orange"/>
<img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>
<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23323330.svg?&style=for-the-badge&logo=html5&logoColor=red"/>     
</p>
</br>

## Contributing Guidelines 👷

* <a href="#" target="_self" title="Fork">Fork</a> the project.
![image](https://user-images.githubusercontent.com/74819092/124501837-e71fd280-dddf-11eb-89b2-b58612d9a1dc.png)

* Create your Feature Branch
```bash
git checkout -b '<your_branch_name>'
```  
### or 
![image](https://user-images.githubusercontent.com/74819092/124501937-1cc4bb80-dde0-11eb-93a0-dbf5e9a71626.png)

* Stage your changes
```bash
git add .
```
* Commit your changes
```bash
git commit -m '<your_commit_message>'
```
* Check for Status to be sure everything is added
```bash
git status
```
* Check for your remote
```bash
git remote -v
```
* Push changes to remote
```bash
git push origin '<your_branch_name>'
```
* Open a <a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/pulls" title="Create Pull request">Pull Request</a>

<br>

## 📌 Opensource Programs

### This project is a part of following Open Source Program
<br>

<table style="width:80%;background-color:white;border-radius:30px;">
    <tr>
  <td>
<center>
  <a href="https://letsgrowmore.in/projects/"><img src="https://letsgrowmore.in/wp-content/uploads/2021/05/cropped-growmore-removebg-preview.png"></img></a>
  </center>
  </td>
  </tr>
</table>
    <hr>

## Useful Links

1. The PlantVillage dataset paper can be found [here](https://arxiv.org/abs/1511.08060).


<hr>

<br>

## Project Admin👨‍:


<p align="center">
<a href="https://github.com/kashish-ag"><img src="https://avatars.githubusercontent.com/u/72383661?v=4" width=150px height=150px /></a></br> 
<p align="center">
  <a target="_blank"href="https://www.linkedin.com/in/kashishag19/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;


<hr>

## ✨Our valuable Contributors :
<br>

<table >
	<tr>
		<td >
			<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kashish-ag/Detection-of-Plant-Disease" />
</a>
		</td>
	</tr>
</table>

<hr>


## License:

<p align="center">
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/blob/main/LICENSE">
<img width=35% src="https://media.tenor.com/images/68ecdcb63296f1db6532bf5b83051da9/tenor.gif"></p>
<h5 align="center"><b>MIT License</b></a> 

<br>

## 📜 Code Of Conduct:
<p align="center">
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease/blob/main/CODE_OF_CONDUCT.md">
<img width=35% src="https://c.tenor.com/xeHd9DDYS1cAAAAM/jack-nicholson-who-cares.gif"></p>
<h5 align="center"><b>Click to read</b></a>  

<!-- You can find our Code of Conduct [here](https://github.com/kashish-ag/Detection-of-Plant-Disease/blob/main/CODE_OF_CONDUCT.md). -->

 <hr>

 <p align="center">
<a href="https://github.com/kashish-ag/Detection-of-Plant-Disease" title="Woodog Github">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
    
</a>
</p>
