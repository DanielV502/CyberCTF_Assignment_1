# CyberCTF_Assignment_1

### 2. Challenge: File types

* The challenge requests the analysis of a PDF file with issues when trying to open it.
* After analyzing The PDF file, we can confirm that it really was hidden script.

![R1_C2_1](https://user-images.githubusercontent.com/124681007/217531805-ec94141b-52bf-4c11-8e14-135a9307ff91.png)

* The output of the script is a file named “flag”, obtained by decoding text inside the script.
* The file “flag” doesn´t had an extension but we can confirm the file type with de command “File” on the terminal.
* Assigning the correct extension to the files, allow us to extract compressed data from the original file “flag.ar” and other files in it.
* The decoding process and the extraction of compressed data required the installation of additional tools.
* The last file extracted was a plain text with some code that we are able to check with a converter tool.

![R1_C2_2](https://user-images.githubusercontent.com/124681007/217531910-0aa970af-5efc-4b17-a5d4-5d8b8e41c724.png)

![R1_C2_3](https://user-images.githubusercontent.com/124681007/217532027-cd4c1e9b-206b-4320-b85a-25b2174a4d0f.png)


* With a HEX to ASCII conversion tool, I was able to read the flag of the challenge:
> The flag is: “picoCTF{f1len@m3_m@n1pul@t10n_f0r_0b2cur17y_3c79c5ba}”

* In this exercise, the technic of trying to hide something valuable on a file can be categorized as an Obfuscation Attack.
