# Lab 5: Configuring Calling Features

In this lab, you will learn how to create a voicemail group, operating modes, announcements, and hunt groups.

**1. Calls outside of business hours need to route to a voice mailbox that all employees can access.**

*Services > Calling > Features > Voicemail group > Add New*

- Create a voicemail group
- Location: VitaCrunch
- Name: VCVmailGroup
- Extension: 600
- Passcode: 258011

**2. During unexpected office closures, calls to the auto attendant will need to be routed to voicemail on demand by an end user.**

Services > Calling > Features > Operating Mode > Add New

- Create an operating mode to route to voicemail
- Location: VitaCrunch
- Name: EmergencyClosure
- No schedule
- Forward destination: VCVmailGroup Ext 600

**3. Some call routings require announcements.**

*Services > Calling > Features > Announcements > Add New > Text to speech*

- Create a greeting for the VitaCrunch Foods Factory queue
    - Level: Location
    - Location: VitaCrunch
    - Label: Welcome Factory
    - Text:

        ```text
        Welcome to VitaCrunch Foods Logistics, a representative will be with you soon.
        ```

        - Generate and listen to the file before saving.
  
- Create a greeting for the VitaCrunch Foods Logistics queue
    - Level: Location
    - Location: VitaCrunch
    - Label: Welcome Logistics
    - Text:

        ```text
        Welcome to VitaCrunch Foods Logistics, a representative will be with you soon.
        ```

        - Generate and listen to the file before saving.

**4. The Factory needs an internal Hunt Group.**

*Services > Calling > Features > Hunt Group > Add New*

- Create a Hunt Group for the VitaCrunch Foods Factory
- Location: VitaCrunch
- Name: Factory HG
- Extensions: 203
- Routing: Simultaneous
- Routing Options: Advance when busy
- Assign Rebekah Barretta and Kellie Melby

**5. The Logistics department needs an internal Hunt Group.**

*Services > Calling > Features > Hunt Group > Add New*

- Create a Hunt Group for the VitaCrunch Foods Logistics department
- Location: VitaCrunch
- Name: Logistics HG
- Extensions: 204
- Routing: Circular
- Routing Options: Advance when busy
- Assign Stefan Mauk and Eric Steele

**Help Article Links**

- [Voicemail Group](https://help.webex.com/en-us/article/mcjd4u/Manage-a-shared-voicemail-and-inbound-fax-box-for-Webex-Calling)
- [Operating Modes](https://help.webex.com/en-us/article/fozeml/Call-routing-based-on-operating-modes-in-Webex-Calling)
- [Announcement Files](https://help.webex.com/en-us/article/n5y120ab/Manage-Announcement-Repository)
- [Manage Hunt Groups](https://help.webex.com/en-us/article/o6rfjeb/Manage-hunt-groups-in-Control-Hub)


!!! danger "STOP: End of Lab 5"
    Wait for instructions before proceeding.
