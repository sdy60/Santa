# Santa repocitory

This is the repo commonly used by Santa team.It is used by all members of the team. 
It contains only the public folder of firebase container.

The usage of this code shall be used as showing in the steps below:

A) Initially we create the firebase environment

  1) Create new gmail account
	email: scootersanta69@gmail.com
	paswd: 1234!@#$


  2) Go to firebase console and do the following

	Add project ScooterSanta 


  3) Initial steps to start implementation 

	a) mkdir firebase
	 
	b) cd firebase
	
	c) npm install -g firebase-tools
	
	d) firebase login				#connected to scootersanta69@gmail.com
	
	e) firebase init	

B) Get remotelly the required files from github repo
  
  4) Go into public folder and run the following:
  
  	REM delete existed files (404.html and index.html)
  	del /A /F /Q *							
  
    REM initialize git environment
  	git init   							
    	
	REM connect to the repo
	git remote add origin https://github.com/iarv69/Santa.git	 
    	
    REM pull required files	
	git reset --hard FETCH_HEAD    				

C) Deployment and execution

  5) Local Deployment/execution 

	a) run: firebase serve

	b) Browse url: http://localhot:5000

  6) Remote deployment/execution

	a) run:  firebase deploy	#initially using default params  +  Firebase initialization complete!

	b) browse URL : https://scootersanda.firebaseapp.com 
	
For implementation we should repeat the following

a) We change/add files on public goldr

b) We deploy,execute and test the app.
