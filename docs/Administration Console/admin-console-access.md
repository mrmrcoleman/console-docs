# Admin Dashboard Access Set Up

## Account Setup

The NetBox Cloud team will set up your account with your email address as the username, and you will use this to access the cloud admin dashboard. Access to the dashboard is secured using a TOTP (time-based one time password) which you need to generate using an Authenticator app such as Google Authenticator or Authy. 

To complete the set up of your account for access to the admin dashboard, follow these steps: 

1. You will receive an email advising you of your username, along with a temporary password and a link to the console URL. Click the link to login

2. Enter the username (your email address) and the temporary password as per the email, and click ‘Sign in’: 

    ![temp password signin](../images/dashboard_access/temp_password_signin.png)

3. You will then be prompted to change your password: 

    ![change password](../images/dashboard_access/change_password.png)

4. Next, add NetBox Cloud to your authenticator app of choice, by scanning the QR code from within the app. Then enter the TOTP code from your authenticator app, and click confirm:

    ![set up totp](../images/dashboard_access/set_up_totp.png)

5. The TOTP set up is now complete and you are logged into the NetBox Cloud Admin Dashboard. You will see (and be able to administer) the instances running under your Organization: 

    ![view instances](../images/dashboard_access/instances_view.png)

6. That is the set up complete and the next time you log in you will need to enter your email address, the updated password (from step 3), and then you will see the prompt for the TOTP, so enter this from your authenticator app and click ‘Confirm’: 

    ![confirm totp](../images/dashboard_access/confirm_totp.png)

7. To retrieve the password for the Admin user account for the NetBox Cloud web interface, first launch the admin console, by clicking on the link to the instance:

    ![view instances](../images/dashboard_access/instances_view.png)

    Then scroll down to the ‘Secrets’ section, and click the blue eye icon to reveal the secrets:

    ![retrive admin password](../images/dashboard_access/retrieve_admin_pwd_2.png)

8. Once the secrets are revealed, then you can copy the admin user password to your clipboard:

    ![retrive admin password](../images/dashboard_access/retrieve_admin_pwd_3.png)

9. Then click the green globe icon in the top right corner of the dashboard (underneath the instance name) to open the URL for your instance’s web interface: 

    ![launch ui](../images/dashboard_access/launch_ui.png)

10. Login with the Admin user account, username of ‘admin’, and the password you have copied from step 8: 

    ![admin login](../images/dashboard_access/admin_login.png)