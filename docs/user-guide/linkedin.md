__To register an application on LinkedIn, please follow the steps below:__

1. Login to [LinkedIn](https://www.linkedin.com/) and go to Page [LinkedIn App](https://www.linkedin.com/secure/developer) to create application
    <div class="soclall-br"></div>
    ![Linkedin : List App](/img/linkedin-1-list-app.JPG)
    <div class="soclall-br"></div>
2. Press button "Add New Application" and fill the application form with the below information
    * Website URL: __http://soclall.com/__
3. Then, check to agreement checkbox and press button "Submit".
    <div class="soclall-br"></div>
    ![Linkedin : Create App Form](/img/linkedin-2-create-app-form.jpg)
    <div class="soclall-br"></div>
4. After create application success, select menu "Authentication" and go to "Authentication" page.
5. In session "Default Application Permissions", please check:
    * r_basicprofile: if you want to use "SoclAll Login"
    * r_emailaddress: if you want to use "SoclAll Invite"
    * w_share: if you want to use "SoclAll Posting"
6. In session "OAuth 2.0", fill "Authorized Redirect URLs" field: __http://api.soclall.com/callback__ and press button "Update".
    <div class="soclall-br"></div>
    ![Linkedin : Authentication Page](/img/linkedin-3-authentication-page.jpg)
    <div class="soclall-br"></div>    
7. In "Authentication" page, you can get the "Client ID" and "Client Secret" to fill SoclAll LinkedIn Settings form.