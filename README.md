Implementing the Azure AD multi-factor authentication, Azure AD conditional access, Azure AD Identity Protection with Azure Active Directory.

Task1 : I deployed an Azure VM by using an Azure Resource Manager template (azuredeploy.json) in USEast



Task 2: I implemented Azure MFA for User1 by activating Azure AD Premium P2 trial in a new tenant


Step 1: Created a new Azure AD tenant

Step 2: Activated Azure AD Premium P2 trial in the new tenant

Step 3: Created 3 Azure AD users. The first user has Global admin role while the other 2 have is User role

Step 4: Assigned Azure AD Premium P2 licenses to Azure users

Step 5: Configured Azure MFA settings for User 1 and set up fraud alerts

Step 6: Validated MFA configuration by testing sign in of user1 user account using an inprivate browser
<img width="960" alt="aad1user login successful" src="https://user-images.githubusercontent.com/110430121/192353074-75dca0e4-69dc-4963-a5e7-eac936096ea0.png">

Task 3: I Implemented Azure AD Conditional Access Policies for User 2


Step 1: Created a policy that requires MFA when signing in to the Azure portal for user 2

Step 2: Tested the conditional access policy and it required me to use MFA when signing in as user 2 using an  inprivate browser


Task 4: Implement Azure AD Identity Protection for User3


Step 1: Viewed Azure AD Identity Protection options in the Azure portal ie New risky users detected and New risky sign-ins detected

Step 2: Configure a user risk policy for all user3 a nd requirde password change

Step 3: Configured a sign-in risk policy for all users

Require multi-factor authentication

Task 4: Simulate risk events against the Azure AD Identity Protection policies

Use RDp to connect to vitual machine and sighin to azure as user 3 with tor browser




 

















































 














































