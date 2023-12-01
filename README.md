Add-Firebase-to-your-web-app

1]   Create Your flutter project for web.

2]   Create a firebase accout and login.

3]   Register app.

4]   Add Firebase Sdk.
         run command -   $"npm install firebase".  {install Nodejs and set environment varriable in your system for npm commands }
		 in Web/index.html file  past scripts into the bottom of your <body> tag.
5]   Install Firebase CLI
         run command -  $"npm install -g firebase-tools"	

6]  Deploy to Firebase Hosting 

        run command - 
		
            $"Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass  [For firebase configuration]"
			$"firebase login"  
			$"firebase init"
	
	And then  Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confirm your      
     choices.
	 
	* Choose - >() Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys
	
7]  Use an existing project.

8]  Hosting Setup 
     
	 {1} What do you want to use as your public directory? 
	  -  build/web
	 
	 {2} Configure as a single-page app (rewrite all urls to /index.html)?
	  -  y
	 
	 {3} Set up automatic builds and deploys with GitHub? (y/N) 
	  -  y and give your github repositorie path
	  
	 {5} Set up the workflow to run a build script before every deploy?
	  -  Yes
       
	 {6} What script should be run before every deploy? (npm ci && npm run build) 
	  -  npm run build
	  

9]  After follow thise steps you got 2 files in your web folder .
 
     firebase.json...
     .firebaserc... 
	
	  if not retry with 			$"firebase init" command.
	  
10]  And now successfully run this command  
 
      $"flutter build web"


11]  Run this command for genrate url for your web. 

      $"firebase deploy"
	  
	  
	  Exmple - https://add-firebase-to-your-web-5b448.web.app/#/dashboard
	  
	

       	
	
	  
	  

	  
	  

	  
	 
	  
 	   
	
	   
		
         
		 
		 
		 
