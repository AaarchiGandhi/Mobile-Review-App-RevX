# Mobile Review App (RevX)

## Project Description

    While watching instagram feed we felt it was very easy to comment, share a post with the view it provides. 
    To achieve this, I thought of creating an app that will be solely used for doing Creative review action such as Approving, Rejecting, etc a Creative using just Mobile.

    The current browser view takes around 3 steps to actually view the content before making a final decision over the creative. 

    This was the basic intent to increase the throughput of manual review team.

    To solve this problem, I went on looking for various frameworks to develop a mobile app which can be easily ported to any platform. 

    I tried out and figured that for our problem space, ionic framework was able to solve all the feature requirements that we thought of.

    Using ionic framework it was easy for us to develop and integrate with other JS framework. 

    To fetch the current creative data we simply used the current API exposed for creative review which had all the relevant info that we wanted to showcase.

    Lets go through the current flow of our app which we feel if used by the user can improve its throughput by 3 times as the current view makes it very clear to approve or reject a content in a single scroll.

    The first page is the login page, here we have two user accounts.

    1. Creative reviewer.
    2. Creative Reviewer lead.

    Lets see the flow of creative review user (DIY after login).
    Lets see the flow of creative reviewer lead (DIY after login).

    To conclude:

    We feel, the efficiency could increase by 3 times.
    Easy access for the manual reviewer team.
    Ease of access for business users.
    Since, it provides a UX which eases the users work.

  The project is build using Ionic Framework in Angular.
  
   I have hosted this project on this link :
  
 Hosted at : [https://AaarchiGandhi.github.io/Mobile-Review-App-RevX](https://aaarchigandhi.github.io/Mobile-Review-App-RevX/login) 
      (Please view in Mobile mode)
    
  ## Please open this website in either Mobile or responsive Mobile devices (if you're using any browser in Laptop screen).
  (Preferably use Samsung Galaxy S20 Series)

  Steps to run the Project :

    npm install
    npm install -g @ionic/cli
    ionic serve

  The project will open at http://localhost:8100/login

  This project is for Mobile devices.
 
    (Just make this repo public, then you're able to see this website live)

  Below are the Usernames & their Credentials :

    - Username : aarchi.gandhi
    - Username : vikhitha.reddy
    - Username : rahul.malhotra
    - Username : deepak.saxena
    - Username : admin

    The password is same for all Users - Creative@123

  We do have 2 roles - Creative Reviewer Lead, and Creative Reviewer role
  
  Creative Reviewer Lead can see the Dashboard of all other users too.
  
  We have 4 components -
    
    - Login Page
    - Main Approved / Rejected / Pending Page
    - View Details Page
    - Profile Page
    
   ## Steps for hosting on Github Pages :
	
	ng build --base-href "https://AaarchiGandhi.github.io/Mobile-Review-App-RevX"
	cd dist
	git init
	
	git remote add origin https://github.com/AaarchiGandhi/Mobile-Review-App-RevX.git

`Here, before committing the files inside dist folder, check this line <base href=https://AaarchiGandhi.github.io/Mobile-Review-App-RevX"> in index.html. You should append '/' forward slash at the end of href path. (Line no.5)`

`It should become <base href=https://AaarchiGandhi.github.io/Mobile-Review-App-RevX/"> in index.html in dist folder. Now, you can commit and push the code in gh-pages branch for deployment. (Line no.5)`

	git add .
	git commit -m "Code push for github page"
	
	git push -u origin master:gh-pages

  Set up GitHub Pages: 
	
	Once the code is pushed, you just need to go to your GitHub repository settings, go to the "Pages" tab and set the source to the gh-pages branch.
  That's it! Your Ionic project should now be deployed to GitHub Pages.
