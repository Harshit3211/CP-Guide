# CP Guide Web App

 - A competitive programming guide web app that suggests codeforces problems.

## About

 - Suggests the problem based on the parameters provided like Tags, Ratings, Handles.
 - If the user has multiple handles then that is also handled.
 - On providing friends handles, the algorithm changes to find problems that the user has not done and provided friends have.
 - Made with React.js, Nodejs, Javascript, HTML and CSS.

## User Interface

 ![image](https://user-images.githubusercontent.com/70953107/137975143-769df7d2-7e85-4cea-aa8f-04bb6c561dba.png)
 
 - Enter your handle (you can enter multiple handles if you have multiple accounts)
     - Here just for example purposes, I have taken a case where there is a pseudo user who has tourist and um_nik as its handles. 
 
 ![image](https://user-images.githubusercontent.com/70953107/137975950-a5eb3d28-f8d5-4ade-9815-f5c69f28016a.png)
 
 - Enter problem tags (optional)
 
 ![image](https://user-images.githubusercontent.com/70953107/137979662-7153105e-882b-43f7-80ef-5c32c41a00fd.png)
 
 - Enter base round (optional)
 
    -  For https://codeforces.com/contest/1573 base round is 1573
    -  All the problems having base round greater than the above value will be considered for the result
    
  ![image](https://user-images.githubusercontent.com/70953107/137979757-fbd954ae-4c00-4de2-a395-234de1e2e072.png)
  
 - Enter the number of problems you want in the result (optional)

   ![image](https://user-images.githubusercontent.com/70953107/137979822-d23ffa4a-8034-4014-9cc9-449527955a11.png)
   
 - Enter minimum rating of problems you want in the result (optional)
 
   ![image](https://user-images.githubusercontent.com/70953107/137979885-7e30a447-cd8b-4c94-a2d9-5cd1f3f4a5c9.png)
  
 - Enter maximum rating of problems you want in the result (optional)
   
   ![image](https://user-images.githubusercontent.com/70953107/137979948-24a0a9bd-244e-4e2e-be63-ee160c808741.png)
   
 - Click on generate list button

   ![image](https://user-images.githubusercontent.com/70953107/137980055-a5b0c5e3-497e-462b-90ec-6ec1d7f902c2.png)

## Awesome feature

  - On providing friends handles, the algorithm changes to find problems that the user has not done and provided friends have.
  
      - So for the above query if you provide some random handle like lpf666 who has done Diameter of graph and Hemose shopping problem and as they are not done by the user they get displayed. 
      - Here we get a msg also because we have queried for 4 questions but there are only 2 questions which meets the problem filtering criteria.
  
 ![image](https://user-images.githubusercontent.com/70953107/137980709-ab7b8e60-5021-408d-b8b8-99ef59356046.png)
 
## Note
  - These results are liable to change as the above mentioned handles can solve more problems.



