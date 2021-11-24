# Style-Transfer-with-GAN

![image](https://user-images.githubusercontent.com/75998991/143183824-214a01c6-61df-46c2-a9d1-788b6601226c.png)

I compared the results by writing models from basic vanilla GAN to cycle GAN and disco GAN.   

![image](https://user-images.githubusercontent.com/75998991/143184603-bd0d1a70-9d18-4805-961a-395e0889f9d8.png)  

Although the performance of the cycle gun was the best, there was a problem that the shape could not be changed well because there was no feature extractor.  
In addition, there was a problem of changing people into zebra due to the problem of datasets. (The absence of a picture of a person riding a zebra.)

![image](https://user-images.githubusercontent.com/75998991/143183632-c9635dcc-eb8e-4b60-8c8a-505f95cb1bf5.png)

 Finally, the performance of the cycle GAN was improved by referring to a paper that solves the problem of not being able to rebuild the shape of the object of the cycle GAN.
