# Lab 9: Test main call routing and features

In this lab, you will test the Auto Attendant and log in as Ricardo Filice to the User Hub to test the operating mode feature.

**1. Call the main number and test routing options.**

- Call the main number using your mobile phone.
    - Select 1 for the Sales Queue
    - Hold music will play because no agents are logged into the Support Queue to take your call.
    - The default comfort message will play every 15 seconds. “Your call is very important to us. Please wait for the next available agent.”
    - Close the call.

**2. Login with Ricardo Filice’s credentials in the Webex app or configure the Cisco 9871 phone using activation code.**

- There are 2 options. You may use the Webex app over your lab computer, or use the device provided in your desk. You may use both.
- Ricardo Filice email is available in user management, and the password is the same as the administrator. All users use the same password in your organization.
- If you want to configure the phone, use the activation code you copied from Lab 4.

**3. Call the main number and test routing options.**

- Call the main number using your mobile phone.
    - Select 1 for the Sales Queue
    - Answer the call as Ricardo Filice
- Call the main number
    - Choose different options to hear the difference between transfer call and without prompts.
- Call the main number. Do not make a selection.
    - You will hear the menu twice then an additional prompt.
    - The call will transfer to Ricardo Filice because he is the operator.

**4. Log in as Ricardo Filice in the user portal.**

- Open user.webex.com in the browser and login as Ricardo Filice.
- Go to Settings > Calling > Features > Mode Management
- Select the Sales Queue
    - Switch Mode
    - EmergencyClosure
- Call the main number, try the Sales Queue option 1. It should route to voicemail.
- In the Mode Management list, click on the Sales Queue. Switch mode back to normal.
- Optionally, if you activated your Cisco phone, test the operating mode using the corresponding key.

**5. If you activated the Cisco phone, please delete the device from Control Hub.**

- As Charles Holland, go back to Devices, select the Ricardo Filice’s phone and delete it under the actions button.


!!! danger "STOP: End of Lab 9"
    Wait for instructions before proceeding.
