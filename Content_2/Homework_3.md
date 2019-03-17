<html>
<body>
<p style="text-indent:2em;">  

# 直方图增强

---

# 1. 绘制直方图
<br>  绘制附件图片的直方图得到如下所示结果：</br>
## 1.1 CityWall
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/citywall.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/citywall1.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/citywall2.jpg?raw=True" width="25%" height="25%"/>
</div>
<div align="center"> Figure1.1 Histogram of CityWall </div>

## 1.2 Elain
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/elain.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/elain1.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/elain2.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/elain3.jpg?raw=True" width="20%" height="20%"/>
</div>
<div align="center"> Figure1.2 Histogram of Elain </div>

## 1.3 Lena
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/lena.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/lena1.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/lena2.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/lena4.jpg?raw=True" width="20%" height="20%"/>
</div>
<div align="center"> Figure1.3 Histogram of Lena </div>

## 1.4 Woman
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/woman.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/woman1.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task1/woman2.jpg?raw=True" width="25%" height="25%"/>
</div>
<div align="center"> Figure1.4 Histogram of Woman </div>

<br>  从直方图中可以看到，一组相似图片在直方图上也几乎一样，不过是在原图像的基础上加入了一定的噪声或是在调色板上进行了改动。</br>

# 2. 直方图均衡
<br>  对于离散取值的图片，使用其概率与求和代替处理概率密度与积分，使用直方图均衡对图片进行处理，从结果可以看到进行直方图均衡后的图片，其直方图较为平滑，分布更加均匀。</br>
## 1.1 CityWall
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/citywall.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/citywall1.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/citywall2.jpg?raw=True" width="25%" height="25%"/>
</div>
<div align="center"> Figure2.1 Equalized CityWall </div>

## 1.2 Elain
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/elain.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/elain1.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/elain2.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/elain3.jpg?raw=True" width="20%" height="20%"/>
</div>
<div align="center"> Figure2.2 Equalized Elain </div>

## 1.3 Lena
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/lena.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/lena1.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/lena2.jpg?raw=True" width="20%" height="20%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/lena4.jpg?raw=True" width="20%" height="20%"/>
</div>
<div align="center"> Figure2.3 Equalized Lena </div>

## 1.4 Woman
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/woman.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/woman1.jpg?raw=True" width="25%" height="25%"/>
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task2/woman2.jpg?raw=True" width="25%" height="25%"/>
</div>
<div align="center"> Figure2.4 Equalized Woman </div>

   <br>  从上图中可以很明显的看到进行直方图均衡后的图片清晰度，亮度更好地在直方图上分布而不影响整体的对比度。对于特别明亮的图像降低其亮度，对于特别暗的图像提升其亮度，但是我们可以看到图片中的一些细节没有得到改善，得到改善的仅仅是图片整体的情况，这也和直方图均衡是全局性的图像增强有关，其并没有显示图像细节信息的能力。</br>
   
# 3. 直方图规定化
<br>  直方图规定化在原理上十分简单，而且在连续像素分布时能达到目标图像的直方图，但是在实际中的图像是离散像素分布，从下图中我们就可以看到其表现并不出色。本次直方图规定化选取原图的直方图作为目标直方图，下图中从上到下分别是原图、直方图均衡后的图像、进行规定化后的图像。</br>
## 3.1 CityWall
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task3/citywall2.jpg?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure3.1. Specified CityWall </div>

## 3.2 Elain
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task3/elain2.jpg?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure3.2 Specified Elain </div>

## 3.3 Lena
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task3/lena2.jpg?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure3.3 Specified Lena </div>

## 3.4 Woman
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task3/woman.jpg?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure3.4 Specified Woman </div>

<br>  根据上面的处理结果可以看到，对图像进行直方图规定化并不能很好的实现处理的目标，其与源图像的差距仍然十分明显。但是值得称赞的是，每一个图片都是与源图像存在较大差距的，但是经过直方图规定化后的图像已经相较于处理前十分接近源图像，而存在偏差的原因在于图像的离散性导致不能完全保存源图像信息。</br>

# 4. 局部直方图均衡
   <br>  之前进行的直方图均衡是基于全图信息的，这样的增强很难使图像的局部特征被增强，也就是说这项像素可能会在全局变换中被忽略，因此需要将全局图像划分为局部图像后，再对子图像块进行直方图均衡。在本次作业中使用了7\*7的局部直方图增强方法，对Elain和Lena图像进行处理得到的结果如下所示：</br>
<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task4/elain.bmp?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure4.1 Locally Equalized Elain </div>

<div align="center">
  <img src="https://github.com/James0618/Images/blob/master/Content_2/task4/lena.bmp?raw=True" width="75%" height="75%"/>
</div>
<div align="center"> Figure4.1 Locally Equalized Lena </div>

<br>  从以上局部直方图均衡的结果可以看到，图像的细节部分被突出出来了，但是与此同时也产生了很不舒服的“棋盘”效应，局部与全局之间的权衡是进行直方图均衡的一个难点。</br>




</p>
</body>
</html>
