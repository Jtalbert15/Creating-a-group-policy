# Creating-a-group-policy

For this lab we need to log in to our Windows Server 2019 VM

<img width="633" alt="Screenshot 2024-05-21 at 7 33 21 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/d45073e3-eec9-4660-b33a-21abd1965088">

Now we will click on Tools in the top right of the screen

<img width="635" alt="Screenshot 2024-05-21 at 7 34 18 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/7900b546-cc8a-4fbe-8429-1f92753ac468">

Click on Group Policy management 

<img width="634" alt="Screenshot 2024-05-21 at 7 35 25 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/bbffc061-1899-40f0-8041-c8ca28d77405">

Double click on domains

<img width="637" alt="Screenshot 2024-05-21 at 7 38 11 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/a601a323-b135-418c-ac60-281244a131b0">

Double click on ITLab.org (yours will be the name of your domain

<img width="636" alt="Screenshot 2024-05-21 at 7 40 10 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/51006510-938c-4363-83e7-34e13c9c7f01">

From here under the Domains folder on the left we are going to right click on our domain name

<img width="636" alt="Screenshot 2024-05-21 at 7 41 06 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/f8aaf05a-99f2-4f0b-a279-da8b9d2e53cb">

Click create a GPO in this domain, and link it here

<img width="637" alt="Screenshot 2024-05-21 at 7 42 00 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/6e5bd2c8-9406-48fe-a1fc-9159c27ba6ad">

Give your Group policy object a name

<img width="635" alt="Screenshot 2024-05-21 at 7 43 54 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/e5372a78-8a5f-491b-8bd0-dddb7fb25b3d">

Now we can right click on our group policy and click the edit

<img width="635" alt="Screenshot 2024-05-21 at 7 45 13 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/0372e6b6-5c91-4cae-941d-7a1a9efa3015">

Now we can set policies or preferences for our users and computers. We can then assign these policies to different users.

<img width="638" alt="Screenshot 2024-05-21 at 7 45 53 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/ec71a2b6-86c7-456e-bdea-51e4e932a32c">

Lets create a user policy. Click on policies under user configuration

<img width="627" alt="Screenshot 2024-05-21 at 7 57 32 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/428b0a66-304e-4d6c-ae04-212505287a92">

Double click on Administrative Templates 


<img width="633" alt="Screenshot 2024-05-21 at 8 13 10 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/e745d6c8-9933-4d88-85d2-d05cd2168749">

Double click on Desktop

<img width="636" alt="Screenshot 2024-05-21 at 8 16 53 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/6e34cc48-2f44-4682-ab3b-e5936d285a88">

Double Click on Remove Recycle Bin icon from desktop

<img width="635" alt="Screenshot 2024-05-21 at 8 17 56 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/4db16f5c-00f8-4d0f-b29c-7beaeedcb096">

Click Enabled on the top left and then Apply in the bottom right. You may then click ok.

<img width="632" alt="Screenshot 2024-05-21 at 8 20 16 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/e84e3eed-6238-49ba-8e82-488dff08d2cf">

Now lets apply this Group Policy to the user we created click add... under security filtering

<img width="634" alt="Screenshot 2024-05-21 at 8 23 10 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/4ca89cd5-b72f-4966-827e-531d672bc666"> 

Enter the name of the user and click check names. Then click ok

<img width="637" alt="Screenshot 2024-05-21 at 8 24 20 PM" src="https://github.com/Jtalbert15/Creating-a-group-policy/assets/66844406/6a7f08e8-2ff2-498c-aa02-f1593efd3dad">

Now when that user logs in he will not have a recycle bin


