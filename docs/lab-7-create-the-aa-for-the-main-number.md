# Lab 7: Create the AA for the main number

In this lab, you will learn how to create and configure an auto attendant.

**1. Agents should have access only to features necessary for their roles on their desktops.**

*Services > Calling > Features > Auto attendant > Add New*

Create an auto attendant for the main number

- Location: VitaCrunch
- Name: Main AA
- Phone Number: Main Number
- Extension: 202
- Language: English
- Business Hours Schedule: Open Hours
- Holiday Schedule: None
- Business Hours Menu
    - Disable extension level dialing
    - Option 1: Transfer without prompt: Extension 201 Sales Queue
    - Option 2: Transfer with prompt: Extension 203 Factory HG
    - Option 3: Transfer with prompt: Extension 204 Logistics HG
    - Option 4: Transfer to operator: Extension 101 Ricardo Filice
    - Option 5: Repeat
    - Option 6: Exit
    - Menu timeout and repeat configuration
        - Repeat on no input: 1 time
        - Action after all repeat attempts: Transfer call to operator: Extension 101 Ricardo Filice
- After Hours Menu
    - Option 1: Transfer without prompt: – Extension 600 VCVmailGroup
    - Menu timeout and repeat configuration
        - Repeat on no input: 1 time
        - Action after all repeat attempts: End the call
- Business Hours Greeting
    - Custom Greeting: Use text-to-speech
    - Label: AADay
    - Text:

        ```text
        Thank you for calling VitaCrunch. Please use the following menu to direct your call. Press 1 for Sales. Press 2 for the factory. Press 3 for Logistics. Press 4 or wait in the line to talk with an operator. Press 5 to Repeat menu. Press 6 to Exit menu.
        ```

- After Hours Greeting
    - Custom Greeting: Use text-to-speech
    - Label: AANight
    - Text:

        ```text
        Thank you for calling VitaCrunch. Our offices are closed. Please call back during our business hours or press 1 to leave a voicemail.
        ```


**Help Article Links**

- [Auto Attendant](https://help.webex.com/en-us/article/nsioxoi/Manage-auto-attendants-in-Control-Hub)


!!! danger "STOP: End of Lab 7"
    Wait for instructions before proceeding.
