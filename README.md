# najva B4a Application
This is a B4a application that NajvaSdk implemented in it.

### Test Najva Service in B4a
If you want test Najva Push Notification Service in b4a application you should:

1.  Clone this project and rename package name of it 

2.  Register this app after login in [najva panel](https://app.najva.com/accounts/login/?next=/).(to register any app, its package name must be unique!)

3.  After register najva panel gives you campaignId,websiteId,apiKey which is specific to your app

4.  Change the code to be like this 

```
Sub Activity_Create(First_Time As Boolean)
    najva.initialize(YOUR_CAMPAIGN_ID_GOES_HERE, YOUR_WEBSITE_ID_GOES_HERE, YOUR_API_KEY_GOES_HERE);
End Sub
```

5.  Now you can run application and send notification from your panel to it!
