# ServiceDesk-Simulator
I am utilizing ServiceDesk-Simulator in order to gain real world experience in solving tickets for end users.

## Scenario 1: Moved to a new team and cannot access their files or folders

1. Scenario Overview

<p align="center">
  <img src="scenario1images/ServiceDesk-Scenario-1-Ticket.png" width="600" alt="Scenario Prompt"><br>
  <em>Figure 1. Initial ticket.</em>
</p>

2. Initial Assessment

* Kavita Patel's manager submitted a ticket as she was transferring departments and needed access to a new set of tools specific to that department. The manager also requested that she be removed from the old group as well. Transferring groups can be done in Active Directory.

3. Investigation/Resolution

* The first step that I took check the Active Directory and search up Kavtia Patel.
<p align="center">
  <img src="scenario1images/Scenario1-Pic1.png" width="500" alt="Active Directory"><br>
  <em>Figure 2. Active Directory Search.</em>
</p>

* Once I clicked on her name, I went to the "Groups" tab and found that she was under "Engineering".
<p align="center">
  <img src="scenario1images/Scenario1-GroupsBefore.png" width="500" alt="Engineering Group"><br>
  <em>Figure 3. Engineering Group.</em>
</p>

* I then removed her from the "Engineering" group to the "IT Infrastructure" group.
<p align="center">
  <img src="scenario1images/Scenario1-GroupsAfter.png" width="500" alt="IT Infrastructure Group"><br>
  <em>Figure 4. IT Infrastructure Group.</em>
</p>

* Lastly, I messaged her manager Tom Wilson, who submitted the ticket to confirm whether or not the changes were submitted correctly.
<p align="center">
  <img src="scenario1images/Scenario1-UserConfirmation.png" width="350" alt="User Confirmation"><br>
  <em>Figure 5. User Confirmation.</em>
</p>

<p align="center">
  <img src="scenario1images/Scenario1-ManagerConfirmation.png" width="350" alt="Manager Confirmation"><br>
  <em>Figure 6. Manager Confirmation.</em>
</p>

4. Lessons Learned

* Department transfers require removing old groups and adding new ones
* Not removing access to old group memberships provides a security risk as they have accesss that is no longer necessary
* Always need to verify if the transfer request comes from an authorized user
* Make sure to document every change like who requested it and when

5. Technologies Used

* Active Directory

## Scenario 2: New employee starting Monday - needs account setup

1. Scenario Overview

<p align="center">
  <img src="scenario2images/Scenario-2-Ticket.png" width="600" alt="Scenario Prompt"><br>
  <em>Figure 1. Initial ticket.</em>
</p>

2. Initial Assessment

* Robert Torres submitted a ticket for a new hire with the name of Jennifer Torres. He provided all of the employee's relevant details and outlined which sepcific groups that she needs to be included in to gain specific access.

3. Investigation/Resolution

* The first step that I took was to go to Active Directory to create a profile for Jennifer.

<p align="center">
  <img src="scenario2images/Scenario1-Pic1.png" width="500" alt="Active Directory"><br>
  <em>Figure 2. Active Directory Search.</em>
</p>

* 
4. Lessons Learned
