# Lab 2: Location Settings

In this lab, you will learn to edit locations, assign PSTN connections, manage PSTN, and location settings.

**1. The main location should be renamed appropriately.**

*Management > Location > dCloud > Location info > Small pencil icon*

- Rename dCloud Location
    - Location name: VitaCrunch

**2. VitaCrunch Foods will use the Cisco Calling Plans as PSTN option.**

*Management > Locations > VitaCrunch > PSTN > PSTN Configuration > PSTN connection > Manage*

- Assign PSTN Connection to the location
    - Location: VitaCrunch
    - Connection Type: Cisco Calling Plans
    - Contract Information: Charles Holland – admin@admin.com
    - Authorized Contact: Charles Holland
    - Job title: Admin
    - Service Address: Do not change

**3. The location needs 5 numbers.**

*Services > PSTN & Routing > Numbers > Add numbers*

- Order and add numbers
- Location: VitaCrunch
- Number Type: PSTN
- Select an area code from the list (*if you don’t see this option, be sure to scroll down in the center section of the screen)*
- Order 5 numbers
- IMPORTANT: Once you have ordered numbers, click view orders
    - Click on the pending order to automatically change the status to provisioned
    - You can also go to *Services > PSTN & Routing > PSTN orders* to find the order if you closed the order confirmation screen too quickly.

**4. To make and receive calls, the location needs a main number.**

*Management > Locations > VitaCrunch > PSTN > PSTN Configuration > Main number*

- Assign a main number to VitaCrunch
- Select one of the available numbers
- Make a note of the number for a subsequent lab

**5. VitaCrunch users will need to use voicemail.**

*Management > Locations > VitaCrunch > Calling > Calling features settings > Voice portal*

Configure the voice portal

- Voice portal name: VitacrunchVP
- Incoming Call:
    - Phone number: Any number not selected as the main number
    - Extension: 200

**6. Calls to certain features will need to route to specific options based on the time of day.**

*Management > Locations > VitaCrunch> Calling > Calling features settings > Schedules*

Create a schedule for VitaCrunch

- Name: Open Hours
- Schedule Type: Business Hours
- Monday – Friday 7:00 am – 8:00 pm
- Make sure to turn off the lunch schedule!

**Help Article Links**

- [Setup Cisco Calling Plan](https://help.webex.com/en-us/article/nousk9ab/Get-Started-with-the-Cisco-Calling-Plan#Cisco_Task_in_List_GUI.dita_36fcaf64-4bcd-4eda-a968-ad59c7887905)
- [Assign Location Main Number](https://help.webex.com/en-us/article/f661ju/Change-the-Main-Phone-Number-for-a-Location)
- [Configure Voice Portal](https://help.webex.com/en-us/article/nojp8ej/Configure-voice-portals-for-Webex-Calling-in-Control-Hub)
- [Create Schedules](https://help.webex.com/en-us/article/bx6j0h/Create-schedules-in-Control-Hub)


!!! danger "STOP: End of Lab 2"
    Wait for instructions before proceeding.
