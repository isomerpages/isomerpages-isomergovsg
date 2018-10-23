---
layout: leftnav-page-content
title: Managing content for your navigation bar
permalink: /managing-content-for-your-navigation-bar/
breadcrumb: Managing content for your navigation bar
collection_name: resources
---

#### **Navigation and Footer Bar**

---

#### **Step-by-step guide to change content for your navigation and footer bar**
![Changing Text for your Navigation Bar](/images/resources/changing-content-for-your-navigation-bar.gif)

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Change the content by amending the section below inside navigation.yml
* Click on "Commit changes" button

<font color="red"><b>Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect</b></font>
```
# Sample navigation.yml file section for reference

- title: Who We Are
  url: /who-we-are/
- title: Digital Gov Transformation
  url: /digital-government-transformation/
  sub-links:
  - title: Overview
    url: /digital-government-transformation/
  - title: Digital Government Blueprint
    url: /digital-government-blueprint/
- title: Contact Us
  url: /contact-us/
```



#### **Step-by-step guide to add 1st level nav to your navigation and footer bar**
![Adding first level nav](/images/resources/adding-first-level-item-to-your-navigation-bar.gif)

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Copy the code snippet below into navigation.yml
* Update the content accordingly
* Click on "Commit changes" button

```
# Sample code snippet for you to create a 1st level nav

- title: Who We Are
  url: /who-we-are/
  
# Sample code snippet for you to create a 1st level nav with external link

- title: Who We Are
  url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl
  external: true
```


#### **Step-by-step guide to add 2nd level nav to your navigation and footer bar**
![Adding second level nav](/images/resources/adding-second-level-item-to-your-navigation-bar.gif)

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Copy the code snippet below into navigation.yml
* Update the content accordingly
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
    
# Sample code snippet for you to create a 2nd level nav    
    
- title: Digital Gov Transformation
  url: /digital-government-transformation/
  sub-links:
  - title: Overview
    url: /digital-government-transformation/
  - title: Digital Government Blueprint
    url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl 
    external: true
```
