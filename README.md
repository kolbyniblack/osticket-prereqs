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
<li> (1) Install / Enable IIS in Windows WITH CGI </li>

<li> (2) Install osTicket Files (parts A-E) </li>

<li> (3) Install MySQL </li>

<li> (4) Register PHP from within IIS (A-B) </li>

<li> (5) install HeidiSQL </li>
</ul>

<!-- --------------------------------------------------------- LIST-OF-PREREQUISITES-CLOSE ------------------------------------------------------------------------------------------------------------- -->

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- --------------------------------------------------------- Install / Enable IIS in Windows WITH CGI - OPEN --------------------------------------------------------------------------------------------  -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<h1>(1)Install / Enable IIS in Windows WITH CGI</h1>


 In the Windows desktop search bar, look up <b>"Control Panel"</b> - The window seen in the image below will open <br /> Next -> <b>Follow the images below step-by-step according to their Roman-Numeral</b>

<p> 
(I) Once this window appears, make sure you double-click on the icon that reads "PROGRAMS" 
</p>

![image](https://github.com/user-attachments/assets/72eff9fb-344b-4449-985f-cc929bcf0a2a)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(II) Double-click on "PROGRAMS AND FEATURES" 
</p>

![image](https://github.com/user-attachments/assets/8060c297-9239-459a-9e73-8605ed8a382c)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(III) On the left side of the window, double-click the Icon that reads "Turn windows Features on or off" 
</p>

![image](https://github.com/user-attachments/assets/5abad30c-c72f-418f-83d2-d8db348b7a8a)

<hr style="border: none; height: 2px; background-color: black;">

<p> 
(IV) In the <b>"Windows Features"</b> window, scroll down until you find a folder that reads <b>"Internet Information Services"</b> or IIS (for short) <br /> (expand/+) the Internet Information Services folder by selecting the (+) icon <br /> 
(expand/+)World Wide Web Services folder <br /> (expand/+)Common HTTP features-
</p>

![image](https://github.com/user-attachments/assets/6482a34f-9dc9-489d-a2e0-f116165f1c76)

<p>both images are the same window, the only difference is that the image below has folders that have been expanded</p>

![image](https://github.com/user-attachments/assets/59db12c3-a0df-4c49-b139-39e68afe71e0)

<p>
  !!For Each listing seen directly below with an "[X]" in front of it - make sure to locate them in the window titled <b>"Windows Features"</b> and check-mark each box as seen in the image above!!
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

<!--this is the beginning of (2-A; 1-4) -->

<h1>(2-A) Install <a href=https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD> "osTicket files" </a></h1>

<p>
Download the <a href=https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD> "osTicket files" </a> 

<ul> 
    <li>Unzip and drag the “osTicket-Installation-Files” folder onto your desktop</li>
     <li>Open the “osTicket-Installation-Files” folder</li>
  </ul>
  
</p>
<!--ROMAN NUMERAL 1 OPEN -->

<p>I.- From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)</p>

![image](https://github.com/user-attachments/assets/d5b96631-519f-4bf5-bb10-2cb1e48bfadd)

<hr style="border: none; height: 2px; background-color: black;">


<h3>When the <b>IIS Manager Set up Window appears</b> </h3>



<!--ROMAN NUMERAL 2 CLOSED --> 

<!--ROMAN NUMERAL 3 OPEN --> 

<p>III.Click Next</p>

 ![image](https://github.com/user-attachments/assets/d91e4b04-4d90-4634-a81e-fecfd8dd4d54)

  

<!--ROMAN NUMERAL 3 CLOSED --> 

<!--ROMAN NUMERAL 4 OPEN -->

<p>IV.Agree to the Licensing agreement</p>

![image](https://github.com/user-attachments/assets/e4d2adc7-54f3-4fda-9013-85b1e78f88fb)

<!--ROMAN NUMERAL 4 CLOSED -->

<br />

<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">
<hr style="border: none; height: 2px; background-color: black;">

<!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) -->
<!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) -->
<!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) --><!--this is the beginning of (2-B) -->

<h1>(2-B) install the Rewrite Module (rewrite_amd64_en-US)</h1>

<p>(I) click on the file that reads (rewrite_amd64_en-US) </p>

![image](https://github.com/user-attachments/assets/4f2690c2-f6e6-4327-8921-7be2e695f732)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<p>(II) Once the <b>"set-up"</b> window opens, click the <b>"Install"</b> button</p>

![image](https://github.com/user-attachments/assets/5a16f15f-81e9-46ce-a1f2-53d3e22caa13)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<p>(III) Once installed, click the "Finish" button, and then continue on to section (2-C)</p>

![image](https://github.com/user-attachments/assets/adfefeba-fdfd-4e0c-bf1f-a668cd5c6c05)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) -->
<!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) -->
<!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) -->
<!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) -->
<!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) --><!--this is the closing of (2-B) -->


<!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) -->
<!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) -->
<!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) --><!--this is the beginning of (2-C) -->


<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<h1>(2-C) Create the directory "C:\PHP"</h1>  
<h4> ( This is a "new folder" that you will create in the C:drive - name the folder <b>"PHP"</b> )</h4>

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<p>(I) On the left side of Windows' "File Explorer" locate the highlighted icon named "This PC", and click the "expansion" button</p>

![image](https://github.com/user-attachments/assets/9c3ed1a2-c369-44c4-916e-858f860b4b86)


<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<p>(II) Once expanded, locate the C:drive. It will show as "Windows(C:)"</p>

![image](https://github.com/user-attachments/assets/92e59021-31d1-4678-b635-af247bd5fb1f)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<p>(III) Right-click anywhere (in the imaginary red-box shown in the image) . When the pop-up window appears, <br /> hover your mouse over "New", then click "Folder" from the pop-up window </p>

![image](https://github.com/user-attachments/assets/dd1a8cdc-8236-4f07-81f0-acf302b1228b)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<p>(IV) Once the folder is created, the name of the folder will be ready to be edited. From here, you can type the letters "PHP" <br /> Then, continue on to section (2-D) </p>

![image](https://github.com/user-attachments/assets/c010a6ce-9d50-4d51-996b-41d2155f3f95)

![image](https://github.com/user-attachments/assets/1842797e-f8d3-4b78-94cf-7af22a48b06c)

<h6>!!When changing the names of files and folders, it is extremely important to name them exactly as directed. Case sensitivity, spaces, etc. are all extremely important to adhere to - Please be very careful!! </h6>

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) -->
<!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) -->
<!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) --><!--this is the beginning of (2-D) -->
 
<h1>(2-D) Unzip [PHP 7.3.8] into the “C:\PHP” folder ( ie: The new folder that was just created )</h1>

<p>
 (I)From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder
</p>

![image](https://github.com/user-attachments/assets/65607a64-9906-4bac-8b13-986aeae2760d)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<p>(II) Right-click on file, and click "Extract All"</p>

![image](https://github.com/user-attachments/assets/089f9ca3-504d-4d28-8a3e-e1fae152cced)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
 
<p>(III) In the next window that appears, click on "Browse"</p>

![image](https://github.com/user-attachments/assets/9c097746-2830-49e8-9191-e093e344581f)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
  
<p>(IV) Find and select the "PHP" folder. Once selected, click the "Select Folder" button</p>

![image](https://github.com/user-attachments/assets/d2bc4df0-7256-4e1f-9591-d87ca93e9ffa)


<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
   
<p>(V) Once the folder is selected, click the "Extract" button</p>

![image](https://github.com/user-attachments/assets/b88a4c14-aa9c-47c0-9d98-1647e24b066e)


<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
    
<p>(VI) Once extraction is 100% completed, you may now move on to section 2-E: "installing <b>Microsoft Visual C++</b> </p>

![image](https://github.com/user-attachments/assets/4a10c724-1c19-4a95-8814-19b801329a34)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


 <!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) -->
 <!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) -->
 <!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) --><!--this is the beginning of (2-E) -->

<h1>(2-E) Installing Microsoft Visual C++ </h1>

<p>
  (I) From the “osTicket-Installation-Files” folder, install <b>VC_redist.x86.exe.
  <ul>
   <li>a. Double-click VC_redist.x86.exe. </li>
   <li>b. Agree to the "terms and conditions"</li>
   <li>c. Click "Install"</li>
  </ul>
  </p>

  ![image](https://github.com/user-attachments/assets/7be4f2c3-cb7f-4b52-bdeb-000801a7ab0a)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

![image](https://github.com/user-attachments/assets/8e6b7775-ef04-4536-b7e6-f17bb64236d7)

<p>Once Set up is successful, you may move on to section 3: <b>"Installing 'MySQL' and Registering PHP from within IIS"</b></p>


<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!----------------------------------------------------------- Install osTicket Files - CLOSED----------------------------------------------------------------------------------------------------------->
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>

<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!----------------------------------------------------------- (3) INSTALL MYSQL - OPEN ----------------------------------------------------------------------------------------------------------------->
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>

<h1>(3-A) Install MySQL and Register PHP from within IIS</h1>

<p>(I) From the “osTicket-Installation-Files” folder, install <b>MySQL 5.5.62</b></p>

![image](https://github.com/user-attachments/assets/a3705f5a-97fd-44d7-a632-14605be9a949)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<p>(II) In the "MySQL" set up window you will follow the list below</p>

<p>
   <ul>
    <li> -click next</li>
    <li> -accept terms and conditions</li>
    <li> -select "typical"</li>
    <li> -select "install"</li>
    <li> -select "launch MySQL configuration Wizard"</li>
    <li> -select "finish"</li>
   </ul>
</p>


![image](https://github.com/user-attachments/assets/33235bd3-9cfb-43b7-80b1-71731a243525)

<p><h6>Important! Make sure "Launch the MYSQL Configuration Instance Wizard" check-box is selected before selecting the finish button</h6></p>

![image](https://github.com/user-attachments/assets/c371ccec-d3d0-40dc-95c8-54b68c76ca13)

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<h1>(3-B) MYSQL Instance Configuration Wizard </h1>
<h2>!!!IMPORTANT!!!PLEASE READ BEFORE MOVING FORWARD!!!</h2>

<h4>In this section you will be prompted to create a password! Make sure you write down or create a password that you are 1,000% sure to remember! If you forget what your password is after this is completed, you will have to start over! </h4>
 
 <p>(I) In the Configuration Wizard, follow each item listen below, in order, from top to bottom </p>

 <ul>
   <li>select "next"</li>
   <li>select "Standard Configuration"</li>
   <li>select "Modify security setting"</li>
   <li>Create Password</li>
   <li>select "Execute"</li>
   <li>select "Finish"</li>
 </ul>





<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!----------------------------------------------------------- (3) INSTALL MYSQL - CLOSED---------------------------------------------------------------------------------------------------------->
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>

<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->


<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!---------------------------------------------------- (4) REGISTER PHP FROM WIHTIN IIS - OPEN  -------------------------------------------------------------------------------------------------->
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<!------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>
<p> <h1>(4-A) Register PHP from within IIS </h1> </p>

<p>
  From the Desktop Search Window, type "IIS Manager" once the name appears, right click, and choose "Run as Administrator" <br /> IIS manager will open 
 </p>

![09-RGSTRPHP-IIS-01-02-mx](https://github.com/user-attachments/assets/82902377-bc81-47fc-bb2a-d3129467155a)

 <p>
  
 </p>

 I. Open "PHP Manager"<br />
 ![09-RGSTRPHP-IIS-02](https://github.com/user-attachments/assets/d4a238bd-d427-49ed-9fed-4c96593807ac)

<hr style="border: none; height: 2px; background-color: black;">

 II. Select "Register new PHP version"<br /> 
 ![09-RGSTRPHP-IIS-03](https://github.com/user-attachments/assets/8ef88c75-b968-4fa8-a7a1-c0497d608d6c)

<hr style="border: none; height: 2px; background-color: black;">

 III. Select the Ke-bab menu (box with 3 dots ) <br />  
 ![09-RGSTRPHP-IIS-04](https://github.com/user-attachments/assets/f6499f47-35f3-45ce-b0a3-8d0acf05001a)

<hr style="border: none; height: 2px; background-color: black;">

 IV. Open the "PHP" folder; Located in the Windows(C:) drive" <br /> 
 ![09-RGSTRPHP-IIS-05](https://github.com/user-attachments/assets/3b7acf99-de2c-4d93-991b-2d8c9050e02c)

<hr style="border: none; height: 2px; background-color: black;">

 V. Open the file "php-cgi" <br />  
 ![09-RGSTRPHP-IIS-06](https://github.com/user-attachments/assets/994d7e78-2e34-4731-87fe-07c0b60385c7)

<hr style="border: none; height: 2px; background-color: black;">

 VI. Select "OK" <br /> 
 ![09-RGSTRPHP-IIS-07](https://github.com/user-attachments/assets/0e0ed9e3-dad2-49d2-8d43-9601ab98725d)

<hr style="border: none; height: 2px; background-color: black;">

 VII. Once back in IIS Manager Window, go the "Osticket-lab Home" screen ( it is located on the left side of the window)<br />  
 ![09-RGSTRPHP-IIS-08](https://github.com/user-attachments/assets/7b09ae9d-e188-40c0-8351-f17517d1e4ba)

<hr style="border: none; height: 2px; background-color: black;">

 VIII. Select the "stop" action ( wait at least 30 seconds ) <br /> 
 ![09-RGSTRPHP-IIS-09](https://github.com/user-attachments/assets/457fcf37-9740-4cf5-8c2a-b7f146049ae6)

<hr style="border: none; height: 2px; background-color: black;">

 VIV. Select the "start" action <br /> 
 ![09-RGSTRPHP-IIS-10](https://github.com/user-attachments/assets/9a2c2d99-fa0f-4f72-a784-53a8094e27a4)
 
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<hr style="border: none; height: 2px; background-color: black;"><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->
<!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line--><!--This is a separation line-->

<h1>4-B</h1>

<p>
 <ul>
  <li>(I) Install osTicket v1.15.8</li>
  <li>(II) Enable osTicket Extensions</li>
  <li>(III) Rename: ost-config.php</li>
  <li>(IV) Assign Permissions: ost-config.php</li>
 </ul>
</p>

<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!--<h2>(I) Install osTicket v1.15.8 (a-f)</h2>-->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
![10-instll-OSTkt-V1158-00](https://github.com/user-attachments/assets/6ff3102a-1713-4fff-a4e6-604d08edc191)
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->

<p>(a) From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip”</p>

![10-instll-OSTkt-V1158-01](https://github.com/user-attachments/assets/ebc1b4bd-6149-4d88-8da1-c14b33b7d6dd)

(b) Copy the "upload" folder, then open "Windows(C:) drive"<br />
![10-instll-OSTkt-V1158-04](https://github.com/user-attachments/assets/7c70e306-7f48-4ce4-8dfc-18e67819125c)

(c) In Windows(C:) open the "inetpub" folder<br />
![10-instll-OSTkt-V1158-03](https://github.com/user-attachments/assets/533ecdce-9cfe-486e-bfa7-ca0b11e88954)

(d) Open the wwwroot folder <br />
![10-instll-OSTkt-V1158-05](https://github.com/user-attachments/assets/3b93ba73-1fb8-499e-a823-162fef22ec28)

(e) right click and select "paste" <br />
![10-instll-OSTkt-V1158-06](https://github.com/user-attachments/assets/e13b1734-1ef6-4c4d-9e3d-9c55ce61bd3a)

(f) once upload is complete, rename "upload" folder <br />
![10-instll-OSTkt-V1158-07](https://github.com/user-attachments/assets/7dea4442-b6f7-4047-b5ac-91d959097680)

(g) Rename the "upload" folder to "osTicket" <br />
![10-instll-OSTkt-V1158-08](https://github.com/user-attachments/assets/7b9b85d3-fa8e-4e53-b472-3b1d9c3a02b0)
![10-instll-OSTkt-V1158-09](https://github.com/user-attachments/assets/32571fe1-24f0-46c1-92b7-136dfbdd23c8)

(h) Open IIS Manager - stop then start the server <br />
![10-instll-OSTkt-V1158-10](https://github.com/user-attachments/assets/1632b603-9f69-42fa-a88e-76fe710116b7)
![10-instll-OSTkt-V1158-11](https://github.com/user-attachments/assets/53823587-2a3c-4a63-aef1-ff7be4d93c8b)

(i) Go to "Sites" -> then "Default Web Site" -> then "osTicket"  <br />
![10-instll-OSTkt-V1158-12](https://github.com/user-attachments/assets/680098bc-b898-415b-a079-c070dd7f5ef7)
![10-instll-OSTkt-V1158-13](https://github.com/user-attachments/assets/3aba9665-b3eb-477d-a5fc-b70cf0974f04)
![10-instll-OSTkt-V1158-14](https://github.com/user-attachments/assets/a3a01a03-8019-45bc-8ee8-079858279edd)


(j) To the right, click “Browse *:80” <br />
![10-instll-OSTkt-V1158-15](https://github.com/user-attachments/assets/543289da-d86a-43a5-b769-6777ebbfd0a3)

You should see the "osTicket Installer" appear (Enabling the Extensions is up next) <br />
![10-instll-OSTkt-V1158-16](https://github.com/user-attachments/assets/36f014a3-fb0c-41a3-b523-c984b5f6e8fe)

<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!--ENABLE-OSTICKET-EXTENSIONS------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
![11-enbl-osTkt-extnsn-00](https://github.com/user-attachments/assets/cd13f069-12fe-4cdc-bed8-d5dddcc930bb)

(a) In IIS Manager, select "osTicket-lab" Home page, and select PHP manager <br />
![image](https://github.com/user-attachments/assets/cd63c114-e551-4aca-98f5-160163445b97)
![image](https://github.com/user-attachments/assets/eec840f9-64c2-4f85-83b9-c93653ca51c2)


(b) Select "Enable or disable an extension <br />
![image](https://github.com/user-attachments/assets/a5a4a0c8-af4a-4878-9135-596e50417f52)

(c) In the pop-up window, locate and nable each item listed below
<p>
 <ul>
  <li> php_imap.dll</li>
  <li> php_intl.dll</li>
  <li> php_opcache.dll</li>
 </ul>
</p>

![image](https://github.com/user-attachments/assets/ab387407-0c22-4d9e-a738-ec4784a6169b)

In osTicket Installer, Refresh the page by clicking the "refresh" button or "f5" on your keyboard and observe the changes <br />
![11-enbl-osTkt-extnsn-05](https://github.com/user-attachments/assets/7f567170-c2cf-4dc3-b682-d69c322e7324)
![11-enbl-osTkt-extnsn-06](https://github.com/user-attachments/assets/41d21ef1-aa30-4e74-820c-32b63f903777)

<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!--(III) Rename: ost-config.php----------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->

![12-Rename-ost-config-php-00](https://github.com/user-attachments/assets/b5222035-b466-4191-a201-c53ff95bf77a)

<p>(a) In the "wwwroot" folder, open "osTicket" - then open "include" and locate the file "ost-sampleconfig.php"</p> <br />

![12-Rename-ost-config-php-01](https://github.com/user-attachments/assets/f7b2b6f8-c9b4-4949-b799-a74ddc322be7)
![12-Rename-ost-config-php-02](https://github.com/user-attachments/assets/26021d52-268a-4411-ab37-9079c93fdf80)

(b) Rename "ost-sampleconfig.php" to ""ost-config.php" <br />
![12-Rename-ost-config-php-03](https://github.com/user-attachments/assets/1c24c329-1537-43ff-a5f6-ae6445ecc992)
![12-Rename-ost-config-php-04](https://github.com/user-attachments/assets/a5b68fc6-94b8-4fa9-a9fd-55ed42ee1799)
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<hr style="border: none; height: 2px; background-color: black;">

<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!---Assign Permissions: ost-config.php---------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->

![13-Assign Permissions- ost-config-php-00](https://github.com/user-attachments/assets/10ab5899-42f0-46e7-a6d9-b4b0f45bd800)

(a) Right click "ost-config.php" and select "Properties" - then "Advanced" - then "Disable inheritance" <br />
![13-Assign Permissions- ost-config-php-01](https://github.com/user-attachments/assets/366bce8f-958e-4ae8-b4bc-702035b02073)
![13-Assign Permissions- ost-config-php-02](https://github.com/user-attachments/assets/a4da4f9d-cf21-4a72-bba7-a040d3749c28)
![13-Assign Permissions- ost-config-php-03](https://github.com/user-attachments/assets/98ee759c-814d-4f86-9125-881071d361f7)

<hr style="border: none; height: 2px; background-color: black;">

(b) Select "Remove all inherited permissions from this object" <br />
![13-Assign Permissions- ost-config-php-04](https://github.com/user-attachments/assets/303ce5e8-b685-4047-bce2-ad7b6cdbfdb8)

(c) In the next window, select the "Add" button <br />
![13-Assign Permissions- ost-config-php-05](https://github.com/user-attachments/assets/45470af6-95bc-4437-afe7-cd8ff4bab99d)

(d) In the next window, click "Select a principal" and in the text box type "everyone" - next select "OK" <br /> Then check off the Basic permissions as seen in the third slide <br />

![13-Assign Permissions- ost-config-php-06](https://github.com/user-attachments/assets/95c5d6ae-3efe-470f-9a57-c7f362247dc3)
![13-Assign Permissions- ost-config-php-07](https://github.com/user-attachments/assets/50932664-2fa8-4a1d-b84f-c62dea0cf506)
![13-Assign Permissions- ost-config-php-08](https://github.com/user-attachments/assets/b6b5f909-f29d-4472-9300-c1c997784b09)

(e) Select "Apply" then continue setting up osTicket in the browser ( click continue ) <br />
![13-Assign Permissions- ost-config-php-09](https://github.com/user-attachments/assets/266bdeb8-2d88-4cf9-9552-15cb3620d3d3)
![13-Assign Permissions- ost-config-php-10](https://github.com/user-attachments/assets/d740a782-44a1-4f7a-9f65-b0e217348734)

(f) Creat a "Helpdesk Name" and a "Default Email" (to receive email(s) from customers) <br />
![13-Assign Permissions- ost-config-php-11](https://github.com/user-attachments/assets/0979ce52-9efc-4b3b-a84a-168e62bfd207)
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->
<hr style="border: none; height: 2px; background-color: black;">
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->

<!----------------------------------------------->
<!----------------------------------------------->
<!-----------(5)install HeidiSQL----------------->
<!----------------------------------------------->
<!----------------------------------------------->
<!----------------------------------------------->

![14-install HeidiSQL-00](https://github.com/user-attachments/assets/b2449076-0252-48bc-84cb-24e64780580b)





