<!-- NAME -->

# COVID-19 TRACKING SYSTEM
>*logApp-De-Paz*

<div align="right">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/w/RalphDePaz/logApp-De-Paz?label=Commits&logo=github&logoColor=green&style=for-    the-badge"> 
</div>
<br>  


<!-- DESCRIPTION -->
## DESCRIPTION

<p style='text-align: justify;'>  
  
This **COVID-19 TRACKING SYSTEM** is intended to assist the general public in obtaining all pertinent and important information pertaining to the scenario that would keep them well-informed and updated as well as provide them with immediate and preliminary assistance if they exhibit COVID-19 virus symptoms so they can be subjected to immediate medical attention and attending.

This will get the basic information such as name, address, and also the log date and time. The system will make sure that all of the information is safe and only admins can view the list of individuals who visited the premises.    
  
</p>

<br> 



<!-- VISUAL   -->
 <div align="center">
    <img src="https://media.giphy.com/media/dVuyBgq2z5gVBkFtDc/giphy.gif" width="400" height="260" style="display: block; margin: 0 auto">  
 </div>
 
<br>

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" src="image/Registration.png">  REGISTRATION |  <img width="1604" src="image/Login_Page.png">  LOG IN PAGE |  <img width="1604" src="image/Persons_log.png">  PERSON'S LOG |  

  
<br>


<!--INSTALLATION -->
## INSTALLATION

- First clone this repository (https://github.com/RalphDePaz/logApp-De-Paz.git)

- Download and install XAMPP [Open-source cross-platform web server solution stack package]
  - XAMPP download link (https://www.apachefriends.org)  
    - Open XAMPP as administrator
      - Start MySQL
  
- Create a account on https://www.freesqldatabase.com
  - You will receive an email you can use later on 
  - Log in into the PhpMyAdmin

- *You can also use MySQL Workbench*

- Set up your data base
  - Create a table for the PERSON [uid, first_name, last_name, address, and logdt]
  - Create a table for the ACCOUNT [uid, username, password]
    -  *Make sure that the logdt is set to TIMESTAMP and default CURRENT TIMESTAMP*

- Locate the cloned repository and open the config.php file on VSCODE or any software you want.
  - Edit this base on what the freesqldatabe email you received.
  >define('ROOT_URL', ''); define('DB_HOST', ''); define('DB_USER', ''); define('DB_PASS', '');  define('DB_NAME', '');

- You can test your file direct on VSCODE using some extension
- You can also test it using the XAMPP
  - Move your folder in the XAMPP/htdocs file location
  >D:\Program Files\Xampp\htdocs

- To test using XAMPP
  - Use any browser you want and type this
    - Registration Form
    - >http://localhost/"Your_Foldername"/logApp-scaling-octo/
    - Log In Page
    - >http://localhost/"Your_Foldername"/logApp-scaling-octo/guestbook-login.php
    - Person's Log
    - >http://localhost/"Your_Foldername"/logApp-scaling-octo/guestbook-list.php
    
                                                                                                                                          
<!-- PROFILE   -->                                                                                                                                         

## AUTHOR
                                                                                                                                       
<div align="left">
    <img src="https://scontent.fmnl13-1.fna.fbcdn.net/v/t39.30808-6/270772910_2085853528243775_5726229684246422638_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=09cbfe&_nc_eui2=AeEcABL7t8-tQVL0A17FhjCO6r98w66wdubqv3zDrrB25jdgPRV5Oj2Ui9kB8Ng7ZZhq9ejDGgEw7ywIwP8wbEmj&_nc_ohc=sAIGzMY57HsAX8oU-yc&_nc_ht=scontent.fmnl13-1.fna&oh=00_AfDYypJ7CotBLxPcT1xZso3LdqP5IcL9PJlj7Xm9rgzlRA&oe=636C837A"
         width="200" height="200" style="display: block; margin: 0 auto"> 
</div>
 
<div align="left"> 
  
## John Ralph De Paz
                                                                                                                                  
*BSCS 3B-1*                                                                                                                                 

[GitHub ](https://github.com/RalphDePaz)

[Email 📬](mailto:202080468@psu.palawan.edu.ph)
  
</div>



| | | 
|:-------------------------:|:-------------------------:|
|<img width="1604" src="image/Registration.png">  REGISTRATION |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="image/Login_Page.png">  LOG IN PAGE | 
