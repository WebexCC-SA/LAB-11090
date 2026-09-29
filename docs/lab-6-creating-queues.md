# Lab 6: Creating Queues

In this lab, you will learn how to create and configure a call queue. Assign the supervisor role to a user.

**1. Callers to the Sales Queue number should be placed on hold until an agent is available.**

*Services > Calling > Features > Call Queue > Add New*

Create the Sales Call Queue

- Location: VitaCrunch
- Name: Sales Queue
- Number: Assign an available number
- Extension 201
- Enable: Allow agents to use call queue number as caller ID
- Number of calls in queue: 15
- External caller ID phone number: Direct Line
- Routing: Priority Based – Longest Idle
- Overflow Settings:
    - Transfer to phone number: Extension 600 PR\_VmailGroup
    - Enable overflow after 60 seconds
- Welcome Message:
    - Welcome Message is mandatory: Enabled
        - Custom Greeting: TTS
        - Label: Welcome Sales
        - Text: Welcome to the VitaCrunch Sales Queue. An agent will be with you soon.
        - Generate and listen to the file before saving.
- Comfort Message: Enabled
    - Time between comfort message: 15 seconds
- Hold Music: Enabled
- Agents:
    - Enable: Allow agents on active calls to take additional calls.
    - Enable: Allow agents to join or unjoin the queue.
    - Taylor Bard, Ricardo Filice, Kellie Melby

**2. Sales Queue has additional settings.**

Select the Sales Queue to configure additional features.

- Queue Policies - Night Service
    - Enable Night Service:
    - Transfer to Phone number: Extension 600 (VmailGroup)
    - Business Hours: Open Hours schedule
- Queue Policies - Stranded Calls
    - Night Service: selected

**3. Eric Steele needs to supervise the members of the Sales Queue.**

*Services > Calling > Features > Call Queue > Supervisors > Add Supervisor*

- Select Eric Steele as Supervisor
    - Select all Agents to assign to Eric Steele

**4. Assign Operating mode to the Sales Queue.**

*Services > Calling > Features > Call Queue > Select Sales Queue*

- Open call Forwarding
    - Forward calls by modes: select Emergency Closures

**Help Article Links**

- [Call Queue](https://help.webex.com/en-us/article/nzkg083/Webex-Customer-Experience-Basic)
- [Operating Modes](https://help.webex.com/en-us/article/fozeml/Call-routing-based-on-operating-modes-in-Webex-Calling)
- [Announcement Files](https://help.webex.com/en-us/article/n5y120ab/Manage-Announcement-Repository)


!!! danger "STOP: End of Lab 6"
    Wait for instructions before proceeding.
