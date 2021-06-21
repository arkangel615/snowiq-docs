---
layout: page
title: Login and Navigation
author: EastBanc Technologies
name: EastBanc Technologies
email: contact@eastbanctech.com
parent: Driver App
nav_order: 1
---

<details open markdown="block">
  <summary>
    <b>Table of contents</b>
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

# Login and Navigation
## Login <a name="-Login"></a>
The login screen below allows Driver users to enter the SnowIQ Driver Application (DA). Click the appropriate 'Login' button to be re-routed to enter the assigned username and password for the application.

![Screenshot 2021-03-02 131014](https://user-images.githubusercontent.com/79857237/109695112-8cd4e380-7b59-11eb-8c83-716743ad6fdf.png)

Once logged into the DA, Drivers will see the screen below. The screens display two types of Drivers logged in, a County Driver and a Contractor. The difference is identified in the status of the Driver. The County Driver, on the left, has a status of 'Ready' whereas the Contractor, on the right, is in 'Standby.' The circle next to the profile picture indicates that this a County Driver and a square is a Contractor. These icons are color coded to match the status.

![Screenshot 2021-03-03 100742](https://user-images.githubusercontent.com/79857237/109826057-6cb02d80-7c08-11eb-963d-7aa5d8c4175c.png)
![Screenshot 2021-03-03 100807](https://user-images.githubusercontent.com/79857237/109826066-6f128780-7c08-11eb-8104-982e42fc8283.png)

## Navigation <a name="-Navigation"></a>
The diagram below highlights basic navigation controls and map elements of the Driver App.

![Screenshot 2021-03-02 131342](https://user-images.githubusercontent.com/79857237/109694808-3667a500-7b59-11eb-8c58-4471ea1129be.png)

1. User Profile Picture, Name, and Status – pressing on the Profile picture opens the Navigation Drawer 
2. Weather widget – automatically updated based on location
3. Status bar  
   * If it is on active assignment, as seen in this diagram, the status bar includes the route number or address being worked, number of miles on the assignment, percentage completed, status of the assignment and progress bar

   * If it is in between assignments or no assignments, the system will display the appropriate notification to the user. 
5. Map – based on the TBD
6. "My current location on the map" pin
7. Button to create Road Hazards
8. Navigate button to get directions to the location from Google Maps
9. Another Driver marker in near-real time with current status color coded 
10. Route segments assigned to the Driver to work on. Routes are represented by different type of route segments: 
    * Emergency - red
    * Primary - blue
    * Neighborhood - orange
  
12. Breadcrumbs (green colored) appear in near-real time over the Route that the Driver has worked on already 
13. Road hazard marker
14. Button "Find my location on the map"

## Navigation Drawer <a name="-Navigation-Drawer"></a>
Users can open the Navigation Drawer by pressing the User Profile picture icon as specified in the diagram above. The panel is divided into three sections:
#### User Profile details <a name="-User-Profile-details"></a>
This section lists the profile details of logged in driver. To edit them, the user can press 'Profile' in the section below.

#### Supervisor details <a name="-Supervisor-details"></a>
Each driver has a Supervisor they report to and who assigns them work. The Supervisor's name and phone number are listed in this section, with the ability to contact the Supervisor directly from within the app, by pressing the green phone icon.

#### Operations menu <a name="-Operations"></a>
The Operations Menu as seen above is for a Driver without any active or future assignments. If a driver receives an assignment or needs to complete an active assignment, an actionable option will be added to the menu, which can be seen here.

![Screenshot 2021-03-02 132549](https://user-images.githubusercontent.com/79857237/109696248-d671fe00-7b5a-11eb-8e2a-61ad4544589e.png)

## Assignments <a name="-Assignments"></a>
A user can press on Assignments' to view the Active Assignment, if there is one, any Future Assignments in the queue, and the History of assignments the driver worked on.

![Screenshot 2021-03-10 122607](https://user-images.githubusercontent.com/79857237/110672601-cfbc3a00-819d-11eb-9622-a5153ba5c232.png)

## Profile <a name="-Profile"></a>
A user can press on 'Profile' to edit their name, phone number, and User Picture.

![Screenshot 2021-03-02 134830](https://user-images.githubusercontent.com/79857237/109698975-ffe05900-7b5d-11eb-8ea6-13c55b2c8a66.png)

## Salt Management <a name="-Salt-Management"></a>
A Driver user can press on 'Salt Management' to record how much salt was loaded and returned by pressing 'Add Salt Usage Info.' The historical usage is saved in the list, as seen below. 

![Screenshot 2021-03-02 135028](https://user-images.githubusercontent.com/79857237/109699211-46ce4e80-7b5e-11eb-8005-cbc2a66637a7.png)

## About <a name="-About"></a>
Displays the current version of the app.

## Logout <a name="-Logout"></a>
A user must logout at the end of each workday.