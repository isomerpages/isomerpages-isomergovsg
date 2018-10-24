---
layout: leftnav-page-content
title: Adding 1st level nav
permalink: /navigation-bar/adding-1st-level-nav/
breadcrumb: Navigation Bar - Adding 1st level nav
collection_name: resources
second_nav_title: "Navigation bar"
---
#### **Step-by-step guide to add 1st level nav to your navigation bar**
![Adding first level nav](/images/resources/adding-first-level-item-to-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

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
