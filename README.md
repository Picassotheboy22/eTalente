# eTalente Assessment
Junior Test Analyst

## Qusestion 1
1.	The first scenario, I documented when going through the login page was the forgotten password function which users really rely on if they have an existing account.
 - The first issue here is that the system will still say that a link to reset the password has been sent even though the 
   email does not exist.
![Screenshot 2024-04-08 111713](https://github.com/Picassotheboy22/eTalente/assets/166037734/d57d5270-ae61-4b4f-918a-c34aa78e306f)

- The second thing is that the system should clearly state to the user if the email does not exist on the system or if the 
  have entered the wrong password or username. If the prompt message is “invalid credentials” it is not really user friendly

     ![Screenshot 2024-04-08 111742](https://github.com/Picassotheboy22/eTalente/assets/166037734/0cd53486-2114-4ea5-88c7-52a856803845)

- The third scenario tested was to see if the username had a case sensitive validation for security reasons. If doesn’t even 
  if the “Admin” is entered as “admin” the system will allow you to login.

## Question 2
2.	Click on “Forgotten password” link.
- Expected result – Site prompts you to enter a valid/registered email address. Once the email address has been entered. 
  Email link is sent to reset password and the site goes back to home page.
- Fail Test case if the email address entered is invalid and the site displays the following message “Reset Password Link 
  sent successfully.”

## Question 3 
3.	Depending on the technology the team is using it will vary how the bug is documented. In this instance I will assume the team is using Azure DevOps to log tasks and create stories. Creating a bug task/story would be the correct way of going about it and explaining in detail how I came across the bug so that the Developer responsible for fixing it has a way to replicate it and it will be easier to track down the cause of the bug and fix it.

## Question 4
4.	This technique is known as black box testing since the tester does not know how the system works. The tester is testing what the output of the system is based on the input they provided.

## Question 5
5.	White Box testing in this case the tester knows how the is supposed to work and they can create test cases based on that.

## Question 6
6.	Based on the boundary value analysis – the valid entries would be between 0,1,50,99,100.

## Question 7
7.	It is known as exploratory testing. It’s an agile methodology it needs outside the box thinking because this process does not follow predefined test cases.


