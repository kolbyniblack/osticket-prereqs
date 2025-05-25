<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<!-- --------------------------------------------------------- LIST-OF-PREREQUISITES-OPEN ------------------------------------------------------------------------------------------------------------- -->


<h2>List of Prerequisites</h2> 

<ul>
<li>1) Install / Enable IIS in Windows WITH CGI </li>

<li> 2) Install osTicket Files </li>


<li>3) Register PHP from within IIS </li>

<li>4) Enable osTicket Extensions</li>

<li>5) install HeidiSQL </li>
</ul>

<!-- --------------------------------------------------------- LIST-OF-PREREQUISITES-CLOSE ------------------------------------------------------------------------------------------------------------- -->

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- --------------------------------------------------------- Install / Enable IIS in Windows WITH CGI - OPEN --------------------------------------------------------------------------------------------  -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<h1>(1)Install / Enable IIS in Windows WITH CGI</h1>


 In the Windows desktop search bar, look up <b>"Control Panel"</b> - The window seen in the image below will open <br /> Next -> <b>Follow the images with their corresponding letter(s) below</b>

<p> 
(A) Once this window appears, make sure you double-click on the icon that reads "PROGRAMS" 
</p>

![image](https://github.com/user-attachments/assets/72eff9fb-344b-4449-985f-cc929bcf0a2a)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(B) Double-click on "PROGRAMS AND FEATURES" 
</p>

![image](https://github.com/user-attachments/assets/8060c297-9239-459a-9e73-8605ed8a382c)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(C) On the left side of the window, double-click the Icon that reads "Turn windows Features on or off" 
</p>

![image](https://github.com/user-attachments/assets/5abad30c-c72f-418f-83d2-d8db348b7a8a)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(D) In the <b>"Windows Features"</b> window, scroll down until you find a folder that reads <b>"Internet Information Services"</b> or IIS (for short) <br /> (expand/+) the Internet Information Services folder by selecting the (+) icon <br /> 
(expand/+)World Wide Web Services folder <br /> (expand/+)Common HTTP features-
</p>

![image](https://github.com/user-attachments/assets/6482a34f-9dc9-489d-a2e0-f116165f1c76)

<p>both images are the same window, the only difference is that the image below has folders that have been expanded</p>

![image](https://github.com/user-attachments/assets/59db12c3-a0df-4c49-b139-39e68afe71e0)

<p>
  !!For Each listing seen with "[X]" in front of it - make sure to check them off in the <b>"Windows Features"</b> window as seen in the image above!!
  <ul>
  <li>[X]Default document </li>
  <li>[X]Directory Browsing </li>
  <li>[X]HTTP Errors </li>
  <li>[X]Static Content</li>
</ul>  
</p>

Then, click "okay"

<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- --------------------------------------------------------- Install / Enable IIS in Windows WITH CGI - CLOSE -------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->


<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- --------------------------------------------------------- Install osTicket Files - OPEN  -------------------------------------------------------------------------------------------------------------  -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<h1>2) Install <a href=https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD> "osTicket files" </a></h1>

<p>
(A) download the <a href=https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD> "osTicket files" </a> 

<ul> 
    <li>Unzip and drag the “osTicket-Installation-Files” folder onto your desktop</li>
     <li>Open the “osTicket-Installation-Files” folder</li>
  </ul>
  
</p>

![image](https://github.com/user-attachments/assets/62022457-211e-4baf-aed3-b05c03248c3e)

<hr style="border: none; height: 2px; background-color: black;">

  <p>
(B) - From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
  </p>

![02-PHP-manager](https://github.com/user-attachments/assets/3d935c5a-f723-417a-bba6-2ba074e2dc35)

<h3>When the <b>IIS Manager Set up Window appears</b> </h3>
<ul>
  <li>Click Next</li>
  <li>Agree to the Licensing agreement</li>
</ul>
</p>
<br />

<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">
(PLACE IMAGE HERE)




<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

<br />

<p>
  
(PLACE IMAGE HERE)
  
</p>
<p>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- --------------------------------------------------------- Install osTicket Files - CLOSE  ------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
