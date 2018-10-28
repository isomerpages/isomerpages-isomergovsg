---
layout: leftnav-page-content
title: Creating 2nd level nav to your navbar
permalink: /navbar-and-footer/creating-2nd-level-nav/
breadcrumb: Navbar and Footer - Creating 2nd level nav
collection_name: documentation
second_nav_title: "Navbar and Footer"
---
#### **Step-by-step guide to create a 2nd level nav on your navbar**
![Adding second level nav](/images/resources/adding-second-level-item-to-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Copy the code snippet below into navigation.yml
* Change the url to your target page permalink
* Click on "Commit changes" button

```
# Sample code snippet for you to create a 2nd level nav

- title: Digital Gov Transformation
  url: /digital-government-transformation/
  sub-links:
  - title: Overview
    url: /digital-government-transformation/
  - title: Digital Government Blueprint
    url: /digital-government-blueprint/
    
# Sample code snippet for you to create a 2nd level nav linking to external website
    
- title: Digital Gov Transformation
  url: /digital-government-transformation/
  sub-links:
  - title: Overview
    url: /digital-government-transformation/
  - title: Digital Government Blueprint
    url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl 
    external: true
```
