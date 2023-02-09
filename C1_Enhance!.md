# CyberCTF_Assignment_1

### 1. Challenge: Enhance! (Easy)

* The SGV file contains code to draw a white background, black circle with a white dot in the middle.

![R1_1](https://user-images.githubusercontent.com/124681007/217520817-6c6965f7-2ef6-46d2-aae4-f82d34da4c13.png)

* The first attempt was just by analyzing the image, select everything, zoom in/out, and I didn´t came with a result more than a little dot in the middle of the image.
*The next step was to look at the code in the file, and there was an area defining text on the image. There was a message on the image but with a small font in the center of the image.

	* **The same result could be obtained by just select everything on the web page, copy and paste on a notepad as:**

		* **“p i c o C T F { 3 n h 4 n c 3 d _ a a b 7 2 9 d d }”**

* As the name of the Challenge, I changed a little bit of the code to enhance the size of the letters and de display arrangement with the next result:

![R1_2](https://user-images.githubusercontent.com/124681007/217520908-57c83795-f9a7-457d-8157-2860eef446c2.png)

* With that change, I was able to read the flag of the challenge:
> The flag is: **“picoCTF{3nh4nc3d_aab729dd}”**

* In this exercise, the technic of trying to hide something valuable on an image can be categorized as a Steganography Attack, which can be a form of an Obfuscation Attack.
