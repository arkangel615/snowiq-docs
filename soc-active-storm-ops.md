---
layout: page
title: Active Storm Ops
author: EastBanc Technologies
name: EastBanc Technologies
email: contact@eastbanctech.com
parent: Storm Operations Center
nav_order: 2
platform: false
comments: true
---

<section id="Active-Storm-Ops" markdown="1">
# Active Storm Ops

<section id="Map-Monitoring-View" markdown="1">
## Map Monitoring View

The Map Monitoring view is the first page that users see when logging in, which can also be accessed from the navigation menu on the left under 'Active Storm Ops' option. This page is used to view near-real time visual updates during a storm event. The Map Monitoring view consists of the following elements:

  * A map based on the service area that is covered, with the borders and boundaries of a county (or other entity such as district, city, state, etc.), along with borders of depots within that entity
  * A visual of markers on the map that represent drivers, routes, road hazards, tickets, and clusters when the map is zoomed out
  * A panel to the left of the map with two tabs for Routes and their current status and Drivers and their status
  * A set of filters above the map that allow to narrow or expand what is displayed on the map

  ![Map Monitoring View](/images/soc/soc-active-storm-ops/map-monitoring-view.png){: data-lightbox="1"}

<section id="Filters" markdown="1">
### Filters

Using the filters at the top of the Map Monitoring view allows users to narrow down what is seen on the map. Setting a filter can add or remove map elements such as route outlines, routes of different priorities, and routes/drivers that belong to a specific depot. Below are the filters and their options:

<section id="Route-Status" markdown="1">
#### Route Status

The Route Status filter allows users to view any routes set to a specific status during an assignment.

  * Unassigned - When there are no assignments created for the route
  * In Progress - When a route has at least one assignment attached to it that hasn't been completed yet
  * Completed - The route has had its assignment(s) completed by assigned driver(s) or the inspector/supervisor manually set the route to 'Completed' 
  * Inspected - The route has had its assignment verified and finalized by an inspector

![Route Status Filter](/images/soc/soc-active-storm-ops/route-status-filter.png){: data-lightbox="2"}
</section>

<section id="Priority" markdown="1">
#### Priority

The Priority filter allows users to view only specific route details and segments based on their priority. The route segments are displayed as color coded lines on the map.

Emergency (Red) – These routes have priority over Residential routes. When selected in an assignment, it must be worked on first. 

Residential (Orange - neighborhood and Blue - primary) – These routes are for all route boundaries not included in the emergency selection.

Route segments (map layer). Routes are represented by different type of route segments: Emergency - Red, Primary - Blue, Neighborhood - Orange

![Priority Filter](/images/soc/soc-active-storm-ops/priority-filter.png){: data-lightbox="3"}
</section>

<section id="Depot" markdown="1">
#### Depot

The Depot filter allows users to select a depot within the county which narrows down what drivers and routes are displayed on the map and on the tabs to the left of the map.

![Depot](/images/soc/soc-active-storm-ops/depot.png){: data-lightbox="4"}
</section>
</section>
</section>

<section id="Routes-Tab" markdown="1">
## Routes Tab

The Routes tab located to the left of the map, as seen below, displays a list of routes with their corresponding route name/number and a status indicator (color coded – see markers), the total number of miles on the route, and the percentage of completion if there is an active assignment. Applying Filters above the map will filter the routes on this tab as well. Clicking on any of the route labels within the tab focuses on that single route on the map.

![Routes Tab](/images/soc/soc-active-storm-ops/routes-tab.png){: data-lightbox="5"}
</section>

<section id="Drivers-Tab" markdown="1">
## Drivers Tab

The Drivers tab to the right of the Routes tab, as seen below, displays a list of Drivers with their names and statuses (color coded – see markers and Status Descriptions). When selecting a Driver from the list, their details will be shown above their icon located on the map as seen below. It provides additional details like the Driver's photo, Supervisor name, and the last time the Driver was seen using the Driver App (DA). 

![Drivers Tab](/images/soc/soc-active-storm-ops/drivers-tab.png){: data-lightbox="6"}

Clicking on the Blue arrow to the right of the Driver name produces the Driver's Profile panel, as seen below, with even more details.

![Driver Profile Panel](/images/soc/soc-active-storm-ops/driver-profile-panel.png){: data-lightbox="7"}
</section>

<section id="Markers" markdown="1">
## Markers

![Markers](/images/soc/soc-active-storm-ops/markers.png){: .width-xl}{: data-lightbox="8-group"}
![Markers1](/images/soc/soc-active-storm-ops/markers1.png){: .width-xl}{: data-lightbox="8-group"}
</section>

<section id="Clusters" markdown="1">
## Clusters

On the Map Monitoring view,  when a user zooms outs, markers with numbers inside them appear called 'clusters' that de-clutter the map and group together like markers. Clicking on a cluster allows the user to zoom in on that area and view the separated markers on the map. 
</section>
</section>
