# Wanna_some_cartoonize

My ChatGPT had given me code for cartoonizing.
You can check the code below.
![image](https://user-images.githubusercontent.com/128031528/227484652-4a32f893-e0aa-4fa1-a511-91a21e1c8718.png)
▲ ChatGPT's code for cartoonizing

And then,
I have tried to surpass code made by ChatGPT.
Totally, I made code for cartoonizing image. but I wonder if this code is better or not. 

Anyway, let's dig in code description.

[Code flow]
1. load input image
2. duplicate the image in grayscale
3. extract edges by using both Sobel filter and Gradient filter
4. then, combine gradient edge with image first
5. blur the intermediate image
6. combine Sobel filter with the image
7. make plot for cartoonized image as well as original one.
8. done!

![image](https://user-images.githubusercontent.com/128031528/227486340-662855ae-b3c6-4263-b2e6-dd27a79e8925.png)
▲ My Output 

![image](https://user-images.githubusercontent.com/128031528/227487030-03e6cf69-9f8e-49c4-bd9b-9e7a3a8ba329.png)
▲ ChatGPT's Output
