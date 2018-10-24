---
layout: leftnav-page-content
title: Changing content
permalink: /navigation-bar/changing-content/
breadcrumb: Navigation Bar - Changing content
collection_name: resources
second_nav_title: "Navigation bar"
---
#### **Step-by-step guide to change content for your navigation and footer bar**
![Changing Text for your Navigation Bar](/images/resources/changing-content-for-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Change the content by amending the section below inside navigation.yml
* Click on "Commit changes" button


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
