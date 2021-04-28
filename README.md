# Klouderp-RPA

### Required package or lib

1. python with pip (pip for download required lib)
2. Git bash (Install git)
3. Selenium (for automation) package
4. Klouderp package ()

### Required apps

1. KloudeERP Assistant (klouderp-Assistant.exe for Windows)
2. KloudERP app (klouderp.apk for Android) for login your account using QR Code Scanner.

Open Klouderp.com web apps, if you have already an account go on your account otherwise open login page. There are three type of login.
1.  using QRCode scan    
2.  mobile number and OTP 
    ![Image of login](https://user-images.githubusercontent.com/10446918/116033685-79d52000-a67f-11eb-9751-60107613cca0.png)
    
 3. using email id and password.
    ![Image of login1](https://user-images.githubusercontent.com/10446918/116033772-a4bf7400-a67f-11eb-947d-e6374eb5e358.png)

If you want to login using QR code :
1.  Open play store on your mobile and search kloudERP apps and install. 
2.  Once app is installed login using number and otp    
3.  Open QR code scanner on your mobile app and scan QR code which will be open klouderp.com login page, Now you can login using QR code anytime anywhere.

Open your account on klodeERP then search and install RPA app in Kloderp web app and open.

Install KloudERP-Assistant.exe apps and open. Now you can see login page which is login using QR code scanner so now open any klouderp app on your mobile and scan QR code then    you are login.

Now you can go on system tray icon of klouderp on your system and right click on KloudERP and select Connections. if you have machine key then paste here otherwise go on          Klouderp and open RPA and add a machine after save a new machine copy machine key and paste kloudERP Assistent connections page then click on Connect Button. If your machine key are exist then update your status offline to online otherwise show a message invalid machine key.

Now you are connected RPA Orchestrator.

#### Create a proccess on Github
We need a **github account** and **git bash** for create a proccess and push processes that git repositories.
We are creating a process for adding two number.

#### Let'create a process
1. Create a python file, file name is test.py which is extention ".py".
2. Write to python code for two number addition in test.py.
3. Save to file and git push your code on github repositories.

#### Let's add you process on KloudERP-RPA app
1. Now login on KloudERP then open RPA
2. Click on **Proccess** and add a Process.
3. Fill all fields like Process name, process uri and environment.
4. Open your github account then open test repositories and copy for clone.
5. now paste your clone url on process uri field.
