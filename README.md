# pagespeedfr-pagebuilderslider
Magento 2 replace the slide of pagebuilder slider - change background image to img tag.
Also add width, height, lazyload and fetchpriority attribute to the image for google page speed preload possibility.


![image](https://github.com/user-attachments/assets/f2fe7a88-5e66-49be-b9d4-49e6b5e455d5)


🛠 INSTALLATION

Manual Installation

Download and unzip the module in: app/code/Pagespeedfr/PageBuilderSlider/ (Create folders if they don't exist)

With composer : composer require pagespeedfr/lcpimage

Then php bin/magento s:up 

You will see on your slide this option Lcp pagespeed poster (take it and fill page speed attribute)
put in the first slide lazyloading -> eager ;  fetchpriority -> high ; let other slide by default

![image](https://github.com/user-attachments/assets/776f273a-94c2-4f09-93c8-a1ec6af1c6a2)


![image](https://github.com/user-attachments/assets/080f520d-4bce-4a19-acf7-779864b8b54d)


if you want to preload the image see my other module
https://github.com/tweetyx/Pagespeedfr_Lcpimage
