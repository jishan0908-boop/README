KEYWORDS:
CLOUD COMPUTING:
CLOUD MODELS:
1. PUBLIC:
2. PRIVATE:
3. HYBIRD;
4. COMMUNITY:

CLOUD SERVICES:
1.IAAS:
2.PAAS:
3.SAAS:

INTRODUCTION OF AWS:

1.AWS SERVICES:
2.EC2-Elastic Cloud Compute
3.EBS-Elastic Block Store
4.Auto scaling
5.S3-Simple Storage Services
6.ELB-Elastic Load Balancer
7.IAM-

1. CREATE AN AWS ACCOUNT
2. THEN GO TO CONSOLE WHERE YOU FIND EC2.
3. THEN CLICK ON LAUCH INSTANCE, WHERE YOU HAVE TO ENTER THE NAME ATG{XYZ}.
4. AFTER THAT SELECT THE OPERATING SYSTEM , THEN CLICK ON FREE TIRE ELIGBLE.
5. NOW YOU HAVE TO CREATE NEW KEY PAIR , WHERE AS KEY PAIR ARE PUBLIC OR PRIVATE. ALSO SELECT THE .PPK THEN PRESS ENTER TO CREATE.DOWNLOAD THE KEY PAIR AND SAVE IT IN DESKTOP ALSO.
6. NOW YOU WILL SEE THE RAM AND CPU WHICH IS GIVEN BY AWS.
7. NOW ALLOW SSH AND HTTP.
8. AFTER ALL THIS STEPS THEN CLICK ON THE LAUNCH INSTANC AND CLICK ON ALL INSTANCE.
9. NOW YOU CAN SEE YOUR CREATED YOUR INSTANCE AND IP ADDRESS.
10. COPY YOUR IP ADDRESS AND PASTE IT IN NEW TAB , YOU WILL FIND NOTHING BECAUSE THEIR IS NO SERVER PRESENT.
11. TO CREATE SERVER INSTALL PUUTY.
12. OPEN PUTTY WHERE FIRST GO TO SESSION AND ENTER YOUR IP ADDRESS.
13. THEN GO SSH THEN AUTH THEN CREDITALS .
14. WHERE YOU HAVE TO CLICK ON BROWSE WEHRE SELECT THE KEY PAIR FILE WHICH IS PRESENT IN DESKTOP.
15. NOW GO TO SESSION AND CLICK ON OPEN
16. YOUR VM IS CREATED.
  TO OPEN A WEB SERVER---
1.TYPE ON GOOGLE HOW TO INSTALL WEB SERVER IN YOUR OS WHICH YOU HAVE SELECTED.
2.NOW DOWNLOAD ANY WEB SERVER LIKE APACHE2ETC.
3.FROM THAT INSTALL APACHE2 IN YOUR VM
TYPE : sudo apt update
       sudo apt install apache2

---PRESS ENTER AND WEB SERVER WILL START INSTALLING----
4.TO SEE THE WEB SERVER GO TO GOOGLE OPEN NEW TAB AND ENTER YOU IP ADDRESS . YOU WILL SEE THE APACHE2 WEB SERVER.
-----------TO SEE HI ON SERVER ---------------
1.ENTER THE FOLLOWING COMMAND
  cd /var/www/html/
  ls
  YOU WILL SEE
  index.html
  ------TO REMOVE SUDO-----------
  sudo su
  --------NOW SUDO IS REMOVED--------

  -------REMOVE THE APACHE2 SERVER -----------
  rm index.html
  ------THEN ENTER--------
  vi index.html
  ------PRESS {i} -------
  ----------ENTER----------
  <html>  hi   </html>
  ------NOW PRESS THESE KEY-------
  ctrl+c
  shift+";"
  wq
  -------PRESS ENTER -------
  NOW GO TO GOOGLE AND ENTER THE IP ADDRESS YOU WILL SEE HII
  ----------------------------------------------------------------------------------------------------------------------

